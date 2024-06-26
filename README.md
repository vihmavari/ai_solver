# A 2048 AI Solver

Результат 100K игр сыгранных 

|max tile| % of games| accumulated %| reversed accumulated %| 
|--------|-----------|--------------|---------|
|16384   | 0.177%    |        0.177%|100.000%|
|8192    |34.500%    |       34.677%| 99.823%|
|4096    |43.819%    |       78.496%| 65.323%|
|2048    |15.656%    |       94.152%| 21.504%|
|1024    | 4.340%    |       98.492%|  5.848%|
|512     | 1.144%    |       99.636%|  1.508%|
|256     | 0.261%    |       99.897%|  0.364%|
|128     | 0.064%    |       99.961%|  0.103%|
|64      | 0.026%    |       99.987%|  0.039%|
|32      | 0.007%    |       99.994%|  0.013%|
|16      | 0.005%    |       99.999%|  0.006%|
|8       | 0.001%    |      100.000%|  0.001%|

<img src="plot1.png" />

The average score is 85351.8 and the average length of a game is 3733.6 steps.

The following graph shows how many games left after certain steps in the 100K simulations:

<img src="plot2.png" />

The graph indicates that the AI performs relatively weak in early stage of the game.


To run https://github.com/tjwei/2048-NN/blob/master/my2048-rl-theano-n-tuple-Copy7.ipynb you need selenium firefox lasagne and cudnn

It is likely to reach 2048 tiles in less than 100 games of learning (sometimes less than 50 games).

Following plots are the average steps and average score during the training(for every 100 training games). 

<img src="avg_step.png" />

<img src="avg_score.png" />

