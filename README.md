# Toggle_Learning_Rate_On_Gradient_Descent_From_Scratch
Observe/Demonstrate effects of toggling learning rate on Gradient Descent 

## Objective of this notebook
- Toggle learning rate on Gradient Descent Algorithm & Observe the effects
- Details of the **problem statement**  , **data set** ,  **summary of the code/solution**  , **sample output/Prediction** from the program and **final result** of the project are listed in the sections to follow.

## Problem Statement/Prologue
This Note book build upon our previous notebook "Vanilla Gradient Decsent From Scratch" which is present in my repository .In this notebook ,we build on top of that notebook and try to toggle learning rate to observe its effects on convergence.We jump right into toggling learning rate , so if the reader needs more of a background on gradient descent then I would recommend going through the previous notebook(which has detailed comments on Gradient Descent)

## Data Description:
The dataset is manually created for the purpose of this exercise

## Domain:
Deep Learning :Proof of concept

## Summary of the Solution/Code:
- Observe the effects on convergence when learning rate is at an optimim value (LR=0.001)
- Observe the effects on convergence when learning rate is at a very low value (LR=0.00001)
- Observe the effects on convergence when learning rate is at very high value (LR=0.1)
- Refer **python worksheet  Toggle_Learing_Rate_On_GradientDecsent.ipynb** for the solution

## Visualizing Input :

![image](https://user-images.githubusercontent.com/68383273/209479217-1954188c-72ff-49d5-b8b0-cd940459b1f0.png)


The above image depicts the following
- We start at a random line (marked in RED)
- The BLUE line indicates the best fit line which is our target
- We need to arrive at this line through the Gradient Descent Algorithm
- Let us see how changing learning rate affects this convergence


## Result with LR optimum value :

![image](https://user-images.githubusercontent.com/68383273/211151251-c1096d19-176a-4703-8ca9-6aecfdcaba39.png)
![image](https://user-images.githubusercontent.com/68383273/211151265-9cb99748-8f3e-478d-b618-c8e5cff76de3.png)



## Result with LR high value :

![image](https://user-images.githubusercontent.com/68383273/211151369-fe04d42e-2246-47a8-ab39-f73bef039f90.png)
![image](https://user-images.githubusercontent.com/68383273/211151513-99202b9d-a0aa-48f2-b9cc-671a563db500.png)




## Result with LR low value :

![image](https://user-images.githubusercontent.com/68383273/211151549-9230bd96-68c9-4cff-82e4-a16b7cef1cc6.png)
![image](https://user-images.githubusercontent.com/68383273/211151584-2a179318-67d0-4109-9c74-8e597244267f.png)



## References
The following references were used while creating this notebook:
- https://towardsdatascience.com/gradient-descent-from-scratch-e8b75fa986cc by Arseny Turin
- Post Graduation AI/ML Study Material by GL/UAT

