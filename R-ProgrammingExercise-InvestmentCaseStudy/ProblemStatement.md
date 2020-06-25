# Project Brief
You work for Spark Funds, **an asset management company**. Spark Funds wants to make investments in a few companies. The CEO of Spark Funds wants to understand the global trends in investments so that she can take the investment decisions effectively.

# Business and Data Understanding
Spark Funds has two minor constraints for investments:
1. It wants to invest between 5 to 15 million USD per round of investment
2. It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in
3. For your analysis, consider a country to be English speaking only if English is one of the official languages in that country
4. You may use this list: Click here for a list of countries where English is an official language.

These conditions will give you sufficient information for your initial analysis. Before getting to specific questions, let’s understand the problem and the data first.

## 1. What is the strategy?
Spark Funds wants to invest where most **other investors are investing**. This pattern is often observed among early stage startup investors.

## 2. Where did we get the data from? 
We have taken real investment data from **crunchbase.com**, so the insights you get may be incredibly useful.

### File Used:
#### 1. Company details:[companies.txt]
**companies**: A table with basic data of companies.
![](./images/companies.png)

#### 2. Funding round details:[rounds2.csv]
**rounds2**: The most important parameters are explained below:
![](./images/rounds2.png)

#### 3. Sector Classification:[mapping.csv]
This file maps the numerous **category names** in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad **sector names**. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.

#### 4. How do you approach the case study? What are the deliverables?
The entire case study is divided into checkpoints to help you navigate. For each checkpoint, you are advised to fill in the tables into the spreadsheet attached in the download segment. The tables are also mentioned under the **'Results Expected'** section after each checkpoint. Since this is the first case study, you have been provided with some additional guidance. Going forward you will be expected to structure and solve the problem by yourself, just like you would be solving problems in real life scenarios.

**Important Note:**<br /> All your code has to be submitted in one main R file. For every checkpoint, keep writing code in one well-commented R file which you can submit at the end.

Also, you have to prepare a short presentation document to present the results of your analysis to the CEO of Spark Funds. This should briefly describe the important results and recommendations. You can include the plots made in Tableau in this presentation.
