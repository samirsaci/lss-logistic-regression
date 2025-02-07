## Lean Six Sigma with Python — Logistic Regression 👷
*Replace Minitab with Python to perform a Logistic Regression to estimate the minimum bonus needed to reach 75% of a productivity target*


<p align="center">
  <img align="center" src="https://miro.medium.com/max/1280/1*VKEztWWOO8ve3Fk3uzs60Q.png">
</p>

Lean Six Sigma (LSS) is a method based on a stepwise approach to process improvements. This approach usually follows 5 steps. 
(Define, Measure, Analyze, Improve and Control) for improving existing process problems with unknown causes.

### Youtube Video
Find in the link below a short animated explained video to understand the concept behind this solution
<div align="center">
  <a href="https://www.youtube.com/watch?v=-C6Zr5wB1rk"><img src="https://github.com/samirsaci/lss-logistic-regression/blob/main/thumbnail.webp" alt="Explainer Video Link"></a>
</div>

### Article
In this [Article](https://medium.com/towards-data-science/lean-six-sigma-with-python-logistic-regression-36d160e84548), we will implement Logistic 
Regression with Python to estimate the impact of a daily productivity bonus on your warehouse operators' picking productivity.

### Scenario
You are Reginal Director of a Logistic Company (3PL) and you have 22 warehouses in your scope.
<p align="center">
  <img align="center" src="https://miro.medium.com/max/700/1*WYwCXoRYTm48idYEIDsSwQ.png">
</p>

In each warehouse, the site manager has fixed a picking productivity target for the operators; your objective is to find the right incentive policy to reach 75% of this target.
P.S: Picking Productivity is defined by the number of cartons picked per hour paid.

### Objective: find the right incentive policy
Currently, productive operators (operators that reach their daily productivity target) receive 5 euros per day in addition to their daily salary of 64 euros (after-tax).
However, this incentive policy applied in 2 warehouses is ineffective; only 20% of the operators are reaching this target.
#### Question
What minimum daily bonus should be needed to reach 75% of the picking productivity target?
#### Experiment
Randomly select operators in your 22 warehouses
#### Implement a daily incentive amount varying between 1 to 20 euros
Check if the operators reached their target

## Code
This repository code you will find all the code used to explain the concepts presented in the article.

## About me 🤓
Senior Supply Chain and Data Science consultant with international experience working on Logistics and Transportation operations. \
For **consulting or advising** on analytics and sustainable supply chain transformation, feel free to contact me via [Logigreen Consulting](https://www.logi-green.com/). \

Please have a look at my personal blog: [Personal Website](https://samirsaci.com)
