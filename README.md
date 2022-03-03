# Housing Loan Prediction
for more information on coding, data cleansing and visualisation,  please look at the https://github.com/AIPracticeUser/Loan-Prediction/raw/main/Housing_Loan_Prediction.pdf

### Problem Statement
Loan eligibility can only be decided after long and intensive process of verification of documents and validation which takes a huge amount of time.
As loans are the core business of banks and their main profit comes directly from the loan's interest, it is in their best interest to shorten the verification process as fast but as accurately as possible.

### Pain Point
![painpoint](https://user-images.githubusercontent.com/100339175/156523063-376c925c-668b-4db6-afe6-44a3fea21a2e.jpg)

### Tools we will use
Chosen to use Python as our programming language, Dataspell as our IDE and Tableau to visualise the findings
![tools](https://user-images.githubusercontent.com/100339175/156524555-aa52236f-c6e1-4c35-aa89-b14274230837.jpg)

### Process Flow
![flow](https://user-images.githubusercontent.com/100339175/156524821-1ce47437-7144-4314-86ad-e9fd2128a52c.jpg)

### Data set
These are the data set and its attributes

![dataset](https://user-images.githubusercontent.com/100339175/156525127-f32cf862-4084-49ce-8b25-a8a043362b5c.jpg)

### EDA
First need to do Exploratory Data Analysis (EDA) to gain insights on the data through Univariate Analysis and Bivariate Analysis
![EDA](https://user-images.githubusercontent.com/100339175/156525623-f43f25dd-7533-4148-93a0-f6f79c3a6808.jpg)
![datatype](https://user-images.githubusercontent.com/100339175/156525872-60e3af65-9074-4cbd-a8be-075b1169a040.jpg)
![nominal](https://user-images.githubusercontent.com/100339175/156526044-3a0aa17b-5a4d-416b-b355-50916d725d48.jpg)
![categorical](https://user-images.githubusercontent.com/100339175/156526148-3a5229a3-4950-4a1c-93c7-dc5c1c28c5ba.jpg)

### Initial Hypothesis
Formed the initial hypothesis based on the findings and data cleansing and proven them to be correct through visualisation
![hypothesis](https://user-images.githubusercontent.com/100339175/156526390-32c8458d-db74-4ac3-9da7-ae2e3aac8d02.jpg)

### Revised Hypothesis
Revised hypothesis based on the domain knowledge, came up with new features that might affect target variable

Total Income = Combined Applicant Income with Co-Applicant Income

Equated Monthly Instalment = Loan_Amount/Loan_Amount_Term

Balanced Income = Total Income - (Equated Monthly Instalment * 1000)

![revisedhypothesis](https://user-images.githubusercontent.com/100339175/156573514-afc731f3-598a-42be-ac66-e04640cbcb8d.jpg)

### Predictive Analytics
Used 3 program tools (to test the functionality of each tool.) and used them to build the models with different classifier algorithm
1. SkLearn - Python + Dataspell(IDE)
2. AutoGluon
3. AutoAI

### Sklearn (Python)
Using Cross-Validation method on all our 4 models for validation
1. Logistics Regression classification
2. Decision Tree classification
3. Random Tree classification
4. XGBoost classification

![Logistic Regression](https://user-images.githubusercontent.com/100339175/156576217-cf6b2517-b060-4e0f-9c37-6b6bbac60853.jpg)

Chosen Logistics Regression to be the representative for Sklearn Python
![validation](https://user-images.githubusercontent.com/100339175/156576660-96b0c6ee-9f86-4fbb-84f0-f8d0cfe0ae6a.jpg)

### Amazon's AutoGluon (Google Colab)
Chosen RandomForest to be representative for AutoGluon
![AutoGluon](https://user-images.githubusercontent.com/100339175/156577060-bf42d288-390e-41d4-8224-89ea63e8c073.jpg)

### IBM's AutoAI (IBM Watson)
Chosen Snap Logistic Regression to be representative for AutoAI
![AutoAI](https://user-images.githubusercontent.com/100339175/156578707-182a6e0c-680c-4937-ab0f-ff870de39719.jpg)

### The Final Model
For the final model, chosen random forestgini from autogluon based on the reasons stated in the slide
![Final Model](https://user-images.githubusercontent.com/100339175/156579028-b98b2af4-2aad-45f1-b01c-170d5a2924e9.jpg)

