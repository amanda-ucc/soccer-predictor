
## Soccer Predictor App

Trains a model to predict the result of soccer matches based on previous data <br>

It uses a 1) random tree classifier and 2) xgboost as well.  <br>

1 Random tree <br>

The out of bag scores are as follows: <br>

<img width="629" height="454" alt="image" src="https://github.com/user-attachments/assets/c47e3e64-f7af-40a2-9cf7-40e554f6ad9f" />

The confusion matrix for the tree based approach is as follows <br>

<img width="883" height="645" alt="image" src="https://github.com/user-attachments/assets/319092cb-d413-4694-b836-78fc6c44f467" />

The best tree looks like this <br>

<img width="1578" height="790" alt="image" src="https://github.com/user-attachments/assets/9cccb105-0d25-44ab-b68c-a93f84b65a71" />

The more important features were <br>

<img width="994" height="545" alt="image" src="https://github.com/user-attachments/assets/246da0f1-4846-4bc0-b868-ab5c01c0d579" />


2) Add xgboost <br>

The confusion matrix is as follows: <br>

<img width="844" height="650" alt="image" src="https://github.com/user-attachments/assets/47288b4c-7cfd-4d90-a071-e96b81020ebb" />

The important features: <br>

<img width="994" height="547" alt="image" src="https://github.com/user-attachments/assets/77d3d02e-14a3-4c80-9535-20217b3c75e3" />


## To run this:

You have to install uv <br>

Make sure your python between [ 3.12 - 4 ) <br>

uv sync --extra dev <br>

## TODO
This will be made into an app which picks up the data online  and makes future predictions on matches

