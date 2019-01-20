TO BE UPDATED
# Report of Assignment
This report explains the method used to solve the Banana Navigation Project.
The submission includes a file in the root of the GitHub repository or zip file (one of Report.md, Report.ipynb, or Report.pdf) that provides a description of the implementation.

## Learning Algorithm
The report clearly describes the learning algorithm, along with the chosen hyperparameters. It also describes the model architectures for any neural networks.
* To solve this reinforcement learning problem, [Deep Q Learning](https://towardsdatascience.com/self-learning-ai-agents-part-ii-deep-q-learning-b5ac60c3f47) is used with the architectures depicted in the following images. All hidden layers use relu activation function.
<img src="https://github.com/alifahsanul/RLnanodegree/blob/master/banana_catcher/image/nn.jpg" alt="drawing" width="500"/>
* For tutorial on how to use PyTorch to build Deep Q Network, visit this [page](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html).
* Hyperparameters used:
  * Discount factor &gamma; = 0.99
  * Learning Rate &alpha; = 5 &times; 10<sup>-4</sup>

## Plof of Rewards
The agent was trained for 604 episodes before reaching 13 average score for 100 consecutive episodes.
![alt text](https://github.com/alifahsanul/RLnanodegree/blob/master/banana_catcher/image/Score.jpg)

Trained agent at play:
![alt text](https://github.com/alifahsanul/RLnanodegree/blob/master/banana_catcher/image/agent_simulate.gif)
## Ideas for future work
The submission has concrete future ideas for improving the agent's performance.
