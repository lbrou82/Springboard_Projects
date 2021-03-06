# Springboard_Projects

Included are my Springboard exercises and mini projects. 



**Data Wrangling JSON:**
1. Find the 10 countries with most projects
2. Find the top 10 major project themes (using column 'mjtheme_namecode')
3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.

**SQL Mini Project:**  

File: 1520094343_sql_project.sql  

Consists of 10 questions about a "country_club" database.     

The database contains 3 tables:  
    i) the "Bookings" table,  
    ii) the "Facilities" table, and  
    iii) the "Members" table.  

**API Mini Project:**  
  
File: api_data_wrangling_mini_project.ipynb

Consists of 7 questions based on data from the Quandl Frankfurt Stock Exchange API. 

1. Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017.
2. Convert the returned JSON object into a Python dictionary.
3. Calculate what the highest and lowest opening prices were for the stock in this period.
4. What was the largest change in any one day (based on High and Low price)?
5. What was the largest change between any two days (based on Closing Price)?
6. What was the average daily trading volume during this year?
7. (Optional) What was the median trading volume during this year.  


**Frequentist Inference Mini Projects**  
Files:inferential_statistics_1a-Q6.25.ipynb, inferential_statistics_1b-Q6.25.ipynb

*Frequentist Inference A*  
Consists of a tutorial and worked through questions introducing Frequentist Inference, including: 

- sampling and calculating probabilities from a normal distribution
- the correct way to estimate the standard deviation of a population (the population parameter) from a sample
- what a sampling distribution is and how the Central Limit Theorem applies
- how to calculate critical values and confidence intervals

*Frequentist Inference B*
Consists of a tutorial and worked through problems furthering the explanation of frequentist inference. 
It includes practice working with real world data. I answer two questions: 1) Has the hospital's revenue stream fallen below a key threshold?, and 2) Are patients with insurance really charged different amounts than those without?  

The exercises work through:
- using the central limit theorem to help you apply frequentist techniques to answer questions that pertain to very non-normally distributed data from the real world
- performing inference using such data to answer business questions
- forming a hypothesis and framing the null and alternative hypotheses
- testing this using a t-test


**Bootstrap Inference Mini Project**  
Files: inferential_statistics_2-Q.ipynb

The exercises work through: 
- calculating the same confidence interval lower limit as you did previously
- testing the assumption that the variances of the two groups (insured vs. non-insured) were equal - something a bit harder to do using the frequentist method because of the nature of the sampling distribution for variance
-calculating the p-value for the difference between the means of the two groups and compared with the result obtained using the previous frequentist approach

**Bayesian Inference Mini Project:**
File: inferential_statistics_3-Q.ipynb

This mini project uses the same dataset as the previous two (Bootstrap and Frequentist). We look at modeling individual charges as a gamma distribution and using Bayesian inference. 
