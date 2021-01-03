## Problem Statement

A leading pet adoption agency is planning to create a virtual tour experience for their customers showcasing all
animals that are available in their shelter. To enable this tour experience, you are required to build a Machine
Learning model that determines type and breed of the animal based on its physical attributes and other factors.

## Data

The data consists the following columns

| Sl No.  | Column Name   | Description |
| ------- | ------------- | ----------- |
|1 |pet_id | Unique Pet Id
|2 |issue_date |Date on which the pet was issued to the shelter
|3 |listing_date |Date when the pet arrived at the shelter
|4 |condition |Condition of the pet
|5 |color_type |Color of the pet
|6 |length(m) |Length of the pet (in meter)
|7 |height(cm) |Height of the pet (in centimeter)
|8 |X1,X2 |Anonymous columns
|9 |breed_category |Breed category of the pet (target variable)
|10 |pet_category |Category of the pet (target variable)

#### Data Description:
The data folder consists of 2 CSV files<br />
train.csv - 18834 x 11<br />
test.csv - 8072 x 9

#### sample_submission:

pet_id,breed_category,pet_category<br />
ANSL_69903,0,1<br />
ANSL_66892,0,2<br />
ANSL_69750,2,4<br />
ANSL_71623,0,2<br />
ANSL_57969,0,1<br />
## Evaluation Metric:
s1=f1_score(actual_values[′pet_category′],predicted_values[′pet_category′],average=′weighted′)<br />
s2=f1_score(actual_values[′breed_category′],predicted_values[′breed_category′],average=′weighted′)<br />
score=100×(s1+s2)/2

Note: To avoid any discrepancies in the scoring, ensure all the index column values in submitted file matches the index column values in 'test.csv' provided.

***
#### My Rank=> *141* out of 840 active participants and 5060 total participants
#### MY Score=> 90.32509(offline)
Link to [LeaderBoard](https://www.hackerearth.com/challenges/competitive/hackerearth-machine-learning-challenge-pet-adoption/leaderboard/pet-adoption-9-5838c75b/page/3/)
