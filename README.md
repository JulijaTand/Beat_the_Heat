## Renewable Energy in Germany: Past, Present, Future

![nasa-Q1p7bh3SHj8-unsplash](https://github.com/JulijaTand/Beat_the_Heat/assets/91824083/13988d3c-81db-4d8d-a682-e395dd173bf8)


Germany has set ambitious energy consumption targets aimed at sustainability by 2030. The importance of these targets is 
accentuated by growing concerns over climate change and the depletion of non-renewable resources.

The goal of this project is to provide valuable insights into Germany's progress toward achieving these targets. Using datasets, 
predictive models, and machine learning techniques, we aimed to explore various hypotheses that pertain to energy consumption patterns at both 
the national and state levels.

## Team: Beat the Heat
 
- Constantine Dranganas
- Julija Tand
- Matthew Fultz
- Sara Liern


- Project presentation (https://lookerstudio.google.com/reporting/f6c338c0-acc8-4c19-a47f-9e8ec2703ace) 
​

We formulated four hypotheses to guide our research
​
- H1: 50% of German states consume renewable energy above the country's share.
- H2: The top states in terms of renewable energy consumption adopt the same energy scheme.
- H3: Energy consumption in Germany will be reduced by 30% as of 2030, compared to levels in 2008.
- H4: 42.5% of energy consumption in Germany will come from renewable sources by 2030.

## Datasets
​
​We collected data in the following categories:

- Country-Level Data

Historical energy consumption and renewable energy metrics for Germany (1965 - 2022).
[Renewable energy consumption](https://docs.google.com/spreadsheets/d/1CJnEe6bdqsaH9iIp6H6cpooaeITnq_Qa2hUYJCEzLYg/edit#gid=1799204313)

- State-Level Data

Historical renewable energy consumption per German state (1990 - 2020) https://www.lak-energiebilanzen.de/laenderbilanzen/ and (2017 - 2020) https://www.lak-energiebilanzen.de/eingabe-statisch/?a=e600


## Project Scope & Problem Definition

The scope of this project is to evaluate Germany's progress toward its 2030 energy sustainability goals by analyzing historical data on energy consumption at both the national and state levels. We aim to understand patterns and trends in energy consumption and to predict whether the 2030 targets will be achieved. The specific problems we're trying to solve are:

  - Assess the renewable energy consumption across German states.
  - Determine if there's uniformity in renewable energy schemes among top-performing states.
  - Predict the future course of energy consumption reduction and renewable energy growth in Germany.


## Data Collection

To explore our hypotheses, we gathered extensive datasets from reputable sources. 
These datasets encompass a wide range of metrics on energy consumption and renewable energy use both at the national 
and state levels in Germany. Data is sourced from official energy statistics databases and comprises historical information 
from 1965 to 2022 for country-level data, and 1990 to 2020 for state-level data.


## Data Transformation & Cleaning

The raw data came in various formats, and some data normalization was required to make it suitable for analysis. 

- We removed any duplicates or irrelevant columns.
- Merge historical energy data per German state in single CSV files.
- Standardized terminology and units across all datasets.


## Descriptive Analysis

Initial descriptive analysis was performed to understand the general trends in the datasets:

Computed summary statistics to get a sense of the distribution and variation of variables.
Identified outliers and examined their cause and significance.
Observed seasonal and yearly patterns in renewable energy consumption and overall energy use.


## Data Analysis​

Our data analysis primarily involved:

Testing the four hypotheses using statistical methods like hypothesis testing and ANOVA.
Exploring relationships between variables using correlation and regression analysis.
Identifying key drivers of renewable energy adoption and overall energy consumption reduction.



## Predictive Modelling

To predict future trends and assess the feasibility of Germany achieving its 2030 targets, we applied predictive modeling techniques.This involved training various machine learning models such as time-series forecasting and regression analysis.
The models were trained and validated using historical data to make reliable predictions about future energy consumption patterns.

- Energy reduction forecast: https://colab.research.google.com/drive/1ZZugqQRjN3wqO9UfNASmJqxiQ6AwNINH?usp=sharing
- Renewable energy increase forecast: https://colab.research.google.com/drive/13fHGJrM8W2VLQkYKSnrSlrIS5ZmRquLU?usp=sharing

  

## Data Visualization

We performed comprehensive data analysis to investigate patterns, trends, and relationships within the data.
This included using statistical tests, creating visualizations, and examining correlations among variables. 

The visualizations consisted of:

- Time-series graphs to depict historical trends.
- Bar graphs to show differences in renewable energy shemes among states and renewable energy growth.


## Key Findings
​
H1: Our analysis revealed that only 6% of German states currently consume renewable energy above the national renewable average (16,29%) of the last decade.

​

​<img width="1026" alt="Screenshot 2023-09-12 at 17 19 23" src="https://github.com/JulijaTand/Beat_the_Heat/assets/91824083/2fd793ac-fefa-4a80-8930-bf1aaeda9b85">



​​
H2: We found considerable differences in the energy schemes adopted by the top German states for renewable consumption (Bayern, 
Niedersachsen,Baden-Württemberg.​
 
​

​
<img width="913" alt="Screenshot 2023-09-12 at 17 25 14" src="https://github.com/JulijaTand/Beat_the_Heat/assets/91824083/30ecf6a9-35d3-488c-8f48-821f5609ccc8">

​
​


H3: On the current energy reduction pace of 0.88%, Germany will only meet its 30% energy reduction target by 2041. Our forecast model suggests a need for a reduction at a pace of 2.01% year over year to meet the target by 2030.

​



<img width="913" alt="Screenshot 2023-09-12 at 17 32 08" src="https://github.com/JulijaTand/Beat_the_Heat/assets/91824083/8a5214db-c372-404f-8a08-43d992236c18">

​



H4: On the current renewable growth pace of 0.22%, Germany will meet the 42.5% EU target by 2041. There is a need of an increase to a pace of 5.19% growth year over year to meet the target by 2030.

​

<img width="918" alt="Screenshot 2023-09-12 at 17 35 14" src="https://github.com/JulijaTand/Beat_the_Heat/assets/91824083/e5120c0f-ef9e-4ff2-9fbf-a5f3bd91c6cc">



## Conclusions
​
Our analyses offer clear predictions regarding the feasibility of Germany achieving its ambitious 2030 energy goals. 
The country seems to be far from reducing overall energy consumption and increasing renewable energy use, while there is a clear lack of uniformity at the state level.


Policy interventions may be required to encourage more states to adopt successful renewable energy schemes, while the country should exceed its current efforts to achieve its goals.
