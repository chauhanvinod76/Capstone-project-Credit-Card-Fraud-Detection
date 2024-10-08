# Capstone-Machine Learning Project 

## Credit-Card-Fraud-Detection
![Screenshot of dashboard](https://i.imgur.com/NzvDPCi.png)


[Link to dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data?select=creditcard.csv)

### Description of dataset
The dataset includes credit card transactions by European cardholders in September 2013, focusing on transactions over two days.

#### General Observations
 * Out of 284,807 transactions, 492 are fraudulent, making up just 0.172% of the data, which highlights a significant class imbalance. 
 * All features, except 'Time' and 'Amount,' are numerical values obtained through PCA transformation, with the original features withheld due to confidentiality. 
 * 'Time' indicates the time elapsed since the first transaction, and 'Amount' represents the transaction amount, useful for cost-sensitive learning. 
 * The target variable 'Class' indicates whether a transaction is fraudulent (1) or not (0)."

### Conclusion
* The final model successfully detected fraudulent transactions with high accuracy. 
* Importance of addressing data imbalance and rigorous model evaluation. 
* Integrating real-time data streaming, testing additional models, and exploring deep learning techniques. 
* XGBoost is the model selected for this dataset based on recall rather than preciseion.

#### Connect with Me!
Send me a DM on [Linkedin!](https://www.linkedin.com/in/chauhanvinod/)

