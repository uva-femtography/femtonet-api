# FemtoNET API
#### v1.0.0
`FemtoNET API` is a server-side library to serve up FemtoNET visualization and models.
### Installation
The cleanest way to install FemtoNET API is by using a virtual environment. If you would prefer to install the package without a virtual environment, you can ignore the sections regarding activating venv and instead run `python -m pip install -r requirements.txt` in the directory.
```bash
pip install venv
```

#### Windows
```bash
git clone https://github.com/uva-femtography/femtonet-api.git
cd femtonet-api
python -m venv api
.\femtonet-api\Scripts\activate.bat
api\Scripts\python -m pip install -r requirements.txt

```

#### Linux/Mac OSX
```bash
git clone https://github.com/uva-femtography/femtonet-api.git
cd femtonet-api
python -m venv femtonet-api 
source /femtonet-api/bin/activate (if using csh, source /femtonet-api/bin/activate.csh instead)
api/bin/python -m pip install -r requirements.txt
```
To run the code at anytime, simply return to the directory and activate the virtual environment.

### Getting Started
To run the api server, run `python app.py`. This should start the server and provide a localhost address where you can access the api. 

