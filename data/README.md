# Data Folder  

## Description of Data Sources  
This folder contains datasets used for analyzing the relationship between academic performance and career success. The primary dataset, **Education & Career Success**, includes 5000 records of students' educational backgrounds, skills, and career outcomes. It is sourced from **Mohan S Acharya** and inspired by the **UCLA Graduate Dataset**. The dataset is designed to predict graduate admissions and career success based on factors such as GRE scores, TOEFL scores, university ratings, and research experience.  

Additionally, supplementary datasets on **Global University Rankings** and **Educational Attainment** are included to provide broader context and enhance the analysis. These datasets are sourced from **The Times Higher Education World University Ranking**, **The Academic Ranking of World Universities**, and **The World Data Bank**. Together, these datasets allow for a comprehensive exploration of how education impacts career outcomes and how global university rankings correlate with national educational attainment.  

## Data Dictionary  
Below is a structured data dictionary for the **Education & Career Success** dataset:  

| Variable Name                     | Data Type | Description                                                                 |
|------------------------------------|-----------|-----------------------------------------------------------------------------|
| GRE Scores                        | Integer   | Graduate Record Examination score (out of 340).                             |
| TOEFL Scores                      | Integer   | Test of English as a Foreign Language score (out of 120).                   |
| University Rating                 | Integer   | Rating of the university (out of 5).                                        |
| SOP Strength                      | Float     | Strength of the Statement of Purpose (out of 5).                            |
| LOR Strength                      | Float     | Strength of the Letter of Recommendation (out of 5).                        |
| Undergraduate GPA                 | Float     | Undergraduate Grade Point Average (out of 10).                              |
| Research Experience               | Binary    | Whether the student has research experience (0 = No, 1 = Yes).              |
| Chance of Admit                   | Float     | Probability of admission to a graduate program (ranging from 0 to 1).       |

For the supplementary datasets, the data dictionaries are as follows:  

### Global University Rankings  
| Variable Name                     | Data Type | Description                                                                 |
|------------------------------------|-----------|-----------------------------------------------------------------------------|
| University Name                   | String    | Name of the university.                                                     |
| Times Ranking                     | Integer   | Ranking according to The Times Higher Education World University Ranking.   |
| Shanghai Ranking                  | Integer   | Ranking according to The Academic Ranking of World Universities.            |
| CWUR Ranking                      | Integer   | Ranking according to The Center for World University Rankings.              |

### Educational Attainment  
| Variable Name                     | Data Type | Description                                                                 |
|------------------------------------|-----------|-----------------------------------------------------------------------------|
| Country                           | String    | Name of the country.                                                        |
| Educational Attainment (%)        | Float     | Percentage of the population with tertiary education.                       |
| Expenditure on Education (% GDP)  | Float     | Public and private expenditure on education as a percentage of GDP.         |

## Multiple Data Sources  
The **Education & Career Success** dataset is complemented by the **Global University Rankings** and **Educational Attainment** datasets. These supplementary datasets provide additional context for understanding the role of university reputation and national educational policies in shaping career outcomes.  

### Integration of Datasets  
1. **University Ratings and Rankings**: The university ratings in the primary dataset can be cross-referenced with global rankings to assess the impact of institutional reputation on career success.  
2. **Educational Attainment and Expenditure**: By integrating data on national educational attainment and expenditure, we can explore how broader educational policies influence individual career trajectories.  

This multi-source approach allows for a more nuanced analysis, addressing both individual and systemic factors that contribute to career success.  
