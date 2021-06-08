
## Deep-Q-Network--Reinforcement-Learning-Code-Project
#### Deep Learning and Multimedia Information Analysis

#### MSc in Artificial Intelligence

#### Aristotle University of Thessaloniki

###### Homework 3

Deep Reinforcement Learning

###  1.	Q-learning Agent play Frozen Lake - Reinforcement Learning
	
	Notebook --->Q-learning Agent play Frozen Lake - Reinforcement Learning.ipynb
	
###  2.	Deep Q-network to learn to balance a pole on a moving cart - PyTorch project
        
	Notebook --->Deep Q-network code PyTorch project-final.ipynb

### A) Frozen Lake

we'll implement the Q-learning algorithm to train an agent to play OpenAI Gym's Frozen Lake.

![frozen lake winter](https://user-images.githubusercontent.com/56552010/121138314-3b1ab400-c840-11eb-97eb-9d8b8bfa53af.jpg)

### B) CartPole-v0
We're going to be building and training a deep Q-network to learn to balance a pole on a moving cart.
The cart and pole problem consists of a cart that can move left and right along a frictionless track. The cart has a pole attached to the top of it, which starts out in a vertical upright position, however, by design, the pole will fall either to the left or right when not balanced. The goal here is to prevent this pole from falling over. A reward of +1 will be given for each time step that the pole remains upright, and an episode will deemed over when the pole is more than 15 degrees from vertical or when the cart moves more than 2.4 units from the center of the screen.

##### So, essentially, the longer the pole remains upright without deviating too far from the center of the screen, the more reward our agent will get.

![poster](https://user-images.githubusercontent.com/56552010/121078752-037d1f00-c7e2-11eb-87da-f0d22d165de2.jpg)


###### CartPole score during Training :

![Screenshot from 2021-06-07 23-54-55](https://user-images.githubusercontent.com/56552010/121086556-f9601e00-c7eb-11eb-814c-989d95bb3a01.png)

###### CartPole score during Training @Episode 1704, Training time 10 hours :

![Screenshot from 2021-06-08 09-53-59](https://user-images.githubusercontent.com/56552010/121138617-8cc33e80-c840-11eb-8926-d78ff7d18bc7.png)

###### CartPole score during Training @Episode 2000, Training time 13 hours :

![Screenshot from 2021-06-08 11-23-31](https://user-images.githubusercontent.com/56552010/121182333-a75edd00-c86b-11eb-8b06-654a4bf805b9.png)
