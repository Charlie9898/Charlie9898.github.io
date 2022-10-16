**For your blog post, write up the strategy you use for EDA.**   
When I obtain the data, the first thing is always to identify the background of the data. For example, is the data from a questionnaire survey/experimental design? Then I will have a rough idea about the variable types and potential approaches to analyze them. Next, I will clean up the dataset, keep the variables I am interested in, check the missing values, and label the variable clearly (eg, remove the space in variable names for a better programming experience). And then, some basic plots/tables, such as frequency tables, contingency tables, histograms, scatter plots, etc. are essential to obtain a rough idea about the data distribution and range. After examining the distribution of single variables, paired plots/ correlation plots are applied to investigate the cross-variable relationships. Some statistical tests are also useful to identify their relationship numerically. By applying these approaches, I will then choose the optimal methods/models to analyze the data further.  
  
  
**What is your overall goal when doing an EDA?**   
The overall goal is to help look at data before making any assumptions. It is often used to see what the data can tell us beyond formal modeling, thereby contrasting traditional hypothesis testing. In addition, it is also helpful for us in selecting the proper statistical analysis approaches to go deeper into the data. EDA can also be valuable for us to avoid violating some basic assumptions before applying the corresponding models.  
  
  
**What methods do you think are important?**   
Whether a method is important depends on the data we are focusing on. For example, if we are analyzing a company's stock price over a year, basic time series analysis can be crucial. However, if the data is from a two-treatment experimental design, time-series related analysis may not be necessary.
However, overall, I think some methods are quite important for most data. The test for normality (eg, Shapiro Wilk test, QQ plot, etc.) is an example. Since it is quite common for us to start from a simple linear model, normality is a very common basic assumption for extensive statistic models. Second, paired plots are also important for identifying the correlation among variable pairs. In addition, line plots can be helpful in detecting any longitudinal pattern. The outlier test can be essential to detect any abnormality in the data.  
  
  
**What things do you try to look for?**   
1. How many variables/samples do we have in the data?
2. What are the types of these variables (numeric, ordinal, categorical)?
3. Are there any missing values?
4. What is the rough distribution of these variables?
5. Are they mutually independent/correlated?
6. Are there any outliers in the data?
7. By answering the questions above, I may try to figure out what statistical models/approaches can be best suitable for the data to conduct deeper analysis.
