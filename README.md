 Customer Churn Prediction Model
    Model to predicts which telecom customers are likely to cancel their subscriptions. 
🌟 Highlights
    - 78.4% prediction accuracy using Random Forest
    - Identifies top risk factors: monthly charges, contract type, and tenure
    - Handles class imbalance with data balancing techniques
    - Generates actionable insights for customer retention
ℹ️ Overview
    Hi everyone! Thanks for taking the time to read my project. This project analyzes telecom customer data to predict churn, which is the rate at which consumers cancel their subscriptions. This was built as a learning project with the goal to understand machine learning as an extension of data projects I’ve already learned about using R in the past. 
    The dataset contains 7,032 customers from IBM, and the final model achieved 78.4% accuracy in predicting who would leave. Through this project, I learned about handling imbalanced data, training Random Forest models, and identifying which customer features (like monthly charges and contract type) actually matter for predicting churn.
✍️ Authors
   Anvay Sur (Me) 
🚀 Usage
  >Open the script in RStudio and run: rsource("Churn_project.R")
    > The model automatically:
    1.Downloads and cleans the dataset
    2.Trains a Random Forest classifier
    3.Returns Peredictions and performance metrics

  > Example output:
  >> Model Accuracy: 78.4%
  >> Churn Rate: 26.6%

⬇️ Installation
Software: 
  - R (Version 4.5.1)
  - RStudio 

Data set: 
  IBM Telco Customer Churn 

 Project Structure
├── Churn_project.R                 → Main analysis script
├── README.md                      → Documentation
├── feature_importance.png     → Variable importance plot
├── model_results.txt                → Performance metrics
└── .gitignore                            → Git ignore rules   


💭 Feedback and Contributing
      This is a learning project, but I'm open to suggestions on how I can improve or advance!



