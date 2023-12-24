### FINAL TERM PROJECT - DA2 CODING 1

1 The task

Analyse the children obesity phenomenon in England / Identify and evaluate possible impact and relationship of different factors with this trend. 

you need to argue why to expect a relationship between y and x.
Note that one potential result is that while we expected a link, there is no relationship between y and x - that is perfectly okay.

2 General rules

∗ Have more than 50 non-missing observations.
∗ Have at least two control variables (Z).

∗ If dataset is already analyzed from the web, come up with new individual research question.
(We will check both data and codes later on.)

Submission: You need to upload the pdf file of the jupyter notebook (knitted pdf) to BOTH Data
Analysis 2: Finding Patterns with Regressions AND to Coding 1: Data Management and Analysis with
Python ceulearning’s site.
– You must put your data and codes into your github account and take care that we can run your
code only by running the . i pynb fi l e; thus you call your data directly from your github repo.
• Submission deadline: Saturday, 23th of December 2023, 11:59 PM


3 General description

You show a compact report on an issue - which is easy to read (nicely formatted) and understand (not
using complicated technical terms or itemized steps of data analysis).
The report has a clear message - what we can learn from the data - and there is a proper argument
based on learnt statistical tools.
• You can state your research question based on your data and you can provide an answer.
You are confident in what we can learn from the data and what you cannot claim based on your
dataset.
You understand the possible challenges of your dataset and can access the uncertainties, which come
from data quality issues. These uncertainties are well articulated when conclusions are made.
You can show patterns of association between variables, you can transform these variables to handle
them in a (linear) regression model.
You understand the nature of your outcome variable and you can use proper model(s) to handle this
nature.
– Within this model you can show you have mastered what we have learnt and can use this in
analysis to make your argument more robust.
• You can show how to generalize your results and what the constraints are of this generalization.

• Formatting requirement:
– PDF knitted by markdowns in jupyter notebook.
– Length: max 4 pages of report and then appendix (which can be as long as you wish)
You should study the provided materials in detail (see the step-by-step for analysis and the example
for term project) and use them as guidelines.

4 Structure and strong recommendations

Output:
1. Introduction: introduce the problem, why interesting
2. Data: present the dataset, describe key features
3. Model:
(a) Present the model you estimate, argue for your model choice
(b) Discuss your variables, process of feature engineering. (In words, put all needed graphs,
estimation into the appendix if needed.)
(c) Show core results. Interpret what you got precisely.
4. Generalization and external validity (robustness check)
(a) Show some robustness / alternative models.
5. Causal interpretation / main summary
(a) Summarize your findings. Discuss room for a causal interpretation.
6. Conclusion
(a) Conclude and make business / policy comments / recommendations.

When writing your report, keep in mind the following:
Create rather a scientific paper or newspaper article style of report than an itemized description what
you have done.
• Pay attention to format your graphs and tables:
– Names, theme, labels, notes, ticks/values of y and x axis, etc.
– Use a unified theme and be consistent during the report using only one type.
– Regression tables - name your variables (avoid e.g. ln gdp per capita sq, rather use ln(gdpc)2).
– When reporting numbers use 2 or 3 digits.
• Never include code chunks or outputs in your report. Always use some kind of formatting.
• Think carefully about what you put into your first 4 pages. Put everything which is not essential for
understanding the main results into the appendix.
• Note: If you use weighted linear regression - there is a different interpretation than simple linear
regression.
