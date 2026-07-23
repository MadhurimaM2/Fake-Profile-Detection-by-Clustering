# Data 602 Finals : Fake Profile Detection by Clustering

## Objective
To identify likely fake or suspicious social media profiles using unlabeled behavioral data.  

## Approach
This problem is treated as a semi-supervised learning and the following is the plan:  

Perform basic EDA and feature engineering  
Use clustering to discover natural groups  
Use SME for some labels  
Assign pseudo-labels to clusters  
Train multiple models on pseudo-labeled data  

## Evaluation Strategy
Internal validation: cross-validation on pseudo-labels  
Check generalization: performance on unseen data  
Final evaluation: compare predictions with actual labels at the end  
