# Zomato Restaurant Rating Project

##### Overview
**This project is designed to help Zomato restaurants predict their ratings using advanced data analytics and machine learning. The workflow covers everything from data exploration to building a predictive model and deploying it as a live web application. The main goals are:**

- Perform extensive Exploratory Data Analysis (EDA) on the Zomato dataset.

- Build a machine learning model to predict a restaurant’s rating based on key features.

- Deploy the model via Flask to enable live predictions of restaurant ratings.
---
##### Features
- In-depth EDA on restaurant data
- Machine learning model for rating prediction
- Flask web app for live predictions via GUI or API
- User-friendly interface for restaurant owners/managers
---
##### Steps
###### A) EDA and Model Building
- 1. Load and analyze the dataset using Jupyter Notebook or Google Colab.
- 2. Build and train a machine learning model. Save the trained model using pickle.

###### B) Deployment
- 1. Use PyCharm (or any IDE) to set up your development environment. (You may also use other editors, e.g., Sublime Text.)
- 2. Set up Python interpreter and required packages.
- 3. Run Model.py to verify the model.
- 4. Run App.py to launch the Flask application.
- 5. Input restaurant features via the provided web interface to get the predicted rating.

##### File Structure
- **Model.py —** Model building and saving logic
- **app.py —** Flask web application and API
- **.csv —** Cleaned dataset used for training and predictions
- **/template —** HTML files for the front-end
- **/static —** CSS and static assets

##### Step	Description
<img width="897" height="204" alt="image" src="https://github.com/user-attachments/assets/1269deda-449d-45fa-9ff0-7245e566204c" />

---
##### Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn (Machine Learning)
- Flask (Web App)
- HTML, CSS (Frontend)

##### Installation & Usage
- Clone the Repository:
- git clone https://github.com/prajwalghotkar/Zomato-Restaurant-Rating-Project

##### Install Dependencies:
- Install required packages via pip:

pip install -r requirements.txt

##### Run the Application:

- Run Model.py to ensure the model is available.
- Start the Flask web app:
python app.py

##### Interact with the Web App:

- Access the local host in your browser.
- Input features and get the restaurant rating predictions.

##### Demo:
- If the PyCharm is already install open the file/Project directly as mentioned below 

![image](https://github.com/user-attachments/assets/88f5044e-daa1-4090-91e6-e400dd7e44c0)
---
- Set Up Python Interpreter

![image](https://github.com/user-attachments/assets/87bcd9e3-bec4-43cc-82b1-21fe7378fd3a)

![Screenshot 2025-02-04 161430](https://github.com/user-attachments/assets/e54fc0b2-949a-4aef-ac81-d97c71dad8cd)
---
- Once all the Packages are loaded

- Right click Model.py the Run

![image](https://github.com/user-attachments/assets/22010d9e-8a27-4ec6-b97c-8e40148b97e5)
---
- This need to complete without any error

![Screenshot 2025-02-04 161619](https://github.com/user-attachments/assets/8883b5f2-ee54-4a5a-9149-5866b5eae2eb)
---
- Same way Right click and Run App.py

![Screenshot 2025-02-04 161659](https://github.com/user-attachments/assets/4b2b2d0a-0d46-4829-a056-70846add46d9)
---
- Enter the Values click the Button <<Predict>> for Prediction

![Screenshot 2025-02-04 162211](https://github.com/user-attachments/assets/fe9465e9-50a3-44ac-b2db-d5266a9ac9f1)
---
- The Rating will be displayed as mentioned below

![Screenshot 2025-02-04 161958](https://github.com/user-attachments/assets/82eba831-cfda-482b-8fdc-0e3eb7c9c98a)
---
##### future befinit of that project:
- **Improved Decision Making:** Restaurant owners can make more informed business decisions—like adjusting menus, pricing, or service—based on predicted ratings and important influencing factors.
- **Operational Efficiency:** Automated, data-driven rating predictions streamline feedback processes, reducing reliance on manual analysis or frequent customer surveys.
- **Enhanced Customer Experience:** By proactively addressing the factors impacting ratings, restaurants can deliver better service and satisfaction to customers.
- **Personalized Marketing:** With insights from feature importance, marketing and promotional campaigns can target the factors most likely to improve customer ratings and loyalty.
- **Scalable to Larger Networks:** As the model evolves, it can be adapted and deployed across other cities or food service platforms beyond Zomato.
- **Competitive Edge:** Early adoption of AI-driven analytics positions restaurants for greater competitiveness in the rapidly evolving food service industry.
- **Continuous Improvement:** Regular updates and retraining with new data ensure the prediction engine becomes more accurate and valuable over time.
---
##### File you will need
- Model.py file
- .csv file
- template
  - .html
  - Static
  - .css file
  - app.py file

##### File Description
###### Model.py:
- The file contains the code for building our model that is used in predicting the restaurant ratings

###### csv.file:
- This contains our that we have already cleaned and saved.

###### templete file:
- The template file contains the html and css documents used in building our web app

###### App.py:
- This contains the Flask API's that receives restaurant details via a GUI/API calls, then make the prediction of restaurant rating based on our model and returns the rate.


🙋‍♂️ 👨‍💻 Developed by Prajwal Ghotkar 
https://www.instagram.com/prajwal.ghotkar_
