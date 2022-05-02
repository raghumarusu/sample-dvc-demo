
create env

```bash
conda create -n wineq python=3.7 -y
```
activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
```
create template.py
create directory data_given
download the data from kaggle and copy to data_given

```bash
git init
```
```bash
dvc init
```
```bash
dvc add data.given/winequality.csv
```

```bash
git add .
```

```bash
git commit -m  "first commit"
```

