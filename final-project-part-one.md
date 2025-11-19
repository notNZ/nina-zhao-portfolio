| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline

Title: How Long Until Your College Degree Pays for Itself?

College is one of the biggest financial decisions young adults make, yet students often select majors or schools without understanding how long it takes for their educational investment to pay off. This project visualizes the payback period of a U.S. college degree — defined as the number of years it takes for cumulative earnings to surpass the total cost of attendance.

My goal is to help audiences such as high school students, families, and college counselors make more informed choices by showing how payback varies dramatically across majors and institutions, even when degrees cost similar amounts. This project aims to reveal where the value of college is highest, where it is lowest, and how equity factors may influence outcomes.

1. Hook — The Problem

College is expensive, but financial outcomes vary dramatically.
“Is college worth it?” is too vague; what matters is when it pays back.

2. Insight — Introducing the Payback Period
“Years until earnings recoup cost of attendance” as an intuitive measure of return.
Evidence — Visual Comparisons

3. Majors ranked by fastest vs slowest payback periods
School-level variation: private v. public institutions
STEM vs Business vs Arts comparison
Interpretation — Why These Patterns Occur


4. Popular/ unpopular majors' payback periods
Popular majors: CS, Engineering, Business, etc.
Unpopular majors: Anthopology, Sociology, Music performance, etc. 
   
5. Call for action
Institutions should have more transparency and post the payback period for each major/ program.
High school students can look at what major they want to study and do a comparison with other majors in terms of payback period,
thus gathering more information before deciding. 

## Initial sketches
<img width="921" height="502" alt="Screenshot 2025-11-18 at 7 56 24 PM" src="https://github.com/user-attachments/assets/dbbecb4e-b673-4f8d-9646-0ffa1ec5150b" />

<img width="784" height="565" alt="Screenshot 2025-11-18 at 8 12 01 PM" src="https://github.com/user-attachments/assets/4f143a51-31a5-4121-8f35-870bb17444d4" />

<img width="878" height="556" alt="Screenshot 2025-11-18 at 8 12 28 PM" src="https://github.com/user-attachments/assets/fc09c1f4-a9a5-4b96-a4f0-3f760fcb2633" />


# The data

| Name | URL | Description |
|------|-----|-------------|
|College Scorecard Data Home      |https://collegescorecard.ed.gov/data/     |The data for this project comes from the U.S. Department of Education’s College Scorecard, which publishes publicly available information about college costs and post-graduation earnings. I chose this source because it provides both of the numbers needed to calculate the payback period of a college degree: the average cost of attendance and the median earnings after graduation.

I am using two datasets. The Most Recent Data by Field of Study gives median earnings 10 years after graduation for each major at each institution. The Most Recent Institution-Level Data provides the average annual cost of attendance for each school. I will combine these datasets using the shared column UNITID, and then calculate payback period as:

**Payback = Cost of Attendance / Median Earnings**

This combined dataset will allow me to compare how quickly a degree pays for itself across majors and across schools.             |
|      |     |             |
|      |     |             |

# Method and medium
I will clean and prepare the data outside of Tableau by merging the two College Scorecard datasets (Field of Study and Institution-Level) using the shared UNITID column, and then calculating the payback period from cost and earnings. I will do the cleaning in R or SQL to make sure the data is in a usable format before importing it into Tableau.

After the data is cleaned, I will build the visualizations in Tableau. The final project will be presented as an interactive web page on GitHub Pages, with the Tableau visualizations embedded so the viewer can scroll through the story and interact with the charts. My goal is to combine narrative and visual exploration so that the audience can understand the message while also exploring the data on their own.

## References
 College Board data: https://collegescorecard.ed.gov/data/ 

## AI acknowledgements
I used AI to help me find relevant datasets. Prompt: "I want to explore the relationship between college major and payback periods, is there a dataset I could use?"

