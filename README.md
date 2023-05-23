# Banana Navigation Project
Project One Submission for Udacity Reinforcement Learning Course<br>

![Screenshot of banana environment](doc/BannerImage.png)<br>

This is an implementation of Deep Reinforcement Q-Learning, applied to train an agent with four possible actions (move left, right, forward, or backward), to pick up yellow bananas and avoid blue bananas.  Pickup of a yellow banana yields a score of +1, a blue banana a score of -1.<br><br>

The details of the state observables were not provided in the course material, but believe are related to directional perception (possibly multiple modes).

The criteria for solving the environment with the agent, is an achievement of an average score of at least +13 over 100 consecutive episodes.  The Udacity benchmark was to solve the environment in 1800 episodes.  This implementation solved the environment in 795 episodes.

+ Follow instructions [here](https://github.com/udacity/Value-based-methods#dependencies) to set up the environment, *with the following changes:
  - Before running `pip install .`, edit `Value-based-methods/python/requirements.txt` and remove the `torch==0.4.0` line
  - After running `pip install .`, run the appropriate PyTorch installation command for your system indicated [here](https://pytorch.org/get-started/locally/)
  - Continue following the instructions [here](https://github.com/udacity/Value-based-methods#dependencies) to their conclusion.
+ Download the appropriate Unity Environment for your platform:
  - [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
  - [Mac OSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
  - [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
  - [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
+ Place the Unity Environment zip file in the `p1_navigation/` folder of the repository cloned in the first step, and unzip the file.
+ Create jupyter notebook instance from terminal with `jupyter notebook` command.  Navigate to BananaNavCode.ipynb and follow the instructions there to train or evaluate an agent.
