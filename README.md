# mds-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [MDS Homework 2 Solved](https://www.ankitcodinghub.com/product/mds-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;91623&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MDS Homework 2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1. Stepwise Regression and Regularization- Ridge, Lasso, and Elastic Net

Data Source: a flotation plant in a mining process https://www.kaggle.com/edumagalhaes/quality-prediction-in-a-mining-process and are attached in the file MDS_Assignment2_Mining.zip.

Dataset provided by EduardoMagalhãesOliveira. Data collection methodology is shown as follows.

Hardware sensors, like temperature, pH, flow, density and all continuous process variables, where data were collected every 20s with no transformation (the dataset here shows raw data). Quality variables, like % of silica content, % of iron ore content and so on are quality measurements made by laboratory analysis. A sample of the iron ore pulp is collected in the field/shop floor, every 15 minutes. Those samples are sent to lab for analysis. So, on every two hours, lab give a feedback of quality analysis, in other words, only every two hours you have a lab/quality measurement of the product stream (iron ore concentrate), which gives you a sense of the quality of the product (iron ore pulp concentrate).

The main goal is to use this data to predict how much impurity is in the ore concentrate. As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions (empowering!). Hence, they will be able to take corrective actions in advance (reduce impurity, if it is the case) and also help the environment (reducing the amount of ore that goes to tailings as you reduce silica in the ore concentrate).

Content

The first column shows time and date range (from march of 2017 until september of 2017). Some columns were sampled every 20 second. Others were sampled on a hourly base.

The second and third columns are quality measures of the iron ore pulp right before it is fed into the flotation plant. Column 4 until column 8 are the most important variables that impact in the ore quality in the end of the process. From column 9 until column 22, we can see process data

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
National Taiwan University Manufacturing Data Science Department of Information Management Instructor: Dr. Chia-Yen Lee

(level and air flow inside the flotation columns, which also impact in ore quality. The last two columns are the final iron ore pulp quality measurement from the lab.

Target is to predict the last column, which is the % of silica in the iron ore concentrate.

Inspiration

Is it possible to predict % Silica Concentrate every minute?

How many steps (hours) ahead can we predict % Silica in Concentrate? This would help engineers to act in predictive and optimized way, mitigatin the % of iron that could have gone to tailings.

Also, for the Amina Flow, Ore Pulp Flow, and Flotation Column, etc. data are the “commas” in those cells supposed to be “decimals” as shown in the csv file. For example, given the column “% Silica Concentrate”=”1,31”, it means that the concentrate is 1.31%.

According to the description mentioned above, if the factor “% Silica Concentrate” is regarded as the response variable (y) and all factors (except the date and % Iron Concentrate) are independent variables, how to identify the importance variable which significantly affects the “% Silica Concentrate” (y)?

(a) (5%) Identify the important variable by linear regression with ordinary least squares (OLS) (i.e. ranked by p-value).

(b) (5%) Identify the important variable by stepwise regression. (hint: you can select forward selection, backward elimination, or both)

(c) (5%) Give a comparison between (a) and (b). The results are consistent?

(d) (5%) From a methodology aspect, what’s the difference between Ridge regression and Lasso? Why does Lasso support the variables selection rather than ridge? (hint: answer with

description or formulation. No computation needed.)

(e) (5%) What’s the benefit to use the Elastic Net? (hint: answer with description or

formulation. No computation needed.)

<ol start="6">
<li>(f) &nbsp;(5%) Identify the important variable by ridge regression.</li>
<li>(g) &nbsp;(5%) Identify the important variable by lasso.</li>
<li>(h) &nbsp;(5%) Identify the important variable by elastic net.</li>
<li>(i) &nbsp;(5%) Give a comparison between (f), (g) and (h). The results are consistent?</li>
<li>(j) &nbsp;(5%) What is “adaptive elastic net”? Why we need it? How to build it? Please simply
describe or formulate it. (No computation needed.)
</li>
</ol>
(k) (5%) Which columns are highly-correlated? Show the table of the coefficient estimation by

using linear regression. Any multicollinearity problem?

(l) (5%) Is it possible to predict % Silica in Concentrate without using % Iron Concentrate

column (as they are highly correlated)? Why? What’s the potential issue? How to address it?

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
National Taiwan University Manufacturing Data Science Department of Information Management Instructor: Dr. Chia-Yen Lee

2. (40%) Principal Component Analysis (PCA)- Faulty Steel Plates

Data Source: https://www.kaggle.com/uciml/faulty-steel-plates

Dataset provided by Semeion, Research Center of Sciences of Communication, Via Sersale 117, 00128, Rome, Italy. www.semeion.it

This dataset comes from research by Semeion, Research Center of Sciences of Communication. The original aim of the research was to correctly classify the type of surface defects in stainless steel plates, with six types of possible defects (plus “other”). The Input vector was made up of 27 indicators that approximately describe the geometric shape of the defect and its outline.

There are 1941 plates with 34 variables. The first 27 columns (i.e. independent variables) describe some kind of steel plate faults seen in images, i.e., X1-X27, as

{X_Minimum, X_Maximum, Y_Minimum, Y_Maximum, Pixels_Areas, X_Perimeter, Y_Perimeter

SumofLuminosity, MinimumofLuminosity, MaximumofLuminosity, LengthofConveyer, TypeOfSteel_A300, TypeOfSteel_A400, SteelPlateThickness, Edges_Index,Empty_Index, Square_Index, OutsideXIndex, EdgesXIndex, EdgesYIndex, OutsideGlobalIndex, LogOfAreas, LogXIndex, LogYIndex, Orientation_Index, Luminosity_Index, SigmoidOfAreas}

The last seven columns (i.e. dependent variables) are one hot encoded classes, i.e. if the plate fault is classified as “Stains” there will be a 1 in that column and 0’s in the other columns. {Pastry, Z_Scratch, K_Scatch, Stains, Dirtiness, Bumps, Other_Faults}

These data can be found in http://archive.ics.uci.edu/ml/datasets/steel+plates+faults, and are attached in the file MDS_Assignment2_Steelplates.xlsx.

Perform a principal component analysis (PCA) on these data.

<ol>
<li>(a) &nbsp;(10%) Use the Logistic Regression to predict the defect type “Bumps” in the testing dataset.
That is, only consider the Bumps column in the 7 defect types. What’s the accuracy and

confusion matrix?
</li>
<li>(b) &nbsp;(5%) For PCA, which variables should not be put into the PCA analysis (eg. binary
variable).
</li>
<li>(c) &nbsp;(5%) What’s eigenvalues and eigenvectors of covariance matrix in PCA? How can you
interpret from these eigenvalues?
</li>
<li>(d) &nbsp;(5%) Plot a scree plot and decide the most appropriate number of principal components
(PCs) to use.
</li>
<li>(e) &nbsp;(10%) Use the selected PCs and perform Logistic Regression to predict the defect type
“Bumps” again. What’s the accuracy and confusion matrix?
</li>
<li>(f) &nbsp;(5%) What conclusions can you draw from above analysis? Give a comparison between (a)
and (e). The results are consistent?
</li>
</ol>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Note

1. Show all your work in detail. Innovative idea is encouraged.

2. If your answer refers to any external source, please “must” give an academic citation. Any

“plagiarism” is not allowed.

</div>
</div>
</div>
