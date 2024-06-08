![Gaming](https://i.pinimg.com/originals/e8/13/62/e81362ba17f072c0bd1d76612c4bec3b.gif)
# A/B testing in mobile game Data Analysis

# About
A Company that develops mobile games has performed A/B testing on users by selling sets of promotional offers. Analyze the sales patterns of two groups, and understand customer behavior. The primary objective is to enhance and optimize sales strategies. The dataset utilized in this project is sourced from the. Suggest metrics to evaluate the results of the last past themed event in the game.

# Data 
This project's data was obtained from [here](https://karpov.courses)
- There are three types of data , the first one is result of A/B test, in which two groups of users were offered different sets of promotional offers. It is known that ARPU in the test group is 5% higher than in the control group. At the same time in the control group 1928 players out of 202103 turned out to be paying players, and in the test group - 1805 out of 202667.format:

| user_id | revenue | testgroup |
|---------|---------|-----------|
|    1    |    0    |     b     |
|    2    |    0    |     a     |
|    3    |    0    |     a     |
|    4    |    0    |     b     |
|    5    |    0    |     b     |

- The second one 'check-in time'
  
| reg_ts    | uid |
|-----------|-----|
| 906166566 |  2  |
| 906344325 |  2  |
| 906686169 |  2  |
| 906893386 |  2  |
| 906980227 |  2  |

- Third one data on the time users log into the game

| auth_ts   | uid |
|-----------|-----|
| 906166566 |  2  |
| 924422172 |  3  |
| 937374732 |  4  |
| 947425117 |  5  |
| 955630339 |  6  |


# Bussiness questions to answer 
- Which set of offers can be considered the best? What metrics should be analyzed to make the right decision and how?
- Statistical analysis
- Retention rate
- The  game features themed events every month, limited in time. In them, players can get unique items for the garden and characters, additional coins or bonuses. The rewards require completing a series of levels in a certain amount of time. What metrics can be used to evaluate the results of the last event that took place?
- Suppose, in another event, we have complicated the event mechanics so that for every unsuccessful attempt to complete a level, the player will roll back a few levels. Would the set of outcome evaluation metrics change? If so, how?
