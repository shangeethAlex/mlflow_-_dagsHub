import dagshub
dagshub.init(repo_owner='shangeethmathan2020', repo_name='mlflow_basic', mlflow=True)

import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1)


https://dagshub.com/shangeethmathan2020/mlflow_basic.mlflow