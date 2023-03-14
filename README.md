# Codeless-AI-ML-2022

## Overview
Theproject is about statistics of Liverpool team for last three season. There are result in each mathc all of 118 mathces. 


The main objective of the project is to look win rate, draw rate, lose rate for prov the performance of Liverpool team.




![Screenshot (8)](https://user-images.githubusercontent.com/110332645/224911546-f819dd5a-09b3-48eb-ac5b-720ce6d5ec1a.png)



## Tools
- Knime

## Columns
- Opponent team
- Scores
- Win rate
- Draw rate
- Lose rate
- Performances

## Method
My dataset is in format of csv, so I use node csv reader to acces it.



![image](https://user-images.githubusercontent.com/110332645/224916054-7fd1b076-fc0d-4410-bb08-780ac1c58f49.png)





In mydataset have mistake word, Therefore the data is distorted. Then I use Rule engine node to solved the data.

![image](https://user-images.githubusercontent.com/110332645/224915817-8ff5c213-e748-43db-a61f-7f7cbe3a49f7.png)



This is the Bar chart to show The match meets all Liverpool teams.



![Screenshot (14)](https://user-images.githubusercontent.com/110332645/224916758-eaa5aed4-6900-47b8-8ed3-9110db08923b.png)



For this is pie chart to show win rate, draw rate, lose rate of Liverpool team for last three saeson.



![Screenshot (38)](https://user-images.githubusercontent.com/110332645/224916941-bfbbcb69-f6b3-473e-b53d-f5dae0ea0d38.png)




In each match, Average of shots for Lierpool team is 1 score. Prov that from Blox plot node.



![Screenshot (44)](https://user-images.githubusercontent.com/110332645/224917013-481b64a7-2a4f-4d5f-a5a1-bbd93251d0ad.png)





I divided the data into 80% and 20%. 80% percent for training and 20% for testing.I use Three model to prov or to see which model is the best.
I use Dicission tree learner, SVM leaner, PNN laener (DDA)




![Screenshot (45)](https://user-images.githubusercontent.com/110332645/224917475-bf006823-a0da-4cdb-8160-41c7f9541cfc.png)




As we see the Dicission tree leaner is the best model. In have accuracy100%


![Screenshot (46)](https://user-images.githubusercontent.com/110332645/224918082-167cb451-9d0d-4d6c-b2a6-9c21aa31d78a.png)


## Conclusion
I use knime to determine which machine learning model is the most suitable to be used for the provided dataset. Liverpool team is a best team on the world. Maybe cuz of Liverpool team have good players and good coach. 
The most rate is win rate. 

## Author
- Mr. Hafis Madeng 631431023

