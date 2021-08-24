create env

'''bash
conda create -n wineq python=3.7 -y
'''

activate env

'''bash
conda activate wineq
'''

create requirements file

install the req
'''bash
pip install -r requirements.txt
'''

download the data from 

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

'''bash
git init
'''

'''bash
dvc init
'''

'''bash

dvc add data_given/winequality.csv
'''

'''bash
git add .
'''

'''bash
git commit -m "first commit"
'''

onliner updates for readme
'''bash
git add . && git commit -m "modified readme file"
'''

'''bash
git remote add origin https://github.com/meghashree0396/Simple-dvc-mlflow-demo.git
'''

'''bash
git branch -M main
'''

'''bash
git push origin main
'''

tox command -
'''bash
tox
'''

for rebuilding -
'''bash
tox -r
'''

pytest command
'''bash
pytest -v
'''

setup commands -
'''bash
pip install -e .

'''

build your own package commands -
'''bash
python setup.py sdist bdist wheel
'''

'''mlflow server command -

mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 5000
