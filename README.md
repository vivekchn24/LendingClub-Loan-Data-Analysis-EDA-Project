**-->> LendingClub-Loan-Data-Analysis-EDA-Project**

**-->> LendingClub Loan Data - Exploratory Data Analysis (EDA) Project**

This project involves a comprehensive Exploratory Data Analysis (EDA) on the LendingClub loan dataset using Python and Jupyter Notebook. The goal is to uncover insights about loan trends, borrower behavior, and key factors affecting loan defaults.

**-->> 📂 Lending-Club-Loan-Data-Analysis-EDA-Project Folder Contains**

-Data_Dictionary.xlsx File (Explaination And FullForms Of The Columns)

-missing_info_vivek_chauhan.xlsx File (For Analyse The Missing Columns One By One)

-LOAN_LENDING_CLUB_EDA_PROJECT_VIVEK_CHAUHAN (Jupyter Notebook Code Pdf File)

-LOAN_LENDING_CLUB_VIVEK_CHAUHAN (PowerPoint Presentation Slides Pdf File)

-DATA CSV FOLDER CONTAINS ORIGINAL DATASET

**-->> 📁 Dataset**

- ""Source"": LendingClub public dataset (Downloaded from Kaggle / official source)
- ""Rows"": Aprrox 37,000+
- ""Columns"": 100+ (various financial & personal borrower details)

**-->> 📊 Objective**

- Analyze the structure of LendingClub loan data.
- Identify factors that influence loan status (Fully Paid, Charged Off,Current Status (Ignored In Data-Analysis Cause We Can't Predict Applicants Behaviour)).
- Perform univariate, bivariate, and multivariate analysis.
- Derive business Insights/Recomendations that can help in credit risk assessment.

**-->> 🛠️ Tools & Technologies Used**

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Data Cleaning & Preprocessing
- Data Visualization
- Statistical Analysis

**-->> 📌 Key Steps Performed In EDA Analysis**

1. Data Cleaning
   - Handling missing values
   - Dropping irrelevant or redundant columns
   - Formatting and type conversion

2. Univariate Analysis
   - Distributions of loan amount, interest rates, term, grades

3. Bivariate Analysis
   - Loan status vs interest rate, loan purpose, etc.

4. Multivariate Analysis
   - Correlation heatmaps
   - Factors affecting loan defaults

5. Insights & Conclusions
   - Summarized key findings with visual charts
   - Business recommendations

** 📌 Recommendations/Insights**

1. Risk-Based Interest Adjustment     
Loans issued to customers with Grade B,C & D (especially sub-grades like B3, B5, C1, etc.) should be charged higher & medium interest rates or subjected to stricter terms, as these categories show a significantly higher default rate.

2. Stricter Loan Approval for Employment History    
 Customers with employment length of 1, 7, or 10 years means experts show a higher likelihood of default. Employment verification and job stability analysis should be prioritized during approval.

3. Defaulters Due for Specific Purposes     
Applicants seeking loans for "debt consolidation" purposes should be evaluated more carefully, as these purposes are common among defaulters.

4. Home Ownership Analysis    
Borrowers with "Rent", "Mortgage",home ownership types are more likely to default. "Mortgage" holders appear more reliable and can be treated as lower risk.

5. Verification Status Checks    
Even borrowers with "Verified" or "Not Verified" status have high default rates. This indicates that verification alone is not sufficient, and other risk indicators should be considered.

6. Term-wise Risk Adjustment    
Loans with a 36-month term show a higher default rate. Consider applying more Strickly credit checks or insurance for these term loans.

7. Time-Based Lending Strategy for Defaulters     
Most defaults occurred in 2011, particularly in the months of October,November and December.

8. Bankruptcy Is Not the Only Indicator    
Most defaulters have “0 bankruptcies”, indicating that relying solely on bankruptcy history to judge credit risk is insufficient.

9. Debt to Income Ratio     
Most defaulters have “”Medium debt ratio””, indicating that Normal dti ratio get higher defaulters.

10. Most Common Purpose That Find In Defaulters     
Most defaulters Purpose is “”Debt-Consolidation””, indicating that Be Carefull Before Apply a loan for this Purpose.

**📌 Disclaimer:**

-This EDA project is created purely for learning and practice purposes; hence, I’ve shared only the PDF versions of the Jupyter Notebook and PowerPoint to maintain originality and avoid direct copy-paste.

-⭐ This EDA project was completed as part of my data analytics training/Journey And the EDA Project Done At Future Vision Computer Institute,Surat.
<a href="https://futurevisioncomputers.com/">Future Vision Computer Institute</a>
