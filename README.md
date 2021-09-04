create env

```bash
conda create -n wq python=3.7 -y
```

activate env
```bash
conda activate wq 
```

created a requirements.txt file 

install the requirements.txt
```bash
pip install requirements.txt
```
get the data

Initialising git and dvc
```bash
git init
```
```bash
dvc init
```
```bash
dvc add data_given/winequality.csv
```
```bash
git add .
```

```bash
git commmit -m "first commit"
```
update for README.md file
```bash
git add. && git commit -m "update REDME.md"
```
```bash
git remote add origin https://github.com/Shuaib11-Github/App.git
```

```bash
git branch -M main
```
```bash
git push origin main 
```
