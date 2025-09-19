# Student Performance Dataset Analysis

## Project Overview
This project analyzes a comprehensive dataset of student demographic attributes, parental background, study habits, and test results to uncover patterns and relationships affecting academic performance. The goal is to provide insights that can support evidence-based educational strategies.

## Dataset Description
The dataset consists of 30,641 records and 15 columns. Each record represents a student with demographic information, parental education, family context, and academic scores in math, reading, and writing.

### Columns
- Gender  
- EthnicGroup  
- ParentEduc (parental education level)  
- LunchType (standard or free/reduced)  
- TestPrep (test preparation course completion)  
- ParentMaritalStatus  
- PracticeSport (frequency of sports activity)  
- IsFirstChild  
- NrSiblings  
- TransportMeans (school_bus, private, etc.)  
- WklyStudyHours (<5, 5–10, etc.)  
- MathScore  
- ReadingScore  
- WritingScore  

## Objectives
- Perform data cleaning and preprocessing on the dataset.  
- Conduct exploratory data analysis (EDA) to identify trends and distributions.  
- Examine relationships between demographic factors and academic scores.  
- Provide actionable insights to improve student performance.  

## Key Insights (Examples)
- Test preparation completion correlates with higher scores across all subjects.  
- Students with higher weekly study hours generally perform better in math, reading, and writing.  
- Parental education and lunch type show measurable impact on academic outcomes.  
- Extracurricular activities such as regular sports practice may be associated with improved performance.  

## Technology Stack
- Python  
- Libraries: Pandas, NumPy, Matplotlib, Seaborn  

## Project Structure

```bash
├── Expanded_data_with_more_features.csv   # Dataset
├── analysis.ipynb                         # Jupyter Notebook with analysis (to be created)
├── README.md                              # Project documentation
└── requirements.txt                       # Dependencies list
````

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/student-performance-analysis.git
cd student-performance-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the analysis notebook:

```bash
jupyter notebook analysis.ipynb
```

## Future Work

* Build predictive models to forecast student scores using demographic data.
* Create dashboards for interactive exploration of the dataset.
* Explore causal relationships and interventions for student success.

Student Performance Dataset Analysis provides a comprehensive look into factors that drive academic outcomes and offers actionable insights for educational stakeholders.



