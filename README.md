# Market Basket Analysis using association rule learning

Tech Stack: Python, Tensorflow/Keras, Numpy, Pandas, mlxtend, matplotlib

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
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/d1e50b0b-ab8f-46aa-b916-f7d40bf9a785)


- Confidence - the probability that a transaction that contains the items on the left hand side of the rule also contains the item on the right hand side (return rate).
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/4ac047a5-be97-4e0c-9dc9-26626d60fb44)


- Lift - strength of association between the products on the left and right hand side of the rule. (ratio)
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/3ec565dc-7e0a-4fcb-83ff-cbb76a1afda4)


- Leverage - measure of difference of X and Y appearing together in the data set and what would be expected if X and Y where statistically dependent. (difference)
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/15a68d83-2556-445b-800b-ca515951d617)


- Conviction - Intuitively similar to lift however it is directional.
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/51de5e86-38f3-46b8-a1f8-c5133ba9a2e6)

## Visualizing the rules:
![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/0c6302b8-7579-4020-ad5d-97f48786c319)

![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/2d2f6ec3-370b-4731-b730-06d33f843516)

## Running time:
- Apriori = 2.03 + 0.03 = 2.06 sec
- FP-Growth = 0.74 sec
- Eclat = 65 sec (Run time for Eclat is high because there is no constraint on lift and all rules are generated which requires many recursive iterations)

## Key differences:

![image](https://github.com/rushildpatel/Market-basket-analysis/assets/73517149/195e56b0-a178-4ec7-8165-ee08b89ba02b)










