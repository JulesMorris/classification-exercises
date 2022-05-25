 Project Planning: 
   
   Acquire data from the Codeup Database and store the process as a function for replication. Save the function in an acquire.py file to import into the Final Report Notebook.

   View data to gain understanding of the dataset and to create the read.   
   
   Create README.md with data dictionary, project and business goals, come up with initial hypotheses.   
   
   Clean and prepare data for the first iteration through the data pipeline. Store this as a function to automate the process, store the function in a prepare.py module, and prepare data in Final Report Notebook by importing and using the funtion.
   
   Clearly define two hypotheses, set an alpha, run the statistical tests needed, reject or fail to reject the Null Hypothesis, and document findings and takeaways.
   
   Establish a baseline accuracy and document well.
   
   Train four different classification models.
   
   Evaluate models on train and validate datasets.
   
   Choose the model with that performs the best and evaluate that single model on the test dataset.
   
   Create csv file with the target variable, the probability of churn, and the model's prediction for each observation in the test dataset.
   
   Document executive summary, conclusions, takeaways, and next steps in the Final Report Notebook.

Project Goals:

    To explore (potentially) strange new areas of churn and see if there are identifiers that would prove useful in addressing churn.

    To seek out new insights and new solutions to address churn.

    To boldly go into hypothesis testing after examining findings from my exploratory analysis.

    To use the findings from the models to produce a clean, readable report.

    To present findings to a mixed audience of technical and non-technical stakeholders.

    To push: readme.md, prepare3.py, and acquire2.py and the final report.


Project Description:

    This project is an analysis of the Telco Dataset, acquired from the Codeup Database.
    The project seeks to address areas of churn to present to a mix of technical and nontechnical stakeholders.
    After reviewing the data, this project will use classification modeling to make predictions and make recommendations.

Initial Hypotheses:

    Customers that churn are likely more price sensitive than retained customers.

    Customers that churn are may be unhappy with particular services offered or lack of services.


Business Goals:

    Find drivers for customer churn at Telco. Why are customers churning?

    Construct a ML classification model that accurately predicts customer churn.

    Deliver a report that a non-data scientist can read through and understand what steps were taken, why and what was the outcome?


Data Dictionary: 
    
    Identifier

        customerID - ID number number unique to the customer

    Target Variable

        Churn - Churn status, whether the customer churned or not

    Demographic Makeup of Dataset

        gender - Whether the customer is a male or a female
        SeniorCitizen - Whether the customer is a senior citizen or not
        Partner - Whether the customer has a partner or not
        Dependents - Whether the customer has dependents or not

    Customer Account Information

        tenure - Number of months the customer has used the service
        Contract - The contract term of the customer
        PaperlessBilling - Whether the customer has paperless billing or not
        PaymentMethod - The customer’s payment method
        MonthlyCharges - The amount charged to the customer monthly
        TotalCharges - The total amount charged to the customer

    Services that each customer has signed up for

        PhoneService - Whether the customer has a phone service or not
        MultipleLines - Whether the customer has multiple lines or not
        InternetService - Customer’s internet service provider
        OnlineSecurity - Whether the customer has online security or not
        OnlineBackup - Whether the customer has online backup or not
        DeviceProtection - Whether the customer has device protection or not
        TechSupport - Whether the customer has tech support or not
        StreamingTV - Whether the customer has streaming TV or not
        StreamingMovies - Whether the customer has streaming movies or not
