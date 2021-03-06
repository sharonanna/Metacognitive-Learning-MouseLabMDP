# Understanding human metacognitive learning
Mouselab-MDP is a [JsPsych](https://github.com/jodeleeuw/jsPsych/) plugin that renders Markov decision processes (MDP) for participants to navigate through. Optionally, information about the environment can be presented when the participant asks for it by clicking on edges/nodes.

This adaptation can be used to test whether misalignment of rewards increases planning time ie: when the generated rewards are random, the user should take more time to plan a path through the grid with maximal reward.

The python file in experiment/bin/make_trials.py generates the trials.json file that is used in experiment.js which in turn is generated by a coffee script - experiment.coffee

Number of trials can be increased by editing make_trials.py (line 70).

There are 2 experiments: \
Experiment 1 (Spider as player): user can click on nodes (deduction of 1 point) but the reward generated is random.\
Experiment 2 (Plane as player): user can click on edges to view the rewards and then plan a path.

Link to experiment: [MCL Assignment](http://167.172.106.143/publix/4/start?batchId=4&generalSingle&pre)


