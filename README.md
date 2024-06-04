# Getting started with ML Flow and DagsHub

import dagshub
dagshub.init(repo_owner='manjitbaishya01', repo_name='Getting-Started-with-ML-Flow', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


MLFLOW_TRACKINGH_URI=https://https://dagshub.com/manjitbaishya01/Getting-Started-with-ML-Flow.mlflow \
MLFLOW_TRACKING_USERNAME=manjitbaishya01 \
