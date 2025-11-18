| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline

Title: How Long Until Your College Degree Pays for Itself?

College is one of the biggest financial decisions young adults make, yet students often select majors or schools without understanding how long it takes for their educational investment to pay off. This project visualizes the payback period of a U.S. college degree — defined as the number of years it takes for cumulative earnings to surpass the total cost of attendance.

My goal is to help audiences such as high school students, families, and college counselors make more informed choices by showing how payback varies dramatically across majors and institutions, even when degrees cost similar amounts. This project aims to reveal where the value of college is highest, where it is lowest, and how equity factors may influence outcomes.

Hook — The Problem

College is expensive, but financial outcomes vary dramatically.
“Is college worth it?” is too vague; what matters is when it pays back.
Insight — Introducing the Payback Period

“Years until earnings recoup cost of attendance” as an intuitive measure of return.
Evidence — Visual Comparisons

Majors ranked by fastest vs slowest payback periods
School-level variation
STEM vs Business vs Arts comparison
Interpretation — Why These Patterns Occur

Wages, tuition, and living costs drive differences
Some expensive schools compensate with high earnings; others do not
Call to Action — What People Can Do

Students can weigh debt risk vs. return
Policymakers / institutions can improve transparency


## Initial sketches
> Post images of your anticipated data visualizations (sketches are fine). They should mimic aspects of your outline, and include elements of your story.  

Text here...

# The data
The data for this project comes from the U.S. Department of Education’s College Scorecard, which publishes publicly available information about college costs and post-graduation earnings. I chose this source because it provides both of the numbers needed to calculate the payback period of a college degree: the average cost of attendance and the median earnings after graduation.

I am using two datasets. The Most Recent Data by Field of Study gives median earnings 10 years after graduation for each major at each institution. The Most Recent Institution-Level Data provides the average annual cost of attendance for each school. I will combine these datasets using the shared column UNITID, and then calculate payback period as:

**Payback = Cost of Attendance / Median Earnings**

This combined dataset will allow me to compare how quickly a degree pays for itself across majors and across schools.

Public access to the data:
_
College Scorecard Data Home: https://collegescorecard.ed.gov/data/_


| Name | URL | Description |
|------|-----|-------------|
|      |     |             |
|      |     |             |
|      |     |             |

# Method and medium
I will clean and prepare the data outside of Tableau by merging the two College Scorecard datasets (Field of Study and Institution-Level) using the shared UNITID column, and then calculating the payback period from cost and earnings. I will do the cleaning in R or SQL to make sure the data is in a usable format before importing it into Tableau.

After the data is cleaned, I will build the visualizations in Tableau. The final project will be presented as an interactive web page on GitHub Pages, with the Tableau visualizations embedded so the viewer can scroll through the story and interact with the charts. My goal is to combine narrative and visual exploration so that the audience can understand the message while also exploring the data on their own.

## References
_List any references you used here._

## AI acknowledgements
_If you used AI to help you complete this assignment (within the parameters of the instruction and course guidelines), detail your use of AI for this assignment here._
