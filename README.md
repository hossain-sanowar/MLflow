# MLflow
MLflow is an open source platform to manage the ML lifecycle, including experimentation, reproducibility, deployment, and a central model registry.

![MLflow end-to-end](https://mlflow.org/docs/latest/tutorials-and-examples/tutorial.html)

Working Steps:
```
touch app.py
pip install -r requirements.txt
python app.py
mlflow ui
```
# Make sure the current working directory is 'examples'
```
python app.py <alpha> <l1_ratio>
python app.py 0.3 0.6 
```