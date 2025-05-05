# statistical-models-project-1-solved
**TO GET THIS SOLUTION VISIT:** [Statistical Models Project 1 Solved](https://www.ankitcodinghub.com/product/statistical-models-project-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;98968&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Statistical Models Project 1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem 1: Conditional independence and BNs

</div>
</div>
<div class="layoutArea">
<div class="column">
Consider the following graphical structures, corresponding to (different) Bayesian networks. For which network does the statement A ⊥ B | C hold? For which does the statement A ⊥ B hold? Prove your answers by the laws of probability.

</div>
</div>
<div class="layoutArea">
<div class="column">
BAAB

a) b)

CC

Problem 2: Markov blanket

Consider the following graphical structure of a Bayesian network:

ABF ED

GC

</div>
</div>
<div class="layoutArea">
<div class="column">
Determine the Markov blanket MB(D) of node D and show that the conditional probability P(D | A,B,C,E,F,G) is the same as P(D | MB(D)).

Problem 3: Learning Bayesian networks from protein data

In this exercise, we will use the R package BiDAG1 to learn Bayesian networks from protein data. The data provided in sachs.data.txt consists of the measurements of 11 phosphorylated proteins and phospholipids derived from primary immune system cells, subjected to both general and specific molecular interventions [2]. (Hint: read the help files of the package and use default parameters unless otherwise stated.)

(a) First, run set.seed(2022) for reproducibility. Read in the data from sachs.data.txt. Report the number of variables n and the number of observations N. Randomly split the data into 80% training data and 20% test data. Initialize the parameters using the function scoreparameters with the training data and the Bayesian Gaussian equivalent (BGe) score [3, 4]. (1 point)

</div>
</div>
<div class="layoutArea">
<div class="column">
1Run install.packages(“BiDAG”) in the R console. Then load the package by running library(BiDAG).

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
[Note: The BGe score is a fully-decomposable marginal likelihood function P(D | G) for scoring Bayesian networks. The main underlying assumption is that the data is normally distributed with N(μ,W−1). The precision matrix W follows a Wishart prior Wn(T−1,αw), where αw &gt; n − 1 is the degrees of freedom and T is the positive definite parametric matrix. The mean vector μ follows a normal prior N (ν, αμW ) with αμ &gt; 0.]

(b) Learn a Bayesian network using the order MCMC algorithm. Plot the directed acyclic graph (DAG). Evaluate the log BGe score of the test data against the estimated DAG. (Hint: one can use the R package graph for the plot.) (1 point)

(c) One of the arguments in the scoreparameters function is bgepar = list(am = 1, aw = NULL), which corresponds to the hyper-parameters αμ and αw for the BGe score. By default, αμ = 1 and αw = n + αμ + 1.

Now, consider the set of values {10−5, 10−3, 10−1, 10, 102} for am and keep aw = NULL fixed. For each value, repeat the process of splitting the data, initializing the parameters, and learning the DAG for 10 times. Then, report the average number of edges in the DAGs and the average log BGe score of the test data in a table as the one shown below. Remember to run set.seed(2022) for reproducibility. (Hint: running the code parallelly with the package parallel can help reduce the runtime.)

Parameter am 10−5 10−3 10−1 10 102 Average number of edges

Average BGe score of the test data

What do you observe? Choose the value of am corresponding to the highest test BGe score and plot the DAG re-learned from the whole dataset. (3 point)

References

<ol>
<li>[1] &nbsp;Suter, P., Kuipers, J., Moffa, G., &amp; Beerenwinkel, N. (2021). Bayesian structure learning and sampling of bayesian networks with the r package BiDAG. arXiv preprint arXiv:2105.00488.</li>
<li>[2] &nbsp;Sachs, K., Perez, O., Pe’er, D., Lauffenburger, D. A., &amp; Nolan, G. P. (2005). Causal protein- signaling networks derived from multiparameter single-cell data. Science, 308(5721), 523-529.</li>
<li>[3] &nbsp;Geiger, D., &amp; Heckerman, D. (2002). Parameter priors for directed acyclic graphical models and the characterization of several probability distributions. The Annals of Statistics, 30(5), 1412-1440.</li>
<li>[4] &nbsp;Kuipers, J., Moffa, G., &amp; Heckerman, D. (2014). Addendum on the scoring of Gaussian directed acyclic graphical models. The Annals of Statistics, 42(4), 1689-1691.</li>
</ol>
</div>
</div>
</div>
