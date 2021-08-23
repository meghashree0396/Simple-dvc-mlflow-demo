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

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

onliner updates for readme
git add . && git commit -m "modified readme file"

git remote add origin https://github.com/meghashree0396/Simple-dvc-mlflow-demo.git

git branch -M main

git push origin main

