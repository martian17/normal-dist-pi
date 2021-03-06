# Calculating π using random walk and normal distribution  

### brief description:
This program calculates π using random walk and normal distribution.<br>
Given a fact that a 1d random walk results in a normal distribution, we can exploit this to calculate pi by reversing the equation of normal distribution which looks like the following.
<br>
f(x) = 1/(σ√(2π))*e^(-1/2*((x-μ)/σ)^2)<br>
<br>
in which<br>
f(x) is the probability distribution,<br>
σ is the standard deviation,<br>
μ is the average.<br>
<br>
notice<br>
f(μ) = 1/(σ√(2π))<br>
therefore<br>
π = 1/(2*σ^2*f(μ)^2)<br>
<br>
we can calculate μ and σ with commonly known means, and then we can calculate f(μ) by takeing a small strip from the distribution center, and dividing it with its width.<br>
<br>
<a target="_blank" href="https://codepen.io/MartianLord/full/QWdEwOz">Demo</a><br>
<a target="_blank" href="https://github.com/martian17/normal-dist-pi">Github</a><br>
<a target="_blank" href="https://en.wikipedia.org/wiki/Normal_distribution">Normal Distribution (Wikipedia)</a><br>
<a target="_blank" href="https://en.wikipedia.org/wiki/Standard_deviation">Standard Deviation (Wikipedia)</a><br>
<a target="_blank" href="https://en.wikipedia.org/wiki/Random_walk">Random Walk (Wikipedia)</a><br>