# PolyAI 2021 hackathon 

This directory describes the work I've done for the 2021 hackathon organised by PolyAI. 

The hackathon was proposed for students of Polytechnique Montreal, where most of the participants didn't have a lot of experiments in machine learning. 

Therefore, we offered 6 challenges with different difficulties. We did 3 class of challenges : easy, medium and difficult. Each difficulty had two challenges associated. 


## Challenges 

I'm going to describe only the challenges I've participated in the organisation. 

### 1. Easy : Supraconductor regression 

This challenge was a regression task for critical temperature prevision.

I got the dataset from a kaggle challenge, and I added some noise to the data, NaN values and some outliers. 

The aim was to enable beginners to learn how to do basic pre-processing, and then use machine learning models (mostly using sklearn). 

The link of the Kaggle challenge is the following : 

https://www.kaggle.com/competitions/code-ml-2021-challenge-1.

### 2. Easy : Solve the maze with reinforcement learning 

The aim of this challenge was to solve a maze using reinforcement learning.

I implemented the maze using openai syntax. The link to this implementation is the following : 

https://github.com/clementbernardd/code_ml_rl. 

Then, the participants had to implement a basic reinforcement learning algorithm (like SARSA or Q-learning). 
For those who wanted to win the competition, they had to go a little further : try to improve the algorithm by reducing the converging time. 

Participants were evaluated by the number of steps until convergence for 3 different mazes.

The description of the challenge in Kaggle is the following : 

https://www.kaggle.com/competitions/code-ml-2021-challenge-2.


### 3. Hard : Fact-checking : claim-evidence verdict

This challenge aimed to implement part of the fact-checking work. 

I took a subset of a dataset I used during my internship. The aim was, given a pair of claim and evidence, to say whether the evidence refutes, supports or doesn't give enough information on the claim. 

The Kaggle dataset is available in the following link : 

https://www.kaggle.com/competitions/code-ml-2021-challenge-5. 

### 4. Hard : Rocks-Papers-Scissors classification 

This challenge was a non-supervised task. The aim was to label into three categories the images in the dataset : Paper, Scissor or Rock.

We got the dataset from another Kaggle challenge, and we removed the labels. Indeed, a classic supervised challenge would have been too easy, that's why we changed the challenge to be an unsupervised one. 

The link to the Kaggle challenge is the following : 

https://www.kaggle.com/competitions/code-ml-2021-challenge-6-pierre-papier-ciseaux.



