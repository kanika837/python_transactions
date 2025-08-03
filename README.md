# python_transactions


This project involves an analysis of a daily financial transactions dataset to uncover trends, patterns, and valuable insights. The analysis process includes data cleaning, exploratory data analysis (EDA), and time series and correlation analysis. The final output is a comprehensive report with visualizations to inform decision-making and strategic planning.



# Key Findings and Analysis

 * Data Overview: The dataset contains information on 2,461 transactions with 8 columns, including Date, Mode, Category, Subcategory, Note, Amount, Income/Expense, and Currency. All transactions are recorded in Indian Rupees (INR).
   
 * Data Cleaning: The initial data inspection showed missing values in the Subcategory and Note columns. A project example outlines steps to handle missing values, correct data types, and remove duplicates to prepare the data for analysis.


   
   # Transaction Distribution:
   
   * Payment Modes: The most common payment modes were "Saving Bank account 1," "Cash," and "Credit Card," with "Saving Bank account 1" being the most frequent.
     
   * Categories: The top five transaction categories were "Food," "Transportation," "Household," "subscription," and "Other".
     
   * Income/Expense: The majority of the transactions were classified as "Expense," followed by "Transfer-Out" and "Income".



![WhatsApp Image 2025-07-31 at 22 34 43_75cf723a](https://github.com/user-attachments/assets/9164337e-2f39-473a-bcd7-7bf7495c2815)




     


     
 #  Transactional Amounts:
   
   * The distribution of transaction amounts is right-skewed, indicating that most transactions are of smaller values.
     
   * A boxplot analysis of the top categories shows that while "Food" is the most frequent category, categories like "Household" and "Transportation" have a wider range of transaction amounts, with some significant outliers. Similarly, the boxplot for subcategories reveals a wide spread of amounts, with Kirana and Mutual fund showing particularly high-value outliers.
     
 * Time Series Analysis: The project example suggests performing time series analysis to identify monthly and daily transaction trends, which can reveal seasonal patterns and peaks in certain months.
   
 * Correlation Analysis: A correlation heatmap can be used to analyze the relationships between different transaction categories, which helps in understanding how spending in one area might relate to another.



   ![WhatsApp Image 2025-07-31 at 22 31 27_33b0cfa8](https://github.com/user-attachments/assets/6ae73fb7-929e-48ca-828d-2c5806988bd3)

