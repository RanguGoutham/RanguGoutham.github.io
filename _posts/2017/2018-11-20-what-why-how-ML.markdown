---
layout: "post"
title: "What Why and How of ML : an intro"

excerpt: ""
comments: true
---
In Machine Learning we assume that there exists a pattern in data which cannot be pinned down mathematically but can be learnt.
The learning happens over a set of Hypothesis functions (H) and the outcome is a final hypothesis function(h) that is nearly similar
to the target function (t). The target function (t) is an unknown function that represents the exact mapping in the data (D).


<div class="fig figcenter fighighlight">
  <img src="/images/wwhml/1.png"  width="300" height="300">
</div>


In a real world scenario the data can be sometimes labelled, but mostly unlabelled and often the label can be time delayed.
Supervised learning algorithms use labelled data to generate a hypothesis function. One such example can be seen by 
considering a Hypothesis set, the perceptrons, where in case of linearly separable dataset(D) the perceptron learning algorithm 
can successfully navigate ths Hypothesis space and arrives at a solution (h).  

> Perceptron learning
>*Dataset* *D* : {*(**x**<sub>1</sub>, y<sub>1</sub>), (**x**<sub>2</sub>, y<sub>2</sub>), (**x**<sub>3</sub>, y<sub>3</sub>), ..... (**x**<sub>N</sub>, y<sub>N</sub>)*}<br />
>*Hypothesis set* *H* : sign(**w**<sup>T</sup>**x**)
>> perceptron implements _h(**x**)_ = sign(**w**<sup>T</sup>**x**)
>>> pick a misclassified sample *(**x**<sub>i</sub>, y<sub>i</sub>)* : *y<sub>i</sub>* != sign(**w**<sup>T</sup>**x**<sub>i</sub>)<br />
>>> update the weight vector <span style="color:green"> **w** </span> = <span style="color:red">**w**</span> + *y<sub>i</sub>* ***x**<sub>i</sub>* 

 



