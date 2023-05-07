Download Link: https://assignmentchef.com/product/solved-ie613-assignment2
<br>
<strong>Question 1  </strong>Suppose that X is σ−subgaussian and X<sub>1 </sub>and X<sub>2 </sub>are independent and σ<sub>1 </sub>and σ<sub>2</sub>−subgaussian respectively, then:

<ol>

 <li>E[X]=0 and Var[X] ≤ σ<sup>2</sup>.</li>

 <li>cX is |c|σ−subgaussian for all c ∈ R.</li>

 <li></li>

</ol>

<strong>Question 2 </strong>Suppose that X is zero-mean and X ∈ [a,b] almost surely for constants a &lt; b.

<ol>

 <li>Show that X is (b − a)/2−</li>

 <li>Using Cramer-Chernoff method shows that if X<sub>1</sub>,X<sub>2</sub>,…,X<sub>n </sub>are independent and X<sub>t </sub>∈ [a<sub>t</sub>,b<sub>t</sub>] almost surely with a<sub>t </sub>&lt; b<sub>t </sub>for all t, then prove</li>

</ol>

<strong>Question 3 </strong>[Expectation of maximum] Let X<sub>1</sub>,…,X<sub>n </sub>be a sequence of σ-subgaussian random variables (possibly dependent) and Z = max<sub>t</sub><sub>∈[n</sub><sub>] </sub>X<sub>t</sub>. Prove that

1.

2.for any δ ∈ (0,1).

<strong>Question 4 </strong>[Bernstein’s inequality] Let                             be a sequence of independent random vari-

n

ables with X<sub>t </sub>− E[X<sub>t</sub>] ≤ b almost surely and S = <sup>P</sup>(X<sub>t </sub>− E[X<sub>t</sub>]) and v = <sup>P </sup>V [X<sub>t</sub>].

t=1                                                                   t=1

<ol>

 <li>Show that is increasing.</li>

 <li>Let X be a random variable with E[X] = 0 and X ≤ b almost surely. Show that E[exp(X)] ≤ 1 + g(b)V [X].</li>

 <li>Prove that for all α ≥ 0. Prove that this is the best possible approximation in the sense that the 2 in the denominator cannot be increased.</li>

</ol>

2-1

2-2                                                                                                                                                              Homework 2: March 19

<ol start="4">

 <li>Let and and prove that</li>

 <li>Use the previous result to show that</li>

</ol>

<strong>Question 5 </strong>Show that

implies the regret of an optimally tuned Explore-then-Commit (ETC) algorithm for subgaussian√             2−armed

bandits with means µ<sub>1</sub>,µ<sub>2 </sub>∈ R and ∆ = |µ<sub>1 </sub>− µ<sub>2</sub>|, satisfies R<sub>T </sub>≤ ∆ + C T where C &gt; 0 is a universal constant.

<strong>Question 6</strong>Fix δ ∈ (0,1). Modify the ETC algorithm to depend on δ and prove a bound on the pseudo-regret of ETC algorithm that holds with probability 1 − δ where A<sub>t </sub>is the arm chosen in the round t.

Hint: Choose ‘m’ appropriately in the regret upper bound of ETC algorithm which is proved in the class.

<strong>Question 7  </strong>Fix δ ∈ (0,1). Prove a bound on the random regret of ETC algorithm that holds with probability 1 − δ. Compare this to the bound derived for the pseudo-regret in the question 5. What can you conclude?

<strong>Question 8 </strong>Assume the rewards are 1−subgaussian and there are k ≥ 2 arms. The −greedy algorithm depends on a sequence of parameters. First it chooses each arm once and subsequently chooses A<sub>t </sub>= argmaxµˆ<sub>i</sub>(t − 1) with probability  and otherwise chooses an arm uniformly at random.

i

<ol>

 <li>Prove that if, then.</li>

 <li>Let ∆<sub>min </sub>= min{∆<sub>i </sub>: ∆<sub>i </sub>&gt; 0} where ∆<sub>i </sub>= µ<sup>? </sup>− µ<sub>i</sub>, and where C &gt; 0 is a sufficiently large universal constant. Prove that there exists a universal C<sup>0 </sup>&gt; 0 such that</li>

</ol>

.

<strong>Question 9 </strong>Fix a 1−subgaussian k−armed bandit environment and a horizon T. Consider the version of UCB that works in phases of exponentially increasing length of 1,2,4,…. In each phase, the algorithm uses the action that would have been chosen by UCB at the beginning of the phase.

Homwork 2: March 19                                                                                                                                                                2-3

<ol>

 <li>State and prove a bound on the regret for this version of UCB.</li>

 <li>How would the result change if the l<sup>th </sup>phase had a length of dα<sup>l</sup>e with α &gt; 1?</li>

</ol>


