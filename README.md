# Fraud Detection 
This project goes over how **Traditional Machine Learning** and **Deep Learning** algorithms that can be used in fraud detection in the financial world. Fraud is a deliberate act (or failure to act) with the intention of obtaining an unauthorized benefit, either for oneself or for the institution, by using deception or false suggestions or suppression of truth or other unethical means, which are believed and relied upon by others. Fraud can cause banks to lose money and damage their reputation. 
<br><br>
Different models have been proposed - **Random Forest, XGBoost, Logistic Regression, K-Nearest Neighbour, Naive Bayes and Recurrent Neural Networks with SimpleRNN and LSTM cells**. The models produce different results. The main emphasis of this research was to find a metrics that can correctly indicate if the algorithm is good or bad at detecting fraud. In addition **False Negative** transactions are tried to be kept as low as possible so financial losses can be further reduced and see how different algithms tackle the problem. The **SMOTE** technique has been used to create synthetic fraudulent transactions because the initial dataset was highly unbalanced. Ideally to generate better models, we would require a balanced dataset with fraudulent and genuine transactions.
<br><br>
## Dataset - [PaySim](https://www.kaggle.com/ntnu-testimon/paysim1)
There is a lack of public available datasets on financial services and specially in the emerging mobile money transactions domain. Financial datasets are important to many researchers and in particular to us performing research in the domain of fraud detection. Part of the problem is the intrinsically private nature of financial transactions, that leads to no publicly available datasets.
<br><br>
PaySim simulates mobile money transactions based on a sample of real transactions extracted from one month of financial logs from a mobile money service implemented in an African country. The original logs were provided by a multinational company, who is the provider of the mobile financial service which is currently running in more than 14 countries all around the world.

## How to run
To run the code you will have to download the repository and the dataset from [Kaggle](https://www.kaggle.com/ntnu-testimon/paysim1). Change the paths inside the files. The fastest way to run the code is to open the files in Google Colab. Alternatively you can just open [Data_Visualisation.ipynb](https://github.com/nickninov/ML-Fraud-Detection/blob/main/Data_Visualisation.ipynb) to visualise the data and the data cleaning process. [Algorithms.ipynb](https://github.com/nickninov/ML-Fraud-Detection/blob/main/Algorithms.ipynb) contains all the algorithms and their results.
<br><br>

## Further research
- Create a custom loss function for Traditional Machine Learning and Deep Learning that calculates the amount lost based on False Negative transactions when a model misclassifies a transaction. This might be a challenge because PaySim is a mobile money simulator and real life administrative costs that banks have also play a crucial part in calculating the total loss of a bank.

- Investigate and improve currently proposed Deep Learning models. Training takese a long time and more experimnets need to be ran with different epochs,batch sizes and create a new RNN model. In addition RNN might not be the most suitable model for this dataset because RNN learns sequential data. A fraudulent transaction can also be caught before a request has even been made just by looking at the user's behaviour on the website, how long it takes them to go from one page to another and even how much time they spend filling up card information or staying on a website.

# Thank you very much for your time ㋡. <br>Feedback is always appreciated!
