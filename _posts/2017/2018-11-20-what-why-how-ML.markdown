---
layout: "post"
title: "What Why and How of ML : an intro"

excerpt: ""
comments: true
---
<div style="text-align: justify"> 
In Machine Learning we assume that there exists a pattern in data which cannot be pinned down mathematically but can be learnt.
There comes no harm in applying machine learning techniques to data regardless of whether there exists a pattern in data, as we 
can determine the existence of the pattern and we can measure the amount of learning.
The learning happens over a set of Hypothesis functions (H) and the outcome is a final hypothesis function(h) that is nearly similar
to the target function (t). The target function (t) is an unknown function that represents the exact mapping in the data (D).
</div>
<br />
<div class="fig figcenter fighighlight">
  <img src="/images/wwhml/1.png"  width="300" height="300">
</div>

So, we are using a set of observations to uncover an underlying process, the underlying process is the target function here.
In a real world scenario the data can be sometimes labelled, but mostly unlabelled and often sometimes the label can be time delayed.
Supervised learning algorithms use labelled data to generate a hypothesis function. One such example can be seen by 
considering a Hypothesis set, the perceptrons, where in case of linearly separable dataset(D) the perceptron learning algorithm 
can successfully navigate the Hypothesis space and arrives at a solution (h).  

> Perceptron learning<br />
>*Dataset* *D* : {*(**x**<sub>1</sub>, y<sub>1</sub>), (**x**<sub>2</sub>, y<sub>2</sub>), (**x**<sub>3</sub>, y<sub>3</sub>), ..... (**x**<sub>N</sub>, y<sub>N</sub>)*}<br />
>*Hypothesis set* *H* : sign(**w**<sup>T</sup>**x**)
>> perceptron implements _h(**x**)_ = sign(**w**<sup>T</sup>**x**)<br />
>>> pick a misclassified sample *(**x**<sub>i</sub>, y<sub>i</sub>)* : *y<sub>i</sub>* != sign(**w**<sup>T</sup>**x**<sub>i</sub>)<br />
>>> update the weight vector <span style="color:green"> **w** </span> = <span style="color:red">**w**</span> + *y<sub>i</sub>* ***x**<sub>i</sub>*<br /> 

To find the patterns in the unlabelled data we use unsupervised learning approaches. In scenarios where a sequence of inputs
in time are mapped to a output reward we use reinforcement learning algorithm. For example in the game of chess, the player
makes many moves and finally arrives at a reward of either win or lose. 





<br />--- more to come