Download Link: https://assignmentchef.com/product/solved-ece4710j-homework-4-visualizing-gradients
<br>
<h2>Visualizing Gradients</h2>

<ol>

 <li>On the left is a 3D plot of f (x, y) — @ — + (y — 3) <sup>2 </sup>. On the right is a plot of its gradient field. Note that the arrows show the relative magnitudes of the gradient vector.</li>

</ol>

<ul>

 <li>From the visualization, what do you think is the minimal value of this function and where does it occur?</li>

 <li>Calculate the gradient V f =</li>

 <li>When Vf 6, what are the values of and y?</li>

</ul>

1

2

<h1>Gradient Descent Algorithm</h1>

<ol start="2">

 <li>Given the following loss function and = [Xi i=l, y = and O<sup>t </sup>, explicitly write out the update equation for 9<sup>t</sup>+ <sup>l </sup>in terms of :ti, Yi, 9<sup>t </sup>, and a, where a is the constant learning rate.</li>

</ol>

L(O, i, j) = —          — log(Yi))

<h2>Convexity</h2>

<ol start="3">

 <li>Convexity allows optimization problems to be solved more efficiently and for global optimums to be realized. Mainly, it gives us a nice way to minimize loss (i.e. gradient descent). There are three ways to informally define convexity.</li>

 <li>Walking in a straight line between points on the function keeps you at or above the function. This works for any function.</li>

 <li>The tangent line at any point lies at or below the function, globally. To use this definition, the function must be differentiable.</li>

 <li>The second derivative is non-negative everywhere (in other words, the function is “concave up” everywhere). To use this definition, the function must be twice differentiable.</li>

</ol>

Is the function described in Question 1 convex? Make an argument visually.

3

<h1>GPA Descent</h1>

<ol start="4">

 <li>Consider the following non-linear model with two parameters:</li>

</ol>

f9(x) = 90 • 0.5 +00 • 01 • + sin(91) • .T2

For some nonsensical reason, we decide to use the residuals of our model as the loss function.

That is, the loss for a single observation is

We want to use gradient descent to determine the optimal model parameters, 90 and 91.

<ul>

 <li>Suppose we have just one observation in our training data, (Xl = 1, .T2</li>

</ul>

Assume that we set the learning rate a to 1. An incomplete version of the gradient descent update equation for O is shown below. 9!) and 91(<sup>t</sup>) denote the guesses for 90 and 91 at timestep t, respectively.

9(t+1)

9(t+1)

Express both A and B in terms of Of),     , and any necessary constants.

<ul>

 <li>Assume we initialize both 08<sup>0</sup>) and 91(<sup>0 </sup>to O. Determine 98<sup>1 </sup>) and Of) (i.e. the guesses for 90 and 91 after one iteration of gradient descent).</li>

 <li>What happens to 90 as t + 00 (i.e. as we run more and more iterations of gradient descent)?</li>

</ul>