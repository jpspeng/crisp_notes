# Welcome to the CRISP R notes page

These are basic R tutorials and exercises for getting started with R programming, created for [Clinical Research Intensive Summer Program](https://www.iths.org/education/professional-development/crisp/) (CRISP) through UW ITHS.

## Course goals 

By the end of the course, you will be able to: 
* Read in a dataset into R 
* Learn about basic syntax in R (objects, functions, etc.) 
* Perform basic data processing and manipulation
* Create basic data summaries and create a “Table 1”
* Perform linear and logistic regression
* Create plots with the `ggplot2` package
* Other potential topics: survival analysis using Cox regression, using AI tools for coding

The goal of this course is to get a taste for how to code in R; it is not meant to be comprehensive! 

## Data 

We will be using the following sample data in our tutorials: 
[CSV file](https://jpspeng.github.io/crisp_notes/pages/crisp-2024-sample100.csv) / [data documentation](https://jpspeng.github.io/crisp_notes/pages/Crisp-2024-sample100-dictionary.pdf). 

Here is the CRISP survey data (version 2): [CSV file](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_survey_data_v2.csv) / [data documentation](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_survey_data_documentation.md)

## Lessons 

| Day | Topic | Powerpoint | Notes and Exercises | R Markdown |
|----------|----------|----------| ----------| ----------|
| Day 1 (7/6/26) | Getting started with R ([Recording](https://washington.zoom.us/rec/share/Ugr5og7I6w8xhjdoXQxA7CJn_efZWCRsCRa0H3lc4mxLYqSfgmH3ABlVhvfzbtA6.r3AoM6Wny_HGL8qp?startTime=1783366528000) - sorry no sound!)   | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day1.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day1.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day1.Rmd) / [Solutions](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day1_answers.Rmd)  |
| Day 2 (7/8/26) | Basic R syntax ([Recording](https://washington.zoom.us/rec/share/jnRIEy_YfAdLkhKR02BDu_k_m-5HYCxls8FQyVnhDQpqZbwLlGRA5bPUMr1ZsMx4.DpCN5uph2PqaIjmZ?startTime=1783539600000)) | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day2.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day2.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day2.Rmd) / [Solutions](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day2_answers.Rmd)  |
| Day 3 (7/10/26) | Data processing and manipulation ([Recording](https://washington.zoom.us/rec/play/YtsWjOT70QxJLjjiLPdtDV8orHvbx-q54SEv82u50HuGYIrjcUiqjcNODK_JT-ScJnvSqRA99KAer2r0.Xjgwk_FDlvF1z1SH?accessLevel=meeting&canPlayFromShare=true&from=my_recording&continueMode=true&oldStyle=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fwashington.zoom.us%2Frec%2Fshare%2FcyCTpOQPT7h_Ql-wFxR_LWNIBUW8hASui2yY5bzAZYIh6aqvrTN8zwA9DT9-FWR0.91QAze54SnZnoqg0)) | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day3.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day3.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day3.Rmd)  |
| Day 4 (7/13/26) | Using dplyr and table1 ([Recording](https://washington.zoom.us/rec/share/VetAtbK7FFy107VVT-ML0jPo2wX9ZoGUldGDtI18lnJK9cHmy7dfzLz7ZxxKY2-r.ZhdExQG_Qhzn9fmo)) | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day4.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day4.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day4.Rmd)  |
| Day 5 (7/15/26) | Creating Table 1 and hypothesis testing ([Recording](https://washington.zoom.us/rec/play/2OfZ-S8QFUu8PvM3hmEJzmloE3Vl94p7GFVPDDfxZ0pBGaDW0W8yg2ZbSV4XJkmfTbwmiRC2-PFBgvHF.meEhOwY3mfql-2iA?accessLevel=meeting&canPlayFromShare=true&from=my_recording&startTime=1784144402000&oldStyle=true&componentName=rec-play&originRequestUrl=https%3A%2F%2Fwashington.zoom.us%2Frec%2Fshare%2FI2nnRCPUPB6jofLg8LyTMJ2yYU5mK3hkDrcoZGd42qeyIRpsTny9-ZCtjII6Ixg.cmyvbGiDQm4BDuGq%3FstartTime%3D1784144402000)) | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day5.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day5.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day5.Rmd)  |
| Day 6 (7/17/26) | Linear regression ([Recording](https://urldefense.com/v3/__https://washington.zoom.us/rec/share/6-xvfdCy-4kCgIN2aimBOV0TWO_TlpUkzNIFfPua7WqdFWUeGwMJZs-8LfjwmrRq.neQxt5R4UUFOqYxE__;!!K-Hz7m0Vt54!kK_yBVDrYwRJ0LeqHsflfoBlunl7B_aRoqRCi6k_Is2oBj3G51BnMVcZfXyOm1nt_Ta9BnsIccJ-CpwS$)) | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day6.pptx) / [Annotated PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day6_annotated.pdf)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day6.html) (Updated with code/interpretation for categorical variables)    | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day6.Rmd)  |
| Day 7 (7/20/26) | Logistic regression | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2026/crisp_2026_R_day7.pptx)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day7.html)    | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_day7.Rmd)  |




## Homeworks

Homeworks for this course are optional but encouraged! You can turn in homework by emailing me at jpspeng@uw.edu, and I will aim to provide feedback to you by the following Wednesday.  

1. *Homework 1*: due Monday, July 13 ([HTML](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_homework1.html) / [Rmd](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_homework1.Rmd) / [CSV used in the homework](https://jpspeng.github.io/crisp_notes/notebooks_2026/hw1_fake_data.csv) ) / [Homework 1 solutions](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_homework1_solutions.Rmd)
2. *Homework 2 (midterm)*: due Friday, July 17 ([HTML](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_homework2.html) / [Rmd](https://jpspeng.github.io/crisp_notes/notebooks_2026/crisp_2026_homework2.Rmd) / [CSV used in the homework](https://jpspeng.github.io/crisp_notes/notebooks_2025/midterm_practicum_sample.csv) ) 
3. *Homework 3 (final)*: due Thursday, July 23 (to be posted by 5 pm, July 20) 

--- 
--- 

## Old Courses 

Here are the files from the CRISP 2025 course.

### 2025

#### Lessons 

| Day | Topic | Powerpoint | Notes and Exercises | R Markdown |
|----------|----------|----------| ----------| ----------|
| Day 1 (7/7) | Getting started with R   | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day1.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day1.html)     | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day1.Rmd)  |
| Day 2 (7/9)    | Basic syntax     | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day2.pptx)     | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day2.html)   | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day2.Rmd)   |
| Day 3 (7/11)    | Data processing and manipulation    | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day3.pptx)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day3.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day3.Rmd)    |
| Day 4 (7/14)    | Using dplyr and table1   | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day4.pptx)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day4.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day4.Rmd)    |
| Day 5 (7/16)    | Factor variables and hypothesis testing  | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day5.pptx)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day5.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day5.Rmd) / [Midterm CSV](https://jpspeng.github.io/crisp_notes/notebooks_2025/midterm_practicum_sample.csv)  |
| Day 6 (7/18)    | Linear regression | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day6.pptx) / [Annotated Notes](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day6_annotated.pdf)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day6.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day6.Rmd)   |
| Day 7 (7/21)    | Logistic regression | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day7.pptx) / [Annotated Notes](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day7_annotated.pdf)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day7.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day7.Rmd)   |
| Day 8 (7/21)    | Plotting with ggplot2 | [PPTX](https://jpspeng.github.io/crisp_notes/powerpoints_2025/crisp_2025_R_day8.pptx)    | [Notes and exercises](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day8.html)      | [RMD](https://jpspeng.github.io/crisp_notes/notebooks_2025/crisp_2025_day8.Rmd) / [Demo CSV](https://jpspeng.github.io/crisp_notes/notebooks_2025/chatgpt_demo.csv)   |

#### Extra Lessons 

We won't have time to cover everything in this mini-course. Here are some additional guides to help you with R: 

| Topic | Notes and Exercises | R Markdown |
|----------| ----------| ----------|
| Lists | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/lists.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/lists.Rmd)|
| Loops | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/loops.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/loops.Rmd)|
| Functions | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/functions.html) | [RMD](https://jpspeng.github.io/crisp_notes/pages/functions.Rmd)|
| Risk differences, risk ratios, and odds ratios | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/risk_differences.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/risk_differences.Rmd)|
| Interaction terms in linear regression | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/interaction_term.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/interaction_term.Rmd)|
| Survival analysis basics | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/survival_analysis.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/survival_analysis.Rmd)|
| Cox regression | [Notes and exercises](https://jpspeng.github.io/crisp_notes/pages/cox_regression.html)| [RMD](https://jpspeng.github.io/crisp_notes/pages/cox_regression.Rmd)|


--- 

### 2024 

Here are the files from the CRISP 2024 course.

#### Data 

We will be using the following sample data in our tutorials: 
[CSV file](https://jpspeng.github.io/crisp_notes/pages/crisp-2024-sample100.csv) 

Here is the [data documentation](https://jpspeng.github.io/crisp_notes/pages/Crisp-2024-sample100-dictionary.pdf). 

#### Mini-Lessons 

1. [Installing R and R Studio](https://jpspeng.github.io/crisp_notes/pages/installing_R.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/installing_R.Rmd))
2. [Using R Studio](https://jpspeng.github.io/crisp_notes/pages/r_studio_r_markdown.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/r_studio_r_markdown.Rmd))
3. [Installing and using packages](https://jpspeng.github.io/crisp_notes/pages/installing_packages.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/installing_packages.Rmd))
4. [Basic language and operations in R](https://jpspeng.github.io/crisp_notes/pages/some_language.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/some_language.Rmd))
5. [Read in data](https://jpspeng.github.io/crisp_notes/pages/reading_data.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/reading_data.Rmd))
6. [Dataframe operations and subsetting data (using the `dplyr` package)](https://jpspeng.github.io/crisp_notes/pages/subsetting_data.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/subsetting_data.Rmd))
7. [Factor variables](https://jpspeng.github.io/crisp_notes/pages/factor_variables.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/factor_variables.Rmd))
8. [Simple comparison of means / proportions hypothesis tests](https://jpspeng.github.io/crisp_notes/pages/tests_comparing_means_proportions.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/tests_comparing_means_proportions.Rmd))
9. [Exercise: Create a Table 1](https://jpspeng.github.io/crisp_notes/pages/creating_table1.html)
10. [Using the table1 package](https://jpspeng.github.io/crisp_notes/pages/using_table1_package.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/using_table1_package.Rmd))
11. [Risk differences, risk ratios, odds ratios](https://jpspeng.github.io/crisp_notes/pages/risk_differences.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/risk_differences.Rmd))
12. [Graphing with ggplot2](https://jpspeng.github.io/crisp_notes/pages/graphing_with_ggplot2.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/graphing_with_ggplot2.Rmd))
13. [Linear regression](https://jpspeng.github.io/crisp_notes/pages/linear_regression.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/linear_regression.Rmd))
14. [More linear regression](https://jpspeng.github.io/crisp_notes/pages/more_linear_regression.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/more_linear_regression.Rmd))
15. [Interaction models](https://jpspeng.github.io/crisp_notes/pages/interaction_term.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/interaction_term.Rmd))
16. [Logistic regression](https://jpspeng.github.io/crisp_notes/pages/logistic_regression.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/logistic_regression.Rmd))
17. [Survival analysis basics](https://jpspeng.github.io/crisp_notes/pages/survival_analysis.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/survival_analysis.Rmd))
18. [Cox regression example](https://jpspeng.github.io/crisp_notes/pages/cox_regression.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/cox_regression.Rmd))

### More advanced coding (optional)

1.  [Lists](https://jpspeng.github.io/crisp_notes/pages/lists.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/lists.Rmd))
2.  [Loops](https://jpspeng.github.io/crisp_notes/pages/loops.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/loops.Rmd))
3.  [Functions](https://jpspeng.github.io/crisp_notes/pages/functions.html) ([Download RMD](https://jpspeng.github.io/crisp_notes/pages/functions.Rmd))
