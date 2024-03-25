# Kidney-Disease-Classification-MLflow-DVC


## Workflows

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline 
8. Update the main.py
9. Update the dvc.yaml
10. app.py

# How to run?
### STEPS:

Clone the repository

```bash
https://github.com/kattela6/Kidney-Disease-Classification-Deep-Learning-Project
```
### STEP 01- Create a python environment after opening the repository

```bash
python -m venv name
```

```bash activate env
kidney/Scripts/activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

```terminal
# Finally run the following command
python app.py
```


##### cmd
- mlflow ui

### dagshub
[dagshub](https://dagshub.com/)

MLFLOW_TRACKING_URI=https://dagshub.com/kattela6/Kidney-Disease-Classification-Deep-Learning-Project.mlflow \
MLFLOW_TRACKING_USERNAME=kattela6 \
MLFLOW_TRACKING_PASSWORD=b5192d6763e717308be815b004e9b5105be05da9 \
python script.py

Run this to export as env variables:

```bash

export MLFLOW_TRACKING_URI=https://dagshub.com/kattela6/Kidney-Disease-Classification-Deep-Learning-Project.mlflow 

export MLFLOW_TRACKING_USERNAME=kattela6

export MLFLOW_TRACKING_PASSWORD=b5192d6763e717308be815b004e9b5105be05da9