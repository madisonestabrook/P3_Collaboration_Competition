# Summary
This project is my third project on [Udacity's Deep Reinforcement Learning Nanodegree (Facebook PyTorch Nanodegree Scholarship Phase 3)](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893). This project uses a Deep Deterministic Policy Gradients (*DDPG*) Network to teach a pair (2) agents to play tennis.

# Project Details
The environment is the `Tennis` enviroment, which is an extension of Unity’s [UnityEnvironment](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md). The `Tennis` environment has different versions for [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip), [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip), [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip) and [MacOSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip). The following screenshot shows the environment set-up:

![This is what the environment looks like](Environment_Screenshot.png)

The state is a [numpy](https://numpy.org/) array of length 8.

The action is how the agent reacts to the environment. 

![This is a plot of the scores](env_solved_p3.png)

The environment is considered ‘solved’ when the __moving__ average (arithmetic mean) score over the last 100 episodes is greater than or equal to __+0.5__.

# Directions
Complete the following steps interact with this project:

1. Determine your operating system (*OS*) 
   - Determine your number of bits (__only__ if you are using Windows) - click [here for help from Microsoft](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64)
2. Click the relevant hyperlink from the following list
   - [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
   - [Windows (32-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
   - [Windows (64-bit)](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
   - [MacOSX](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
3. Place the file you downloaded in this repo's folder on your computer and unzip (or decompress) the file [click here for help](https://github.com/udacity/deep-reinforcement-learning/tree/master/p3_collab-compet)
4. Open `Tennis.ipynb` using Jupyter Notebook (or Jupyter Lab)
5. Click **Cell>Run All**
6. Be patient as the magic happens
