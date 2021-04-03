create env

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create req file

install the req
```bash
pip install -r requirements.txt
```

git init

dvc init

dvc add data_given/winequality.csv

git add.

git commit -m "first commit"

git add . && git commit -m "update readme.md file" 

one liner updates  for readme
```bash
git remote add origin https://github.com/dee-walia20/mlops_sample.git
git branch -M main
push origin main
```

tox command
```bash
tox
```
tox rebuidling
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup commands
```bash
pip install -e .
```

build your own package command
```bash
python setup.py sdist bdist_wheel
```