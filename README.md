# cs60050-assignment-2--naive-bayes-classifier-solved
**TO GET THIS SOLUTION VISIT:** [CS60050 Assignment 2- Naive Bayes Classifier Solved](https://www.ankitcodinghub.com/product/cs60050-assignment-2-naive-bayes-classifier-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113990&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS60050  Assignment 2- Naive Bayes Classifier Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
1 Instructions

• Use python programming language for your implementation.

• Use appropriate approach if you find some attribute is missing in your data.

• Report must contain step-wise description of your implementation and analysis of results. Since data analysis is a crucial task for any machine learning algorithm, report should demonstrate detailed analysis of results and conclusion. It should also clearly mention the steps to run your code. • Do not use any direct in-built functions of libraries to implement naive bayes classifier algorithm, otherwise -10 will be deducted.

2 Dataset

• Spooky Author Identification, https://www.kaggle.com/c/spooky-authoridentification/overview.

Each row of the dataset contains three fields: id, text and author. The task is to predict the author from the text. Download the dataset from the given link and proceed.

3 Problem statement: Naive bayes classifier

1. For your dataset, each example is a raw text. In this step, we will extractfeatures from the raw texts. You have to create an r × c binary feature matrix M where r is the number of examples and c is the size of the vocabulary consisting of distinct words present in the dataset. Each row corresponds to an example of the dataset and each column corresponds to a word in the vocabulary. Mij = 1 if and only if the j-th word is present in the text of the i example. 30

Note the following points while creating the feature matrix:

(a) Use only the train split (train.csv) of the dataset for your experiment.Which mean you have to create the feature matrix M from train.csv only.

1

(b) To read data from train.csv, you can use the python package pandas.Use the function pandas.read csv() to read the data.

(c) Since each example is a raw text, split the text into words (this stepis called tokenization). You can use the python ‘re’ package for this. Use the function re.findall(“[a-z0-9]+”, text.tolower()) to split the texts into words.

(d) Once you have splitted the texts into words, remove all the uninformative words (also referred to stopwords) like article, prepositions, verbs etc. You can find a list of stopwords at https://gist.github.com/sebleier/554280.

2. Randomly split the feature matrix into train split and test split with 7030 ratio. Train a Naive Bayes classifier on the train split. Compute and report the accuracy of the classifier on the test split. 5+10+10

3. Train a Naive Bayes classifier using Laplace correction on the same trainsplit and report the accuracy on the test split. 20+5

4. A report explaining the implementation and analysis of the results byproviding the 95% confidence interval of the accuracy, precision, f-score, sensitivity and specificity for questions 2 and 3. 20

2
