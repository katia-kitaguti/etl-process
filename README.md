# 🧭 ETL Process
This project was developed to improve skills in ETL process using DOCKER and Python. 
This project is divided into:
1. Exploratory analysis of a [base downloaded from Kaggle](https://www.kaggle.com/datasets/arnavsmayan/amazon-prime-userbase-dataset)
2. Dividing this table extracted from Kaggle in 4 tables
- User`s Information;
- Subscription Information;
- Engagement metrics;
- Customer Support interaction (Since the data extracted from Kaggle only have the number of interactions of users and considering that normally companies have a table which contains the registration of each customer support interaction, which day users have interacted with it, for instance. So based on it, I created this table using [GabsAki tutorial](https://github.com/GabsAki/gb_mysql_db) as a  reference)
3. Uploading these 4 tables in Docker Postgres instance. 
