# Ace_Dynamics-
FrostHack Hackathon
![Screenshot 2022-05-21 182710](https://user-images.githubusercontent.com/90788942/169652568-1a829a20-9685-4b93-a529-a8a6eab35ea4.jpg)


## Deploying ML Model using Flask


### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

Flask version: 0.12.2
conda install flask=0.12.2  (or) pip install Flask==0.12.2

### Project Structure
This project has four major parts :
1. model.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.
2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3. template - This folder contains the HTML template (index.html) to allow user to enter employee detail and displays the predicted employee salary.
4. static - This folder contains the css folder with style.css file which has the styling required for out index.html file.

### Running the project
I have already save ML Model in model.pkl


1. Run app.py using below command to start Flask API
```
python app.py
```
By default, flask will run on port 5000.

2. Navigate to URL http://127.0.0.1:5000/ (or) http://localhost:5000

You should be able to view the homepage.

Enter valid numerical values in all 30 input boxes and hit Predict.

If everything goes well, you should  be able to see the predcited salary vaule on the HTML page!
check the output here: http://127.0.0.1:5000/predict
