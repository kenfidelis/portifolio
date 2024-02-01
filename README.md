# portifolio

A portifolio website for Ekene fidelis

## Steps

1. Create a python virtual Environment --- 'python3 -m venv ~7.venv' or 'virtualenv ~/.venv' #/home/codespace/.venv
2. virtualenv ~/venv  #create venv  
source ~/.venv/Scripts/activate
deactivate
pip install -r requirements.txt
pip install fastapi uvicorn

uvicorn main:app --reload
