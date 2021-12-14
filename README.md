# Organizational structure movements

## Install
1. Clone or download this repository
2. Create your own virtual environment and activate it.  
**Windows:**  
	* `py -m venv venv `  
	* `source venv/Scripts/activate`

	**Mac OS**:
	* `virtualenv venv`
	* `virtualenv -p /usr/local/bin/python3 venv`
	* `source venv/bin/activate`

3. Install dependencies: 
	* `pip install -r requirements.txt`
	* `pip install -r notebooks/requirements.txt`
	* `pip install -r src/requirements.txt`
	* `pip install -r api/requirements.txt`

uvicorn api.main:app --reload


export GOOGLE_APPLICATION_CREDENTIALS=$(realpath xxxx.json)

echo $GOOGLE_APPLICATION_CREDENTIALS