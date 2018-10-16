# Deep-Q-Network-Navigation

<h1>Project 1: Navigation</h1>
  <h2>Introduction</h2>
    <div>
      <p>The purpose of this navigation project is to train an agent to navigate and collect bannanas in a large open square world</p>
      <p>Eachtime the agent collects a yellow banana the agent is rewarded with +1 reward, however, if a blue banana is picked up the agent then receives a score of -1.  Throughout this environment the goal of the game is to select a strategy that enables the agent to maximize the number of yellow bananas that it eats which minimizing the number of blue bananas that it stumbles across</p>
      <p>Overall, if each state space has 37 dimensions and contains the agents velocity, and the ray based perception of objects around the agent's forward direction.  During this time the agent must determine the best set of actions to take.  4 discrete actions that are available include the following</p>
      <ul>
        <li><b>0:</b> move forward</li>
        <li><b>1:</b> move backward</li>
        <li><b>2:</b> turn left</li>
        <li><b>3:</b> turn right</li>
      </ul>
      <p>To solve the environment an avg. score of over 13 in any 100 episode period</p>
      <p>Note that for the sake of simplicity to read all classes and subsequent steps were included in a simple file to facilitate learning from anyone that might want to reference this at a later time</p>
    </div>
  <h3>Requirements</h3>
    <div>
      <p>First ensure that you have a package manager such as anaconda and an environment that meets requirements listed within requirements.txt within my git repo</p>
      <p>Follow instructions from the UDACITY github repo located at https://github.com/udacity/deep-reinforcement-learning#dependencies to make sure your python environment is setup correctly with all the packages you need to get things running.</p>
    </div>
  <h3>Learn the Code, Run the Code.</h3>
    <div>
      <ol>
        <li>Familiarize your self with the environment, action, and state spaces</li>
        <li>Define variables (included are what I used)</li>
        <li>Become acquainted with the fully connected neural net used within the QNetwork class</li>
        <li>Refer to the Agent class to view Step, Action, and Learning methods for the Deep Q Network's overall architecture</li>
        <li>Finally, the DQN class brings the previous classes together in order to train the agent using Deep Q learning.
        <li>After reviewing relevant class train the agent to the environment by creating a training instance of dqn class from the Agent class</li>
        <li>Once done training the network next steps can include tyring different implementations such as double DQN, dueling DQN, or even Rainbow!</p>
      </ol>
    </div>
