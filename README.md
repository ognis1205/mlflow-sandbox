# mlflow-sandbox

## setup

```bash
 $ pyenv virtualenv 3.6.5 mlflow-sandbox
 $ pyenv local mlflow-sandbox
 $ pip install mlflow scikit-learn lightgbm matplotlib jupyter tensorflow
```

```bash
 $ mlflow server --backend-store-uri sqlite:///tracking.db --default-artifact-root file:/tmp/artifacts --host 0.0.0.0
 $ mlflow server --backend-store-uri sqlite:///data/mlflow.db --default-artifact-root file:data/mlflow-artifacts/ --host 0.0.0.0
```
