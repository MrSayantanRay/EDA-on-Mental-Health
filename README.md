# Analysis on Mental Health Trends and Patterns in Metropolitan Cities

## Objective

The objective of this project is to explore and analyze mental health data to identify patterns and relationships between key psychological factors such as depression, anxiety, and stress, along with demographic and lifestyle attributes.

---
## Acknowledgment

I would like to sincerely thank **Prof. Zakir Hussain** for his guidance and support in helping me understand the dataset, including the meaning and relevance of various features and column names used in this analysis.

## Dataset
I am using a survey-based dataset that tracks various mental health indicators. The dataset was obtained from ([Mendeley Data][1]) and has been used for analysis after appropriate preprocessing.

The dataset utilized in this project is a cleaned and transformed version of the original data source. The processed dataset has been included in the repository under the dataset section to ensure transparency and reproducibility of the analysis.

[1]:https://data.mendeley.com/datasets/45g49shf4v/1

### What's inside the data:

The dataset is a survey-based collection of responses capturing:

- **Demographics** (Age, Occupation)  
- **Economic conditions** (income changes, expenditure)  
- **COVID-related factors** (Phase 1 & Phase 2 impact)  
- **Family conditions** (children education, occupation changes, whether or not family member suffering from chronic disease)  
- **Mental health indicators** (Depression, Anxiety, Stress levels)  

This data is typically gathered using standard psychological scales (like the DASS survey), which use structured questions to measure how someone is doing ([Wikipedia][2]).

[2]: https://en.wikipedia.org/wiki/Depression_Anxiety_Stress_Scales

---

## Key Questions  

- How did economic changes during COVID affect mental health?  
- Which age group was most affected?  
- Did changes in children’s education impact mental health?  
- How did different COVID phases influence stress, anxiety, and depression?  

---

## Tools Used

To keep things simple and effective, we used:

* **Python**: The core language for our work.
* **Pandas & NumPy**: For organizing and cleaning the data.
* **Matplotlib & Seaborn**: For creating charts and graphs to make the data easier to read.

---

## Data Cleaning & Preprocessing

Before starting the analysis, we had to get the data ready:

- Handled missing values to ensure data completeness  
- Removed duplicate survey responses to maintain data integrity  
- Renamed column headers for better clarity and interpretability  
- Standardized data formats and data types for consistency  

---

## Exploratory Data Analysis

Here is how we explored the data:

- Distribution analysis of age, demographics, and mental health indicators  
- Comparative analysis across COVID phases and age groups  
- Analysis of economic status and children's education impact on mental health  
- Correlation and pattern analysis using heatmaps  
- Visualizations to identify relationships between key variables  

---

## Key Insights  

### Demographics  
- Age distribution is positively skewed (~0.5)  
- Majority of respondents fall within the 25–50 age group  

### Economic Status Impact  
- ~45% of respondents whose family business declined suffered severe depression in Phase 2  
- High anxiety levels (~44%) observed among individuals with business losses  
- Individuals with no economic change also showed notable stress levels  
- Pay cuts were associated with moderate to severe anxiety and stress  

### Expenditure Trends  
- Increase in families within lower expenditure groups (0–20k)  
- Decrease in mid-level expenditure groups (20k–40k)  
- Suggests precautionary saving behavior during COVID  

### Children’s Education (Key Finding)  
- Families where children’s education worsened showed:  
  - Higher depression levels  
  - Higher anxiety levels  
  - Higher stress levels  
- This trend was consistent across both COVID phases  

### Major Conclusion  
- Economic disruptions and education instability are key drivers of mental health issues  
- Mental health indicators (depression, anxiety, stress) are strongly interrelated  
- The status of children's education is a significant contributing factor to mental health deterioration  
---

## Conclusion
This study highlights the significant impact of COVID-19 on mental health, particularly through economic instability and disruption in children's education. The findings emphasize the importance of socio-economic stability in maintaining psychological well-being.

---

## Future Work

We have plenty of ideas for what to do next:

* Figure out which specific factors have the biggest impact.
* Find larger and more diverse datasets to improve accuracy.
* Build easy-to-use interactive dashboards (using tools like Power BI or Tableau).

---

## Project Structure  

mental-health-eda/  
│── data/  
│── images/  
│── mental-health-eda.ipynb  
│── README.md  

---

## How to Run

1. Clone this repository to your computer.
2. Open the `.ipynb` file in Jupyter Notebook or upload it to Google Colab.
3. Run the cells in order to see the results.

---

## 👤 Author

**[Sayantan Ray](https://sayantan-portfolio-sigma.vercel.app/)**

