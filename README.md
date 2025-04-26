# cs3316-final-project-solved
**TO GET THIS SOLUTION VISIT:** [CS3316 Final Project Solved](https://www.ankitcodinghub.com/product/cs3316-reinforcement-learning-final-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127051&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3316 Final Project Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
1 Introduction

The goal of the final project is to implement two kinds of model-free RL methods: value-based RL and policy-based RL. In this project, you are free to choose RL methods to solve two benchmark environments.

2 Review

2.1 Value-Based Reinforcement Learning

Value-based methods strive to fit action value function or state value function, e.g. Monte-Carlo, TD learning for model-free policy evaluation and SARSA, Qlearning for model-free control. Off-policy training mode is easy to implement in value-based method. DQN achieves remarkable performance under off-policy. In DQN (Silver, 2015), past experiences that stored in experience buffer can be used to train the deep Q network. In many transfer algorithms for DQN, expert’s experiences are often used to fit the current value function. Hence value-based methods are often more sample efficient.

Although value-based RL like DQN and its variants achieve remarkable performance in some task, e.g. atari games, the inherent drawbacks hinder its development.

• First, action selection in value-based methods is according to the action values, which is inherently unsuited to continuous action space.

• Second, non-linear value function approximation like neural network is unstable and brittle with respect to their hyperparameters.

2.2 Policy-Based Reinforcement Learning

3 Experiment Environments and Requirements

OpenAI provides benchmark environments toolkit ‘gym’ to facilitate the development of reinforcement learning. 6 types of experiment environments are available (access https://www.gymlibrary.dev/ for more). In our project, you are required to train agents over Atari and MuJuCo. You should choose appropriate and effective RL methods to achieve high scores in the environments as possible as you can. To get started with gym, refer to https://github.com/ openai/gym.

3.1 Atari Games Environment Description

The Atari 2600 is a home video game console developed in 1977. Dozens of games are provided by ‘gym’. In our project, we limit the choice of environment to the following:

• VideoPinball-ramNoFrameskip-v4

• BreakoutNoFrameskip-v4

• PongNoFrameskip-v4

• BoxingNoFrameskip-v4

You should at least choose one environment to test your value-based method.

3.2 MuJuCo Continuous Control Environment Description

MuJuCo stands for Multi-Joint dynamics with Contact, which is originally designed for model-based control methods test. Now, MuJoCo simulator is a commonly adopted benchmark for continuous control. We narrow down the choice of environments to the following:

• Hopper-v4

• Humanoid-v4

• HalfCheetah-v4

• Ant-v4

You should at least choose one environment to test your policy-based method.

3.3 Requirements

Here is the experiment content:

• You are required to choose and implement value-based RL algorithm and test it on at least one of the Atari game listed above.

• You are required to choose and implement policy-based RL algorithm (except Soft Actor-Critic) and test it on at least one of the MuJuCo simulator listed above.

The algorithms you choose in the scope of value-based and policy-based are non-limited. For the ease of running your submitted codes and grading, we have some limitations in this project.

• Programming language: python3

• The final results should use the experiment Name like following: python run.py –env name BreakoutNoFrameskip-v4

4 Report and Submission

4.1 About Submission

• You are required to accomplish this project individually.

• Your report and source code should be zipped and named after ”Name StuID”. Besides, README file that shows the instructions to run your code should be included inside the zip file.

4.2 About Report

The report should cover but not be limited to the following sections:

• The description of the algorithms you use.

• The performance of the algorithms you achieve in selected environments

• The analysis about the algorithms.

4.3 Bonus

• Modification of the algorithms that achieves better performance.

• Test your algorithms on more than one environment.

• Excellent analysis about the algorithms.
