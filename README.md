## MLflow application - Modeling wine preferences by data mining from physicochemical properties

### Software & Tools Reqs

1. [Github Account](https://github.com)
2. [MLflow](https://mlflow.org/docs/latest/index.html)
3. The data set used in this example is from: (http://archive.ics.uci.edu/ml/datasets/Wine+Quality)

Create a new environment 
```
conda create -p venv python==3.7 -y
```
Git Commit
```
git add --all
git status
git remote add origin https://github.com/rtdjin3000/mlflow_wine_prefer.git
git commit -m "This is my first commit for this project"
git push origin main --force

```

MLFLOW_TRACKING_URI=https://dagshub.com/rtdjin3000/mlflow_wine_prefer.mlflow \
MLFLOW_TRACKING_USERNAME=rtdjin3000 \
MLFLOW_TRACKING_PASSWORD=c5baa3e86b7d810035c6b85ee726ab0092a215f9 \
python script.py
