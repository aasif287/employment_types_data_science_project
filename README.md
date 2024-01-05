# Types of Employment Case Study

## I. The Topic

### Employment Dynamics in the U.S.: A Comprehensive Data Analysis

The analysis focuses on understanding the evolving landscape of employment types in the United States over the past 20 years. It delves into the distinctions between full-time and part-time positions, exploring patterns, trends, and potential influences on the workforce.

---

## II. Prior Knowledge

Work-life experiences significantly impact job satisfaction, health, and career advancement. Full-time workers generally enjoy better benefits, higher wages, and greater job security, while part-time workers may experience better physical health outcomes. This study aims to build upon existing knowledge, investigating how these factors have evolved over time.

---

## III. Hypotheses

### Key Research Questions:
1. How have full-time, part-time, temporary, and contract positions evolved over time and across industries in the United States?
2. What policies and tactics ensure part-time workers have equal access to perks and job security, and how can these be applied across different business sectors?
3. How have new technologies influenced the job market in different sectors, impacting job security and future career opportunities?

Additional Questions:
- Which employment type has experienced the most significant growth in the past 20 years, and does it align with professional and economic circumstances?
- Which employment type has seen the least growth in the past 20 years, and what factors contribute to this?

Hypothesis: Patterns will emerge between employment types based on the progression of fields creating job opportunities.

---

## IV. Data

### Planned Data:
Data sourced from the Bureau of Labor Statistics, covering the number of full-time and part-time workers monthly for the past 20 years.

### Explored Data:
Explored data matches the planned data, offering filtering opportunities based on age, regions, and excluding contract workers.

### Collected Data:
Data collected from statistical surveys reflecting the current U.S. population. Structured in Excel tables, separated for Full-Time and Part-Time Employees, with years and months as rows and columns.

**Note:** The data for full-time and part-time workers is available in the following files:
- `fulltime.csv`
- `partime.csv`
  
---

## V. Preparing The Data

1. **Clean-Up:**
   - Removed headers from downloaded Excel files.
   - Shifted cells for improved visual clarity.

2. **Conversion:**
   - Converted the cleaned Excel file to a CSV format for analysis in R Studio.

---

## VI. Analysis

### Plots Used:
1. **Bar Plots:**
   - Visualized the yearly count of full-time and part-time workers to highlight numerical differences.
   
2. **Line Plot:**
   - Tracked changes in the number of workers over time, revealing peaks and drops influenced by external factors.
   
3. **Descriptive Statistics:**
   - Calculated monthly means, identifying years and months with the highest and lowest number of workers for both full-time and part-time categories.

### Code Documentation:
The code for creating the plots is available in the document:
- `DSproject.docx`

### Insights:
- Both full-time and part-time workers exhibit similar patterns of increasing and decreasing employment during specific years, indicating external influences.
- Descriptive statistics reveal trends in employment peaks and troughs, providing insights into the dynamics of the job market.
  
![image](https://github.com/aasif287/employment_types_data_science_project/assets/155476415/40778d55-187b-4960-bd8e-0c91bd9bd72d)

![image](https://github.com/aasif287/employment_types_data_science_project/assets/155476415/5476a480-0613-4cef-b843-772ceb5bf277)

This graphic helps us understand that full-time and part-time workers follow the same pattern of increasing and decreasing employment during specific years, even though the number of workers varies based on employment status. This can indicate that external influences on the job market create a demand or reduced need for these people. 

![image](https://github.com/aasif287/employment_types_data_science_project/assets/155476415/218ae57e-61b7-4df2-9907-ac3c39ea0f11)

![image](https://github.com/aasif287/employment_types_data_science_project/assets/155476415/2f1017a8-4ba4-4b5d-a16b-67ba4457bf27)

These descriptive statistics give information in the data set that highlights the lowest and highest points of the data, representing the year the most workers were working when. From this analysis, we see that both full-time and part-time workers have had the highest number of workers in the same month, which is in February. Similarly, we know they also had the lowest employment in January. Based on this collected information, these months have occurrences that explain the increases and decreases in employment. In January, career demand is low due to the new year starting, and companies analyze the assets of their workers and may potentially lay off workers then. Then in February, individuals are getting rehired, explaining the spike in employment for both types. 

![image](https://github.com/aasif287/employment_types_data_science_project/assets/155476415/d1c9d223-c0f1-441c-8041-23a7ee7e7c07)

The visual above depicts the part-time workers in red while the full-time workers are in green. Noticeably, many characteristics of this graph explain patterns and differences that affect full-time and pattern work. Overall, there is a general increase in the number of workers regardless of employment type. From 2000 to 2007, both employment types followed a similar track pattern where the number of jobs increased. Then around 2008, the number of full-time workers significantly decreased, which can be explained by the 2008 recession and why many potential full-time workers were laid off. After the end of that, in 2010, full-time work resumed gaining increasing numbers, why part-time jobs had very little growth in terms of numbers and remained somewhat stagnant. Then around 2019-2020, COVID Virus hit the United States, and the impact was primarily seen in the number of part-time workers, where there was a drastic drop, but contrastingly full-time workers were at a peak. This may be because part-time workers were primarily a part of retail, and it wasn't considered essential, so they were laid off. But full-time workers were still needed for business functions, and their work was accessible to be transitioned online. And based on the y-axis scale, there are three times more the number of full-time workers than there is of part-time workers. 


---

## VII. Conclusion and Further Directions

### Findings:
- Full-time and part-time employment patterns reveal shared economic, social, and environmental impacts.
- Recommendations include applying for jobs in February, the month with the highest employment rates.

### Further Directions:
1. **Industry-Specific Analysis:**
   - Explore employment trends in specific sectors like life sciences, engineering, and business.

2. **Social and Economic Inequality:**
   - Investigate the impact of part-time work on social and economic inequality, focusing on gender and industry differences.

---

## VIII. References

1. Thorsteinson, T. (2003). *Job Attitudes of Part-time vs. Full-time Workers: A Meta-analytic Review.*
2. U.S. Department of Justice, Bureau of Justice Statistics. (1987-1990). *BJS data report.*
3. Waltower, S. (n.d.). *Full-time vs part-time employees: What's the difference?* Business News Daily.

---

Feel free to reach out for any clarifications or additional information. Happy analyzing!
