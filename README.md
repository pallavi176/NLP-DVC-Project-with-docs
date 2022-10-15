# dvc-project-template
NLP-DVC-Project-with-docs

## STEPS -

### STEP 01- Create a repository by using template repository

### STEP 02- Clone the new repository

### STEP 03- Create a conda environment after opening the repository in VSCODE

```bash
conda create --prefix ./env python=3.8 -y
```

```bash
conda activate ./env
```
OR
```bash
source activate ./env
```

### STEP 04- install the requirements
```bash
pip install -r requirements.txt
```

### STEP 05- initialize the dvc project
```bash
dvc init
```

### STEP 06- commit and push the changes to the remote repository

Project with Mkdocs documentations

git rm -r --cached 'artifacts\model\model.pkl'
git commit -m "stop tracking artifacts\model\model.pkl"

git rm -r --cached 'logs\running_logs.log'
