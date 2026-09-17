# Hands-on Section 1
Hands-on practice for CSE 60745 Special Topics In Machine Learning and Artificial Intelligence

### Practice 1: Friend Recommendation
**Context:**
Social networks can be represented as graphs where users represent nodes and friendships represent edges.

**Assignment:**
To design a friend recommendation model using graph structural properties. 

[`friend_rec.ipynb`](https://github.com/angelesmarinbatana/hw1/blob/main/friend_rec.ipynb) contains a model that takes graph features as input data and returns a ranking score of who is most likely to be someone's friend. I did this by:
* calulating graph properties for each pair 
* building a regression model to predict the probability that each candidate pair (i did a pair of girls as an example) would actually be directly connected
* ranking all the potential condidates by their score where the highest score means a good friend match. 

## Practice 2: Community Detection
**Context:**
Graphs can help us identify potential communities in a social network. 

**Assignment:**
Find communities in a network graph given a network of 7,624 nodes and 27,806 edges. Group them together using one sigle repeating rule

[`com_detec.ipynb`](https://github.com/angelesmarinbatana/hw1/blob/main/com_detec.ipynb) contains an algorithm for finding communities in networks. You keep picking whatever community most of your friends are in. At the end, friend clusters all pick the same group and those become communities. 
