# Fraud Detection in Online Transactions Story.

With the fast development of 4.0 technology, more and more transactions are preferred to be completed online. However, the rise in digital crime is also more popular,
especially fraudulent online transactions, which is defined as a case when a person’s card is used without the owner’s authority, lowering the banks’ credibility. In general, credit card fraud is classified into two types, card-present fraud and card-not-present fraud. The former situation occurs when a person’s card’s information such as card number, expiration date, and CVC are taken physically. The second case occurs when the card’s details are known and exploited without the physical presence of the card in the transaction. This usually happens with online transactions. Although the introduction of chip-payment cards decreased point-of-sale fraud by 28%, card-not-present fraud increased significantly by 106% from 2015 to 2018 (Harrow, 2018). Therefore, it is necessary to figure out a solution to minimize and prevent the fraudulent practice, saving customers and financial companies time and millions of dollars each year. Data Science and Machine Learning techniques can take part in
the data mining process to figure out the solution to such detection problems.

The dataset was collected from [IEEE-CIS Fraud Detection Contest](https://www.kaggle.com/competitions/ieee-fraud-detection/code?competitionId=14242), which was hosted on the Kaggle competition. There are 394 factors related to online tracked transactions and 41 factors associated with the identity of the transactions. Since the dataset was significant, we decided to use Python notebooks to pre-process the dataset, involving partitioning the data by its relationship with the response variable and figuring out a way of filtering N/A variables by its definition and collection process.

#### -- Project Status: [Active]

## Project Intro/Objective
Recently, the rise in digital crime is also more popular, especially fraudulent online transactions have been a threat of lowering the credibility of the banks and costs the economy millions of dollars per year. This study aims to examine the significant features as well as attempting to build a predictive model for fraud detection.


### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python

## Key Observations:
* Some unpopular email domains used by the purchasers might be suspicious of a fraudulent transaction. Top 5 are: (protonmail.com, mail.com, outlook.es, aim.com, and outlook.com)
* Those with three decimal places in transactions are three times more likely to commit fraud than those with only none and one decimal place in transactions. It is infrequent to have standard transactions and online payments to have over two decimal places in their value.
* Categorise the time periods in terms of highest fraudelent transactions frequency:
    ** High time: 6AM to 9AM
    ** Medium time: 3AM to 5AM, 10 to 11AM
    ** Low time: 0-2AM, 12PM to 4PM

* The probability of observing a fraudelent transactions using credit card is higher compared to debit card usage, with Discover card has the highest frequency of fraudelent transactions.
* Most transactions comes from three most popular devices information: Windows, iOS Devices, and MacOS.


