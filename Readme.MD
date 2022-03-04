Run python Controller.py to train the code.

Optional:
* You can set: 
 - play: Set to run in interactive mode:
       0 = no interactive mode
       1 = play as the bot
       2 = play as the enemy
* You can also provide your own Map by modifying map in environment Class
* You can choose deferent train algorithems: egreedy for SARSA and greedy for normal Q-learning.
   Also possible if you defined your own step
* You can change the parameters in the controller:
     - episodes: number of episodes to train the agent.
     - trainingReportRate: how many episodes pass before printing out a report during training

More detailed explaination could be found in the code comment.