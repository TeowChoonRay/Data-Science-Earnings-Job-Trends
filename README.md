# Data Science Salaries: Designations, Experience and Company Factors in the Industry 🧑‍💻👩‍💻

<p align="center">
  <img src="data-science.jpg" alt="Data Science">
</p>

## Abstract
As data-driven roles continue to gain popularity in this digital economy, understanding the trends in job salary across Data Science professions has become a topic of interest for many job seekers and employers. Data Science professionals contribute to a wide range of industries while holding diverse roles that vary in experience level and work arrangements. As such, a significant gap in earnings can be observed between professionals in this field and industry. This project aims to explore the relationship between data science salaries and its associated factors. Through basic data analysis techniques, the findings will provide valuable insights to both data science professionals and their employers in understanding expected salary outcomes and future career progression plans.

## Table of Contents
1. [Collaborators](#collaborators)
2. [Introduction](#introduction)
3. [Conclusion](#conclusion)
4. [Future Developments](#future-developments)

## Collaborators

Submitted for MH3511 Data Analysis with Computer (Team 45):

| Name | GitHub | LinkedIn |
|------|--------|----------|
| Nicole Ang | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nicoleang18) | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicoleang18/) |
| Teow Choon Ray | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TeowChoonRay) | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/choonray/) |
| Chloe Yeo | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/itschloechloe) | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chloeyeo-yangenxi/)|
| Clarabelle Chua | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/clarabelle04) | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/clarabelle-chua-147547317/) |
| Zhang Yiping | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yiping1708) | [![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yiping-zhang-ntu/) |

## Introduction
In our project, a dataset containing Salary_In_Rupees of 607 Data Science professionals is used, with other variables such as Designation, Experience, and Company_Location. Based on this dataset, we seek to explore the following statistical relationships, focusing specifically on the variable Salary_In_SGD (Converted from Salary_In_Rupees) in the Data Science field:
- [Data Cleaning and Exploratory Data Analysis](https://github.com/TeowChoonRay/Data-Science-Earnings-Job-Trends/blob/main/DataCleaning%20and%20EDA.Rmd)
- [Relation between Designation and Salary_In_SGD (Factoring in Experience)](https://github.com/TeowChoonRay/Data-Science-Earnings-Job-Trends/blob/main/Designation%20v%20Salary.Rmd)
- Relation between Company_Location and Salary_In_SGD
- Relation between Working Year and Salary_In_SGD
- [Relation between Remote_Working_Ratio and Salary_In_SGD](https://github.com/TeowChoonRay/Data-Science-Earnings-Job-Trends/blob/main/Remote%20Working%20Ratio%20v%20Salary.Rmd)
- [Relation between All Categorical Variables and Salary_In_SGD](https://github.com/TeowChoonRay/Data-Science-Earnings-Job-Trends/blob/main/Influence%20of%20All%20Categorical%20Variables.Rmd)

## Conclusion
In this report, we attempt to answer some of the basic questions related to salaries in the Data Science Industry, relating to working years 2020 to 2022

We conclude that:
Designation alone does not significantly impact salary (likely due to uncontrolled variation in experience levels within each job role), while Experience has a highly significant effect on salary
Company_Location has the strongest influence on salary, where US salaries significantly outpace GB salaries and India has significantly lower salaries compared to Germany, France, and Canada 
Working_Year is significantly associated with salary as Salaries in 2022 are significantly higher than those in 2020 and 2021 (partially attributing to the recovery of the Covid-19 pandemic)
No significant deviation that 40% of employees would accept lower pay for remote work 

## Future Developments
While the findings offer practical insights into expected salary structures in the industry, it is important to acknowledge several limitations. The analysis is based on a single dataset, and does not account for special economic circumstances (i.e. Covid-19 Pandemic) or non-salary compensation such as equity or bonuses. Notably, none of the employees in the dataset are based in Singapore, which limits the direct applicability of the results to the local job market.

To strengthen future analysis, we recommend incorporating longitudinal data, controlling for additional variables (i.e. education level, skill sets, industry domain), and applying predictive modeling techniques. Nonetheless, this report provides a comprehensive overview of salary expectations in the Data Science field — offering valuable guidance for DSAI students as they prepare to enter the workforce.

