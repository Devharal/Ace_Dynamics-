# Ace_Dynamics
## Machine Learning to Predict Credit Card fraud
FrostHack Hackathon
![Screenshot 2022-05-21 182710](https://user-images.githubusercontent.com/90788942/169652568-1a829a20-9685-4b93-a529-a8a6eab35ea4.jpg)


## Description

Credit card fraud, act committed by any person who, with intent to defraud, uses a credit card that has been revoked, cancelled, reported lost, or stolen to obtain anything of value. Using the credit card number without possession of the actual card is also a form of credit card fraud. Through training by model I made ML model to make prediction regarding frauds. You need to give 30 transation details it will Predict. Particularly model is deployed on webstie using FLASK
I also made a Website which will connect to main website. Link -https://gorgeous-zuccutto-7e5a36.netlify.app/

## PLatform
<p >
        <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white" alt="Github Stats" />
  <img src="https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white" alt="Github Stats" />
</p>


## Language Used-

<p >
        <img src="https://github.com/jalbertsr/logo-badge-images/blob/master/img/rsz_flask.png?raw=true" alt="Github Stats" />
 
</p>
<p >
        <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="Github Stats" />
   <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=whit" alt="Github Stats" />
   <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="Github Stats" />
   <img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue" alt="Github Stats" />
   
</p>

## Deploying ML Model using Flask


### Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.

Flask version: 0.12.2
conda install flask=0.12.2  (or) pip install Flask==0.12.2

### Project Structure
This project has four major parts :
1. ace-dynamics-fraud-detection.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.
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
