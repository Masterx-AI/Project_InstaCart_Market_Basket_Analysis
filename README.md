# AI/ML Project - InstaCart Market Basket Analysis

<p align="center"><img src="https://user-images.githubusercontent.com/54996245/146815706-df1786e6-6771-4bb0-9f10-e4ace2afbe53.jpg" style="width: 1000px;"/></p>

### Description:

Whether you shop from meticulously planned grocery lists or let whimsy guide your grazing, our unique food rituals define who we are. Instacart, a grocery ordering and delivery app, aims to make it easy to fill your refrigerator and pantry with your personal favorites and staples when you need them. After selecting products through the Instacart app, personal shoppers review your order and do the in-store shopping and delivery for you.

Instacart’s data science team plays a big part in providing this delightful shopping experience. Currently they use transactional data to develop models that predict which products a user will buy again, try for the first time, or add to their cart next during a session. Recently, Instacart open sourced this data - see their blog post on 3 Million Instacart Orders, Open Sourced.

In this competition, Instacart is challenging the Kaggle community to use this anonymized data on customer orders over time to predict which previously purchased products will be in a user’s next order. They’re not only looking for the best model, Instacart’s also looking for machine learning engineers to grow their team.


### Acknowledgements:
This dataset is taken from Kaggle, \
https://www.kaggle.com/c/instacart-market-basket-analysis/data

### Objective:
- Understand the Dataset & cleanup (if required).
- Build classification model to recommend groceries based on users past purchases.

### Stractegic Plan of Action:
**We aim to solve the problem statement by creating a plan of action, Here are some of the necessary steps:**
1. Data Exploration
2. Exploratory Data Analysis (EDA)
3. Data Pre-processing
4. Data Manipulation
5. Predictive Modelling
6. Project Outcomes & Conclusion

### Some Visuals of the Project:

**1. Online Shopping Department-Frequency**
  
<p align="left"><img src="https://user-images.githubusercontent.com/54996245/146815880-ad65cc9d-4451-42b8-aefb-c366b0c683ab.png" /></p>
  
**2. Online Shopping Aisle-Frequency**
  
![image](https://user-images.githubusercontent.com/54996245/146815996-457a744a-5b3b-4b2b-8209-afc3155da56f.png)

**3. Online Shopping Product-Frequency**

![image](https://user-images.githubusercontent.com/54996245/146816065-d0a93d69-cc55-437f-bc7c-007ec75817e6.png)

**4. Houly Online Shopping Frequency**

![image](https://user-images.githubusercontent.com/54996245/146816402-7d2691f2-8934-4a48-8a25-2e878d1e8248.png)

### Here are some of the key outcomes of the project:
- The Dataset was quiet large with combined data totally around 1.3M. 
- There were also few outliers & no duplicates present in the datset, which had to be dropped.
- Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the featureset.
- Further filtering was done with threshold for the number of user id's & product id's.
- Finally Nearest Neighbours Algorithm was employed to get the similar Groceries Recommendations based on the Cosine Similarity.

