# Survey-Analysis

Evaluating the Effectiveness of Community Engagement Courses 

# Introduction
This project aims to explore the impact of community engagement courses on student outcomes. Utilizing pre- and post-course survey data, our analysis focuses on identifying changes in students' attitudes, knowledge, and behaviors concerning community involvement and social responsibility. This project aims not only to assess the effectiveness of these courses but also to provide actionable insights that could enhance their design and implementation.

# Data Processing
Detailed Steps:
- Cleaning: I began by removing variables that were not necessary for my analysis, such as timestamps, last names, and minors' self-described gender identities. This step ensures privacy and relevance in my dataset.
- Deduplication: I used university IDs to identify and remove duplicate entries from the pre- and post-course surveys, ensuring each student's data was unique and accurately represented.
- Standardization: Major and course names were standardized to a consistent format to avoid discrepancies in data interpretation. This also involved converting textual data into categorical factors for easier analysis.
- New Variables: I introduced a new variable to classify participants based on their campus locations (North or South), which helped in comparing regional differences in engagement levels.
- Response Adjustment: I reversed the values on a 1-5 scale for certain questions where negative results needed to be reinterpreted, enhancing the clarity and usability of the data.
- 
# Exploratory Data Analysis (EDA)
Process:
- Baseline Assessment: Initially, I conducted an exploratory analysis to identify baseline trends and distributions across different courses and demographics. This step helped in understanding the initial conditions before any interventions.
- Variable Distribution: I examined how various factors such as ethnicity, major, and enrollment distributions affected student engagement and outcomes.
- Visualization: Through charts and graphs, I visualized the distribution and frequency of data points to pinpoint patterns and outliers, which informed subsequent deeper analyses.
  
# Statistical Analysis
Techniques and Findings:
- Regression Analysis: I applied logistic regression models to analyze the significance of demographic variables and their correlation with engagement outcomes. This helped in understanding which factors most strongly predict student engagement.
- Text Mining: Utilizing text mining techniques, including sentiment analysis and latent Dirichlet allocation, I extracted themes from open-ended survey responses. This provided qualitative insights into the students' perceptions and experiences.
- Impact Measurement: The statistical analysis aimed to quantify the changes in students' knowledge, attitudes, and behaviors regarding community engagement as a result of participating in the courses.

# Limitations
This study, while comprehensive, encounters several limitations:

- Survey Bias: Inherent biases in survey responses, such as social desirability bias, may affect the authenticity of the data.
- Design Constraints: The lack of a control group and reliance on a pre-post survey design limit my ability to establish causality.
- Generalizability: My findings are specific to UCLA and may not necessarily apply to other institutions or contexts.

# Conclusion
- Key Outcomes:
My analysis revealed significant positive changes in students' engagement with community and societal issues, suggesting the courses are effective to some extent.
However, variations in engagement levels indicate opportunities to refine and improve course content, delivery, and student involvement strategies.

# Future Directions:
I recommend expanding the study to include a larger and more diverse participant base.
Future iterations should consider integrating a control group and employing a longitudinal study design to better assess the courses' impacts over time.
