# College-Application-Analysis
This is a data analysis and visualisation project developed with the help of python
School Applications Analysis
**Overview**
This project involves analyzing data about school applications from an aggregator website. The dataset comprises 10,000 entries with 8 columns: uniqueId, date, name, school, type, rating, tuition_fee, and acceptance_rate. The analysis includes data cleaning, handling missing values, and visualizing various aspects of the dataset to derive insights.

**Data Description**
uniqueId: Unique identifier for each application.
date: The date of application.
name: Name of the applicant.
school: Name of the school (e.g., Caltech, Wharton, Yale).
type: Type of school (Stem or non-Stem).
rating: Rating given to the school by the applicant.
tuition_fee: Tuition fee of the school.
acceptance_rate: Acceptance rate of the school.
Data Cleaning
Missing Values: The dataset had 2.21875% missing values.
rating, tuition_fee, acceptance_rate: Filled with median values.
date: Filled with mode value.
Analysis and Visualizations
Average Tuition Fee by School

Insight: Caltech has the highest average tuition fee, exceeding Wharton and Yale by 4%. Wharton and Yale have similar average tuition fees.
Distribution of Ratings for Different Majors

Insight: Most majors have a high rating distribution (4.0 - 5.0). LAW302 and CS4382 have a wider range (1.0 - 5.0).
Line Plot of Acceptance Rate by Date

Insight: Acceptance rates fluctuate seasonally. The median acceptance rate is around 92%.
Scatter Plot of Tuition Fee vs Acceptance Rate

Insight: Lower tuition fees correlate with higher acceptance rates, indicating an inverse relationship.
Histogram of Tuition Fees

Insight: Majority of the majors have tuition fees around 18,000.
Total Applicants by School

Insight: All three schools have a similar number of applicants. Caltech has 0.5% and 0.6% more applicants than Wharton and Yale, respectively.
Total Applicants by Major

Insight: All majors have a similar number of applicants. LAW102 has the highest number of applicants (11.5%) and LAW342 has the lowest (10.6%).
Applicants Across Majors and Their Range of Acceptance Rates

Insight: Most applicants (60%) have acceptance rates between 90-100%. Only 1% have acceptance rates below 70%.
**Conclusion**
Tuition Fees: Not a major difference between schools.
Ratings: Generally high satisfaction across all majors.
Acceptance Rates: Seasonal fluctuations suggest factors like application volume and competitiveness.
Tuition-Acceptance Relationship: Inverse relationship observed.
Applicant Distribution: Similar distribution among majors and schools.
Acceptance Rate Distribution: High competition for admission.
How to Run
Clone the repository.
Ensure you have the required libraries: pickle, pandas, numpy, seaborn, matplotlib.
Load the data from the provided SchoolApplicationpkl50103.dat file.
Run the analysis script to generate the visualizations.
Review the insights derived from the visualizations.
