## Analysis of Stack-Overflow 2023 Survey

### Problem

*Read the survey_result_public_EDAsurvey_2023.pdf document properly, to gain more perspective and 
understanding about the dataset.*

*Task is going to be simple. Perform a robust EDA, explore every parameter possibles and communicate your 
insights via appropriate visuals. Educate us on the choice of visual and document your entire findings*


**Application**

*Python*

**Libraries**
- Pandas
- NumPy
- Matplotlib
- Seaborn

**Data**

*Stack-Overflow 2023 survey*

**Data Structure**

The data set contains 89,184 rows and 84 columns

**Data Cleaning and Preparation**

Each of the columns represent the responses to the questions asked in the survey. The survey had seven sections which are were:
1. Basic Information
2. Education, Work, and Career
3. Technology and Tech Culture
4. Stack Overflow Usage + Community
5. Artificial Intelligence
6. Professional Developer Series (Optional)
7. Final Questions

But for the purpose of our Exploratory Analysis we only explored informations in section 1 (Basic Information), section two (Education, work and Career), section 3 (Technology and Tech culture), section 5 (Artificial Intelligence), section 6 (work experience) and final quesitons

Analysis was carried out done in three categories:
1. Univariant analysis
2. Bivariant analysis
3. Multivariant analysis

Since we were not using all the sections, we going to dropped columns not relating the above mentioned sections.

**Visualization**

- Bar charts were used for columns having more than 5 unique values. 
- Scatter plot was used for relationship between two numerical variables
- Pie charts were used for column with 5 or less unique values to show proportions of whole
- Stacked bar charts were used for multivariant analysis. 

