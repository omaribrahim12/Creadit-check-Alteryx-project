# Credit check Alteryx project 
### Overview

This repository contains a README file documenting the process of analyzing a customer dataset using Alteryx. The dataset includes various attributes related to customers' creditability and financial information.
Dataset

The dataset includes the following attributes:

1. Creditability
2. Account Balance
3. Duration of Credit (month)
4. Payment Status of Previous Credit
5. Purpose
6. Credit Amount
7. Value Savings/Stocks
8. Length of current employment
9. Instalment per cent
10. Sex & Marital Status
11. Guarantors
12. Duration in Current address
13. Most valuable available asset
14. Age (years)
15. Concurrent Credits
16. Type of apartment
17. No of Credits at this Bank
18. Occupation
19. No of dependents
20. Telephone
21. Foreign Worker

### Analysis Process
Data Loading: The dataset was loaded into an Alteryx workflow.

Data Summary: A summary of the dataset was generated to understand its basic characteristics and distributions.

Data Preparation:
  Select Tool: The Select tool was configured to choose relevant columns for analysis.
        
  Formula Tool: The Formula tool was utilized to perform calculations or transformations on the selected data.
  
  Setting Categorical Values: Categorical values were properly encoded to facilitate model training.
  
        
Model Training:
        Several machine learning models were trained using the prepared dataset, including:
            Logistic Regression Model
            Decision Tree
        
Model Validation:
        The trained models were validated to assess their performance and predictive accuracy.

### Usage

To replicate the analysis process:

  Install Alteryx Designer on your system.
  Clone or download this repository to your local machine.
  Open the Alteryx workflow file (.yxmd) in Alteryx Designer.
  Follow the annotations and comments within the workflow to understand each step.
  Run the workflow to perform the data analysis.

### Contributors

  Omar Elzr

### License

This project is licensed under the MIT License.
