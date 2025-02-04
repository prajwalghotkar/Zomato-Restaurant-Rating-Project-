# Zomato Restaurant Rating Project

## Main Objective:

### The main agenda of this project is:

#### * perform extensive Exploratory Data Analysis(EDA) onn the Zomato Dataset.
#### * Build an appropriate Machine Learning Model that will help various Zomato Restaurants to predict their respective Rating based on certain features.
#### * DEPLOY the machine learning model via Flask that can be used to make live prediction of restaurant ratings.

# STEPS:

### A) EDA and Model Building Part

#### 1) Load the Dataset and perform the necessory EDA in your Jupyter Notebook or google colab
#### 2) Build your Machine learing algorithm and save your model using "pickle"

### B) Deployment Part

#### 1) In this we will be using "pycharm", however, feel free to use any IDE that you are conformable with (e.g. you can use sublim text editor to achive the same) NOTE: There several ways of using Flask to deploy your application including creating a virtual environment.

#### 2) Install your favourite IDE(e.g. pycharm) 

##### * If the PyCharm is already install open the file/Project directly as mentioned below 
![image](https://github.com/user-attachments/assets/88f5044e-daa1-4090-91e6-e400dd7e44c0)

##### * Set Up Python Interpreter
![image](https://github.com/user-attachments/assets/87bcd9e3-bec4-43cc-82b1-21fe7378fd3a)
![Screenshot 2025-02-04 161430](https://github.com/user-attachments/assets/e54fc0b2-949a-4aef-ac81-d97c71dad8cd)

##### * Once all the Packages are loaded
##### * Right click Model.py the Run
![image](https://github.com/user-attachments/assets/22010d9e-8a27-4ec6-b97c-8e40148b97e5)
##### * This need to complete without any error
![Screenshot 2025-02-04 161619](https://github.com/user-attachments/assets/8883b5f2-ee54-4a5a-9149-5866b5eae2eb)
##### * Same way Right click and Run App.py
![Screenshot 2025-02-04 161659](https://github.com/user-attachments/assets/4b2b2d0a-0d46-4829-a056-70846add46d9)
##### * Then Copy the http://127.0.0.1:5000/ open it in a web browser.
![Screenshot 2025-02-04 163339](https://github.com/user-attachments/assets/e4bb6447-df2e-4568-91f3-ab9facaf0e91)
##### * Enter the Values click the Button <<Predict>> for Prediction
![Screenshot 2025-02-04 162211](https://github.com/user-attachments/assets/fe9465e9-50a3-44ac-b2db-d5266a9ac9f1)
##### * The Rating will be displayed as mentioned below
![Screenshot 2025-02-04 161958](https://github.com/user-attachments/assets/82eba831-cfda-482b-8fdc-0e3eb7c9c98a)

### File you will need
##### * Model.py file
##### * .csv file
##### * template
#####    * .html
##### * Static
#####   * .css file
##### app.py file

### File Description

#### Model.py:
##### The file contains the code for building our model that is used in predicting the restaurant ratings

#### csv.file:
##### This contains our that we have already cleaned and saved.

#### templete file:
##### The template file contains the html and css documents used in building our web app

#### App.py:
##### This contains the Flask API's that receives restaurant details via a GUI/API calls, then make the prediction of restaurant rating based on our model and returns the rate.


###### Prajwal Ghotkar




