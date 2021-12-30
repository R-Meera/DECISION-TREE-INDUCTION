# DECISION-TREE-INDUCTION

The dataset used to implement this Decision Tree Induction Algorithm is retrived from UCI Machine Learning Repository 

I have created a train and test data in 80 - 20 split. 
Decision tree is generated using the info gain measure.
I have noticed that the algorithm has a nominal accuracy of 100 percent, but due to the small sample size,the decision tree is directly to derive conclusions about the system in this case, and for data sets of comparable low complexity.
On each level, the algorithm evaluates a new attribute to split. I can see that different attributes being selected for each child in the second level depending on which branch was taken in the first level. Each branch, in fact, chooses a new partition with a different entropy. To generate the full decision tree,repeat this procedure for each node in the second level.
