#### Applause Prediction for Political Speeches

##### How to train the model
1. Create a conda virtual environment (optional but recommended) using command `conda create -n applause_prediction python=3.6`
2. Activate the created environment (optional, must if step 1 is executed)`conda activate applause_prediction`
3. Install all the dependencies `pip install -r requirements.txt`
4. Train the model `python train_applause_predictor.py`
5. You can predict using `python predict.py` or run it using the web interface by using the flask app described below

##### How to predict through the website
1. Make sure the model is saved in the model directory
2. Run app.py using python3 
