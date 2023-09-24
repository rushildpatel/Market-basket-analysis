# Market Basket Analysis using association rule learning

## Project Objective:
1] The main objective is to thoroughly explore the association rule learning techniques that are commonly implemented.
2] To determine the similarities and differences along with advantages and disadvantages of different ARL algorithms.
3] To implement deep learning techniques (similar to those used for movie recommendations) for performing the same task and evaluate the feasibility of the method.

## Motivation to select this topic:
- There are many real-life situations where items or objects are associated with each other in a way that is not directly recognizable to the human brain.
- Examples include Store Optimization and Movie Recommendation.
- Strategic placement of objects in a store can improve the sales significantly.
- This topic was selected to explore the process of determining these strategies as used by many big firms and stores.

## Dataset Description:
- Link : [Kaggle Dataset Link](https://www.kaggle.com/datasets/mohammedsaifjakbani/suggestions)
- The dataset contains 7501 transactions with maximum length of 20 items from a grocery store.
- There are 120 unique items in the dataset with ‘Mineral Water’ having max frequency of 1788 and ‘Asparagus’ having minimum frequency of 1.

## Methodology:
1] Perform data pre-processing and visualization.
2] Implement Apriori, FP-growth and Eclat algorithms.
3] Generate insights and strategies from rules mined.
4] Compare the results.
5] Implement Auto-encoder for same task.
6] Compare results with conventional methods.
7] Evaluate feasibility of this method.

## Metrics Involved:
- Support - the percentage of transactions that contain all of the items in an itemset.
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/cb33f52c-633b-4381-b589-ea34c3257b8e)


- Confidence - the probability that a transaction that contains the items on the left hand side of the rule also contains the item on the right hand side (return rate).
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/243df631-d61b-4c58-be79-7a38e0c66ba6)


- Lift - strength of association between the products on the left and right hand side of the rule. (ratio)
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/1c79acb2-d17b-48b1-87d1-7cf1edf27299)


- Leverage - measure of difference of X and Y appearing together in the data set and what would be expected if X and Y where statistically dependent. (difference)
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/55766704-0b8c-404b-8902-c98be6eb81e3)


- Conviction - Intuitively similar to lift however it is directional.
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/1874d644-cc5d-4240-b3ce-546608be7496)

## Visualizing the rules:
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/f03bea07-e856-42f4-ad55-044ede9c8ea0)

![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/923396cb-5f7c-4c89-8d91-fccf996c3bdb)

## Running time:
- Apriori = 2.03 + 0.03 = 2.06 sec
- FP-Growth = 0.74 sec
- Eclat = 65 sec (Run time for Eclat is high because there is no constraint on lift and all rules are generated which requires many recursive iterations)

## Key differences:

![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/0153a776-3cb9-4c1a-914d-c2244eb38992)









