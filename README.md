# Social Media and Mental Health Analysis

## Overview

This GitHub repository contains the code and documentation for a comprehensive analysis exploring the relationships between social media usage, demographics, and mental health. The project aims to uncover patterns and correlations within the data to better understand how social media impacts individuals' mental health, considering factors such as self-esteem, anxiety, and depression.

## Project Description

Our analysis delves into a diverse dataset encompassing multiple social media platforms and people's feelings. Leveraging advanced techniques such as data preprocessing, correlation assessments and statistical analysis, we aim to extract valuable insights and predict possible mental issues

## Research question

How does the use of social media affect individuals' mental health, including factors such as self-esteem, anxiety, and depression?

### Key Features

- **Correlation Analysis**: Explore and quantify relationships between variables, uncovering connections between social media habits, demographics, and mental health indicators.
- **Statistical Significance**: Assess the reliability of observed relationships, ensuring that correlations are not mere chance occurrences but have statistical meaning with a significance level set at alpha = 0.05.
- **Logistic Regression Model**: Employ a statistical model to analyze and predict the impact of various factors on categorical outcomes, aiding in understanding the influence of social media and demographics on mental health indicators.

## Dataset

We used a comprehensive dataset collected from a research project for the Statistics Course STA-2101 for the University of Liberal Arts Bangladesh (ULAB). Submitted by - Khan Raqib Mahmud. Submitted by - Souvik Ahmed (203014004) and Muhesena Nasiha Syeda (203014015).

Link: <https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health>

The dataset includes: timestamp, user demographic information and measurements of frequency or intensity of mental health symptoms, taken through Likert Scale questions.

### Dataset Information

- **Source**: <https://docs.google.com/spreadsheets/d/1lWFIL7h0F7xtmJHNPJX7ttPkO4v9j3xQ2E9Qb1wjek4/edit#gid=1240299773>
- **Format**: CSV
- **Size**: number of records: 481, number of columns: 21
- **Attributes**:
  - Variables:
    1. Age
    2. Gender
    3. Relationship Status
    4. Occupation Status
    5. Affiliated Organizations
    6. Social Media Used
    7. Time spent - social media use, in hours
  - Mental Health Questions:
    1. Purposeless use of Social Media [ADHD] - Question 9
    2. Distracted by Social Media [ADHD] - Question 10
    3. Restlessness if Social Media not used [Anxiety] - Question 11
    4. Easy of Distraction by Social Media [ADHD] - Question 12
    5. Bothered by worries [Anxiety] - Question 13
    6. Difficulty in concentrating [ADHD] - Question 14
    7. Comparison of self to peers [Self Esteem] - Question 15
    8. Feelings about the above comparison [Self Esteem] - Question 16
    9. Validation sought from Social Media [Self Esteem] - Question 17
    10. Feelings of Depression [Depression] - Question 18
    11. Fluctuation of interest [Depression] - Question 19
    12. Sleep Issues [Depression] - Question 20

### Data Preprocessing

Before analysis, we performed necessary preprocessing steps, including cleaning the data, handling missing values, and converting text data into a suitable format for analysis.

### Requirements

- Python >= 3.10
- Anaconda
- Jupyter Notebook
- Main Python packages employed:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scipy
  - plotly
  - scikit-learn

## How to Use

1. Clone the repository
2. Navigate to the project directory
3. Open and run the Jupyter Notebooks in a compatible environment.
4. Navigate to relevant folders for detailed findings and code used in the analysis:
    1. **01-Cleaning**: Contains a complete notebook with all data cleaning and preprocessing tasks and individual notebooks with each member's contribution. This section ensures the dataset is prepared and formatted for subsequent analyses.
    2. **02-Analysis**: Encompasses notebooks dedicated to statistical analyses, including correlation assessments and any other exploratory data analysis techniques applied to understand the relationships within the dataset. It contains a complete notebook with all analysis and individual notebooks with each member's contribution.
    3. **03-Visualisations**: Hosts notebooks focused on creating visual representations of the data. This folder includes charts, pies, and other visualizations to enhance the understanding of patterns and trends identified during the analysis phase. It contains a complete notebook with all visualisations and individual notebooks with each member's contribution.
    4. **Datasets**: Holds the raw and processed datasets used in the analysis. It ensures transparency and allows others to replicate or extend the study using the same data.
    5. **github_updater.ipynb**: A Jupyter Notebook script that automates the process of updating the GitHub repository with new files, changes, or additional content, streamlining version control.

### Members

- Giorgia Faedda [GitHub](https://github.com/fgiorgia) | [LinkedIn](https://www.linkedin.com/in/fgiorgia/)
- Hoda Nseif [GitHub](https://github.com/12345475) | [LinkedIn](https://www.linkedin.com/in/hoda-nseif-94398b201/)
- Andrea Herrera [GitHub](https://github.com/Andrea18364) | [LinkedIn](https://www.linkedin.com/in/andrea-herrera-3a027a184/)
- Raghad Al Shalati [GitHub](https://github.com/raghadalshalati) | [LinkedIn](https://www.linkedin.com/in/raghad-al-shalati-241152162/)
- Umida Rahmanova [GitHub](https://github.com/Adimu83) | [LinkedIn](https://www.linkedin.com/in/umida-rahmanova-7317752a/)

## Contributing

Contributions are welcome! If you find any issues, have suggestions, or want to expand the analysis, please create a new issue or submit a pull request.

## License

This project is licensed under the Apache License - see the [licence](./LICENSE) file for details.

---

**Note**: This project was developed as part of a final group project for [ReDI School of Digital Integration Malmö](https://www.redi-school.org/redi-school-malmo).
