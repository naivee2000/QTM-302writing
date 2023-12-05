*Instructions: Click on the raw button in the upper right hand corner of this box.  Copy and paste the template into the README.md document on your github.  Fill in the titles, information and links where prompted! Feel free to stray a bit to suit your project but try to stick to the format as closely as possible for consistency across DSWG projects.*

# Project Name
This project is a part of the [Data Science Working Group](http://datascience.codeforsanfrancisco.org) at [Code for San Francisco](http://www.codeforsanfrancisco.org).  Other DSWG projects can be found at the [main GitHub repo](https://github.com/sfbrigade/data-science-wg).

#### -- Project Status: [Active, On-Hold, Completed]

## Project Intro/Objective

The purpose of this project is to explore and understand the complex factors influencing fertility decisions in urban households in the United States from 2018 to 2022. This study seeks to go beyond traditional models that correlate income and women's labor participation with fertility rates, by examining a broader range of socio-economic and household dynamics. By analyzing data from IPUMS-USA, the project aims to identify which factors are most influential in shaping individual fertility choices in the context of rapidly changing socio-economic landscapes. The outcomes of this research are expected to have significant implications for policy making in areas such as welfare, education, and employment, as well as for businesses in sectors like education, healthcare, and real estate. Additionally, the findings will provide individuals and families with a deeper understanding of the socio-economic factors affecting their fertility decisions, thereby aiding in more informed life choices.

### Partner
* Jenny Chao
* ran.chao@emory.edu

### Methods Used
* Data Visualization
* Predictive Modeling


### Technologies
* R Studio
* HTML


## Project Description

This project provides a detailed overview of how various socio-economic and household factors influence the number of children in a family (NCHILD) in urban households in the United States. Here's a more detailed overview:

1. **Data Sources and Variables**: Our primary data source is IPUMS-USA, focusing on urban-centric households from 2018 to 2022. Key variables include:
   - Family Income (FAMINC)
   - Adult Family Size (AFCB)
   - Education Level (EDUC)
   - Usual Hours Worked (UHRSWORKT)
   - Wage Income (INCWAGE)

2. **Hypotheses and Questions**: We are exploring how these variables correlate with NCHILD. Our hypotheses include:
   - Higher family income and wage income might correlate with fewer children.
   - Higher education levels could be associated with smaller family sizes.
   - Longer working hours might negatively impact the number of children.

3. **Data Analysis and Visualization**: We employ regression models to understand these relationships, with graphical representations to visually depict these correlations. For example, the negative coefficient for FAMINC suggests a decrease in NCHILD with increased income, though this wasn't statistically significant.

4. **Challenges and Blockers**:
   - The complexity of socio-economic factors makes isolating individual impacts on fertility decisions challenging.
   - Some relationships, like that between FAMINC and NCHILD, show trends but lack statistical significance, posing interpretative challenges.
   - The dynamic nature of socio-economic contexts might render some findings specific to the studied period, limiting generalizability.

5. **Significant Findings**:
   - The base prediction (Intercept) suggests an average of just over one and a half children per family when other factors are constant.
   - A strong positive relationship between AFCB and NCHILD indicates cultural or societal norms might favor larger families under certain conditions.
   - A negative relationship between EDUC and NCHILD, and UHRSWORKT and NCHILD, suggests higher education and longer working hours are associated with fewer children.
   - The relationship between INCWAGE and NCHILD is marginally negative, indicating nuanced socio-economic dynamics at play.

6. **Modeling Work**:
   - Regression analysis forms the core of our modeling approach, helping quantify the relationship between the dependent variable (NCHILD) and independent variables.
   - Visualizations, such as scatter plots or regression lines, aid in better understanding and communicating these relationships.

This comprehensive analysis aims to untangle the multifaceted nature of fertility decisions in contemporary urban settings, offering insights crucial for policy development, business strategy, and personal life choices.










