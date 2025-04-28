# cs760-homework-4-solved
**TO GET THIS SOLUTION VISIT:** [CS760 Homework 4 Solved](https://www.ankitcodinghub.com/product/cs-760-machine-learning-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117458&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS760 Homework 4 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
In this homework you will use decision trees to determine whether you would have survived the Titanic sinking, and compare your results to those obtained with logistic regression. To find out, we will use the titanic dataset (titanic_data.csv), containing the following information about 887 passengers: 1) whether they survived or not (1 = survived, 0 = deceased), 2) passenger class, 3) gender (0 = male, 1 = female), 4) age, 5) number of siblings/spouses aboard, 6) number of parents/children aboard, and 7) fare:

Passenger 1 Passenger 2 Passenger 3 ··· Passenger 887

Survived 0 1 1 ··· 0

Passenger Class 3 1 3 ··· 3

Gender 0 1 1 ··· 0

Age 22 38 26 ··· 32

Siblings/Spouses 1 1 0 ··· 0

Parents/Children 0 0 0 ··· 0

Fare 7.25 71.2833 7.925 ··· 7.75

Our goal is to construct a decision tree that determines/predicts whether an individual would survive or not. Each subproblem is worth 10 points.

Problem 4.1. To make things easier, transform each of your features into a binary variable. Describe the transformation that you will use for each feature, and explain your reasoning.

Problem 4.2. Given vectors xj,y ∈ {0,1}N containing the jth feature and the response of N i.i.d. samples, write your own code to estimate the mutual information I(xj,y). Submit your code in an appendix.

Problem 4.3. Given vectors x1,…,xD,y ∈ {0,1}N containing information about D features, and the response y of N i.i.d. samples, use your mutual information code above to write your own code to build a decision tree. Submit your code in an appendix. What stopping criteria did you use?

Problem 4.4. Use your code above to build a decision tree for the titanic dataset. Display the tree you

obtained.

Problem 4.5. Write your own code to perform 10-fold cross-validation to assess the accuracy of your tree. Submit your code in an appendix. What accuracy did you obtain?

Problem 4.6. Build your own feature vector x. According to this and your decision tree, would you have survived the Titanic sinking?

Problem 4.7. Write your own code to build a random forest with 5 decision trees, using a random subset of 80% of the samples for each tree.

(a) Display the 5 trees you obtained.

(b) Use your code above to perform 10-fold cross-validation for your random forest. What accuracy do you obtain?

4-1

Homework 4: Decision Trees 4-2

(c) According to your random forest, would you have survived the Titanic sinking?

Problem 4.8. Write your own code to build a random forest with 6 decision trees, each excluding one of the features in your dataset.

(a) Display the 6 trees you obtained.

(b) Use your code above to perform 10-fold cross-validation for your random forest. What accuracy do you obtain?

(c) According to your random forest, would you have survived the Titanic sinking?

Problem 4.9. Do all your predictions agree with each other, and with your prediction using logistic regression? Which method would you prefer to use, and why?
