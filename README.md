# Modeling Global Ecological and Socio-Economic Factors (2015-2023)

**IDS702, Fall 2024**  
**Authors**: Meron Gedrago, Xiangyu Wang, Adil Gazder, Hongyi Duan  

## Abstract

This study investigates the interconnected roles of education, income, and socioeconomic factors in shaping global carbon emissions. By analyzing comprehensive datasets from 2015-2023, we examine:  
1. The impact of compulsory education duration on carbon emissions across income groups and population sizes.  
2. The influence of life expectancy and labor force participation on income group classifications, and their indirect effects on environmental outcomes.  

Our findings highlight the importance of education and socioeconomic factors in addressing climate change and socioeconomic disparities. Key insights include the role of life expectancy and labor force ratio in income classification and the critical impact of income and population size on carbon emissions.


## Introduction

Global carbon emissions, driven by fossil fuel consumption, deforestation, and industrial activities, are the primary contributors to climate change. These emissions disproportionately impact low-income nations while high-income countries bear significant responsibility. Education plays a vital role in equipping individuals to tackle these challenges through sustainable practices and innovative solutions.

This study explores the dynamic relationships between education, income inequality, and carbon emissions, aiming to provide actionable insights for sustainable development policies.  

Key Research Questions:  
1. How do national income and population size influence carbon emissions across countries with varying compulsory education durations?  
2. How do life expectancy and labor force participation affect income group classifications, indirectly impacting carbon emissions?  


## Methods

### Data Sourcing and Preprocessing

We used datasets from the **World Development Indicators (WDI)**, the World Bank's comprehensive collection of development indicators. The analysis was limited to variables relevant to the research questions, ensuring clarity and focus.

### Key Variables
- **Carbon Emissions**: Measured in megatonnes of CO₂ equivalent from human activities.  
- **Income Group**: Categorized into four levels (Low, Lower-Middle, Upper-Middle, High) based on Gross National Income (GNI) per capita.  
- **Compulsory Education Duration**: Converted into categorical variables: Low (≤10 years) and High (>10 years).  
- **Labor Force Ratio**: Ratio of labor force to total population.  
- **National Income**: Non-inflation-adjusted GNI, accounting for fixed capital and natural resource depletion.  

### Analytical Techniques
- **Multiple Linear Regression**: To analyze the relationship between carbon emissions, education, income, and population size.  
- **Multinomial Logistic Regression**: To predict income group classifications based on life expectancy and labor force participation.  

## Results

### Research Question 1: Factors Affecting Carbon Emissions
- Carbon emissions are strongly influenced by **national income** and **population size**.  
- The relationship between income and emissions is more pronounced in countries with lower education levels.  
- **Compulsory education duration** plays a significant role in moderating the impact of income on emissions.  

Key Metrics:
- \( R^2 = 0.93 \): Indicates a strong fit for the regression model.  
- Interaction effects between education and income significantly improve model performance (\( p < 0.0001 \)).  

### Research Question 2: Factors Influencing Income Group Classification
- Life expectancy and labor force participation are critical predictors of income group classification.  
- The multinomial logistic regression achieved an accuracy of **62%**, outperforming the no-information rate (31%).  
- Challenges remain in accurately classifying lower-income groups due to class imbalances.

## Discussion

### Key Insights
- Education influences the relationship between income and carbon emissions, particularly in lower-income nations.  
- Policies targeting education reform and socioeconomic equity can simultaneously address climate change and income disparities.

### Limitations
- Imbalanced representation of income groups may impact model accuracy.  
- Further research is needed to explore additional socioeconomic and environmental variables.  

## Technologies Used
- **Programming Languages**: R  
- **Libraries and Tools**: ggplot2  
- **Data Source**: World Development Indicators (WDI)  

---
