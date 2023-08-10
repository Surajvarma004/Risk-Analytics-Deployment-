# Problem Statement : Default Prediction using SVM


![webpage](/static/webpage.png?raw=True "Title") 

# create conda enviroment
> conda create --name deployment python=3.7

# activate the conda env and install libraries 
> conda activate deployment

> pip install -r requirements.txt 

# deactivate the enviroment
> conda deactivate 

# Run Server
> python app.py

# request url 
> http://127.0.0.1:5000/api/prediction

# request method: 
> post 


# request data in json 

{
    "Gender": 0.0,
    "Married": 0.0,
    "Dependents": 10.0,
    "Education": 1.0,
    "Self_Employed": 0.0,
    "ApplicantIncome": 1.0,
    "CoapplicantIncome": 0.0,
    "LoanAmount": 104300.0,
    "Loan_Amount_Term": 36.0,
    "Credit_History": 0.0,
    "Property_Area": 2.0
}

# Response:

> eligible or not eligible
