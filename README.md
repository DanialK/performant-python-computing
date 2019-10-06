# Replicate the environment and install packages
- `sudo apt update`
- `sudo apt install software-properties-common`
- `sudo apt-get install python3.7-dev python3.7-venv python3-pip`
- `python3.7 -m venv venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`


# Dask JupyterLab Extension
- `sudo apt install nodejs npm` 
- `pip install dask_labextension`
- `jupyter labextension install dask-labextension`