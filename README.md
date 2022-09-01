# cheap_mlops
On going project to develop a docker composer and individual images that would build out 
jupyterlab, airflow, feast, and mlflow for end to end data science platform

TODO - docker composer for feast, airflow, mlflow, jupyterlab. 
establish all the images for everything 

1) pull down all images
2) run images with composer
3) introduce a sample notebook that would run/register model within mlflow
4) airflow dag that would pull out mlflow model registry prod version 
5) preprocess data within dag save feature into feast
6) batch run predict and save within feast as prediction_feature (usecase, model:sub-model relationship

Honestly you can start putting random stuff inside like a recommendation engine 
