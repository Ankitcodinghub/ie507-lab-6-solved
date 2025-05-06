# ie507-lab-6-solved
**TO GET THIS SOLUTION VISIT:** [IE507 Lab 6 Solved](https://www.ankitcodinghub.com/product/ie507-lab-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97675&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE507 Lab 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Instructions:

We will practice modeling non-linear optimization problems as linear programs in this lab. We will continue to model problems by loading information from files in this lab.

Please follow the instructions given below:

<ul>
<li>Please use different notebooks for solving different problems.</li>
<li>The notebook name for Exercise 1 should be YOURROLLNUMBER IE507 Lab6 Ex1.ipynb.</li>
<li>Similarly, the notebook name for Exercise 2 should be YOURROLLNUMBER IE507 Lab6 Ex2.ipynb,
etc.
</li>
<li>Please post your doubts in MS Teams or Moodle so that TAs can clarify.
For more details on pyomo, please consult https://pyomo.readthedocs.io/en/stable/index. html.

There are only 3 exercises in this lab. Try to solve all problems on your own. If you have difficulties, ask the Instructors or TAs.

Only the questions marked [R] need to be answered in the notebook. You can either print the answers using print command in your code or you can write the text in a separate text tab. To add text in your notebook, click +Text. Some questions require you to provide proper explanations; for such questions, write proper explanations in a text tab.

After completing this lab’s exercises, click File → Download .ipynb and save your files to your local laptop/desktop. Create a folder with name YOURROLLNUMBER IE507 Lab5 and copy your .ipynb files to the folder. Also copy the .csv files to the folder. Some questions require the appropriate files to be included in folder. Please include all related files required to execute your code in the folder. Then zip the folder to create YOURROLLNUMBER IE507 Lab5.zip. Then upload only the .zip file to Moodle.

The deadline for today’s lab submission is tomorrow, 24th September 2020, 11 59 PM Indian Standard Time (IST).
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 06 23-September-2020

Exercise 1: Objective function with absolute value function [15 marks]

Consider the optimization problem (OP) considered in the practice code and its equivalent linear program problems (OP1) and (OP2).

<ol>
<li>Use cbc solver to solve optimization problem (OP1).</li>
<li>[R] Report the solver status and solver termination condition. Does the solver yield an optimal solution? If not, illustrate the reason for non-optimality and devise appropriate remedies so that you get optimal solution values. Explain the remedy measures you used.</li>
<li>[R] If the solver results in optimal solution, report the optimal objective function value, values of the decision variables xi and the new variables ui and the constraint activities at the optimal solution. List your observations about the optimal values of original decision variables xi and the new decision variables ui.</li>
<li>Now consider the optimization problem (OP2). Create a file containing the coefficients of ob- jective function and constraints in problem (OP2). Name the file as lab6 practice coef OP2.txt</li>
<li>Copy the file to colab environment.</li>
<li>Use numpy to load the .txt file contents.</li>
<li>Write a pyomo model to solve problem (OP2).</li>
<li>Use cbc solver to solve the model for optimization problem (OP2).</li>
<li>[R] Report the solver status and solver termination condition. Does the solver yield an optimal solution? If not, illustrate the reasons for non-optimality and devise appropriate remedies so that you get optimal solution values. Explain the remedy measures you used.</li>
<li>[R] If the solver results in optimal solution, report the optimal objective function value, values of the decision variables ai and bi, and the constraint activities at the optimal solution.</li>
<li>[R] Write code to print the original variables xi from ai and bi and print the values of xi.</li>
<li>[R] Compare the xi values obtained from solving problem (OP1) and problem (OP2). Com- ment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 06 23-September-2020

Exercise 2: An optimization problem with non-linear absolute value function in the constraints [20 Marks]

Recall the advertisement problem considered in practice session of Lab 4. We considered the optimization problem:

</div>
</div>
<div class="layoutArea">
<div class="column">
max 35×1 + 57×2 + 48×3 + 20×4 + 15×5, s.t.x1 +x2 +x3 x3 +x4 +x5 x1 + x2 30000×1 + 95000×2 + 10000×3 + 5000×4 + 4000×5 100000×1 + 500000×2 + 200000×3 + 45000×4 + 25000×5

</div>
<div class="column">
≤75, ≤100,

≥ 10,

≤ 1500000, ≥ 900000,

</div>
</div>
<div class="layoutArea">
<div class="column">
xi ≥ 0, i ∈ {1,2,3,4,5}. (OPT-ADV)

where x1,x2,x3,x4,x5 denote the number of different types of media slots (assumed to be non- negative integers) to be used for advertisement, where x1 corresponds to website, x2 corresponds to TV, x3 corresponds to daily newspaper, x4 corresponds to weekly magazine and x5 corresponds to monthly magazine.

<ol>
<li>[R] Let z1 denote the total number of media slots used for website and TV and let z2 de- note the total number of media slots used for other mediums. We wish to introduce a new constraint into problem (OPT-ADV) where the absolute value of difference between z1 and z2 cannot exceed 18. Write the formulation obtained by introducing this new constraint into the optimization problem (OPT-ADV). Note that your formulation should not contain z1 and z2 and should be in terms of the original decision variables x1,…,x5. Is the resultant formulation a linear program? Why or why not? Explain with appropriate reasons.</li>
<li>[R] If the resultant optimization problem is not a linear program, use Approach 1 and Ap- proach 2 discussed in Lab 6 practice session to convert it to respective linear programs and write the new formulations.</li>
<li>Use the code used in Lab 4 practice session and modify it so that you can solve the new linear programs resulting from Approach 1 and Approach 2.</li>
<li>[R] Solve the respective linear programs obtained from Approach 1 and Approach 2 and report the solver status and termination conditions. Are you getting optimal solutions in each case? If not, illustrate the reasons for non-optimality and devise appropriate remedies so that you get optimal solution values. Explain the remedy measures you used.</li>
<li>[R] For each of the respective linear programs obtained from Approach 1 and Approach 2, report the optimal objective function values, optimal values of the original decision variables and the new decision variables and the constraint activities in each case.</li>
<li>[R] Report your observations on the optimal values of the original decision variables obtained using Approach 1 and Approach 2.</li>
<li>[R] Suppose we wish to introduce a different new constraint to the optimization problem (OPT-ADV). Let z3 denote the total number of media slots allotted for weekly and monthly magazines. Suppose we want the absolute value of difference between z3 and x3 (recall x3 corresponds to the number of media slots used for newspapers) must be at least 4. Write the formulation obtained by introducing this new constraint into the optimization problem (OPT-ADV). Note that your formulation should not contain z3 and should be in terms of the original decision variables x1 , . . . , x5 . Is the resultant formulation a linear program? Why or why not? Explain with appropriate reasons. Illustrate how you will convert this new formulation into a linear program.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 06 23-September-2020

Exercise 3: Fitting data using a linear model. (Adapted from Bradley, Hax, and Magnanti, Addison-Wesley, 1977) [15 Marks]

The selling prices of a number of warehouses in Powai overlooking the lake are given in the following table, along with the size of the lot and its elevation.

</div>
</div>
<div class="layoutArea">
<div class="column">
Warehouse Selling price

i Pi

</div>
<div class="column">
Lot size (sq. ft.)

Li 1800 2800 3500 800 700 500

</div>
<div class="column">
Elevation (feet)

Ei 250 400 450 100 200 50

</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6

Table 1: Selling

</div>
<div class="column">
<pre>175000
150000
125000
</pre>
90000

80000 120000

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰂

</div>
</div>
<div class="layoutArea">
<div class="column">
􏰂

</div>
</div>
<div class="layoutArea">
<div class="column">
of the residuals Ri = Pi − Pi.

In this lab, we will solve this problem for 6 data points in Table 1.

</div>
</div>
<div class="layoutArea">
<div class="column">
prices for different lot sizes and elevations

</div>
</div>
<div class="layoutArea">
<div class="column">
You have been asked by Marol Warehousing Company to construct a model to forecast the selling prices of other warehouses in Powai from their lot sizes and elevations. The company feels that a linear model of the form P = b0 + b1L + b2E would be reasonably accurate and easy to use. Here b1 and b2 would indicate how the price varies with lot size and elevation, respectively, while b0 would reflect a base price for this section of the city. You would like to select the best linear model in some sense. If you knew the three parameters b0,b1 and b2, the six observations in the table would each provide a forecast of the selling price as follows:

Pi =b0 +b1Li +b2Ei i=1,2,…,6.

However, since b0,b1 and b2 cannot, in general, be chosen so that the actual prices Pi are exactly

</div>
</div>
<div class="layoutArea">
<div class="column">
equal to the forecast prices Pi for all observations, you would like to minimize the absolute value 􏰂

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>[R] Write a general optimization problem using the actual objective provided in the descrip- tion. You may assume that b0 ≥ 0 and b1, b2 do not have bounds on them. Is the optimization problem linear? Explain.</li>
<li>Use Approach 1 and Approch 2 described in Lab 6 practice to convert the optimization problem into respective linear programs.</li>
<li>Create an appropriate .csv file from Table 1, which you can use during the construction of the objective function and the constraints for both approaches.</li>
<li>Construct pyomo models for the respective linear programs resulting from Approach 1 and Approach 2.</li>
<li>[R] Solve the respective linear programs obtained from Approach 1 and Approach 2 using cbc solver, report the solver status, solver termination conditions, optimal solution values for the original and new decision variables, and the optimal sum of residuals. Comment on your observations.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
