### `Boston House Pricing`

`Project aim`: The aim of the project includes the following:
1. Training a house price prediction `Regression model`
2. Creating a simple `flask app` to make `predictions` based on user inputs
3. `Dockerizing` it 
4. Creating a `github actions`
5. `Deploying` it on `Heroku` cloud 

`Project requirements`: python, pandas, numpy, flask, scikit-learn and docker

`Tools used`: VS Code and Linux CLI

### `Software and Tools Download Links`:

1. [Github Account](https://github.com)
2. [Hereku Account](https://heroku.com)
3. [VSCode IDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/download/linux)


### `Steps involved in the project`:
1. Create a new environment for the project

```conda create -p venv python==3.7 -y```

2. Activate the environment
```conda activate venv/```

3. Create a requirements.txt file
```run pip install -r requirements.txt```

4. Create flask based application
* Creating a home template ```home.html```
* Added a form based input and prediction api

5. Create a github repository and push all files

6. Deploying it to heroku cloud
* Deploy using github repo option

7. Docker based Deployment
* Create a `Procfile`
* Create a `Dockerfile`

8. Creating github actions CI/CD pipeline
* Create a .github/workflows directory
* Add a github action main.yaml file

9. Push files to github and deploy the container on Heroku cloud

`Application link`: [House Price Prediction Application](https://bostonhousepricing101.herokuapp.com/)