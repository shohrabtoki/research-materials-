# On-Line Building Optimization Using Deep Reinforcement Learning 

## Author: Elena Mocanu et al 
## Publisher: IEEE 

**0. Summary**

The paper duscussed the benefit of using deep learning and reinforcement learning in the context of smart grid environment to perform on-line optimization of schedules for building energy management systems. They used two learning methods: 

1. Deep Q-learning 
2. Deep policy gradient 

The proposed method was validated by the use of [Pecan street data.](https://www.pecanstreet.org/)

**1. Problem Formulation** 

2.1 Cost Minimization Problem 

In this paper, two price components are considered to formulate the cost minimization function. One is the price value set by the utility company and other one is the price value at which the utility company busy from the end-users at time, t. 

2.2 Peak Reduction Problem 

In this paper, the assume the price for elctricity generation and consumption are equal. Therefore, the cost minimization problem becomes a peak reduction problem. However, the fuction is extended considering the types of loads available such as shiftable, non-shiftable and controllable. 

2.3 Electrical Device Constraints 

**2. Methodology** 

In this paper, they used two reinforcement learning methods to accomplish the task. And deep neural network is used to aprroximate the value funtion for each of the methods. 

![](https://github.com/mdshohrabhossain/research-materials-/blob/master/Figures/paper2.1.PNG)

**3. Novelty** 

The use of deep policy gradient is quite rare in terms of building energy managment systems. This is the first paper I have read so far introduced this method which even performs better than the Deep Q learning in an on-line learning. 

**4. Improvement** 

1. More extensive research can be done to further evaluate the comparison between on-line and off-line learning

2. They used single agent to do all the task while multi-agent concept can be applied to evaluate the performance of the given methods 
