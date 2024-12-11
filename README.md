# EDA Telecommunications

## Project Description
This notebook performs an exploratory data analysis on five datasets from the telecommunications company Megaline.

The notebook goes through the entire data cleaning and data enrichment process, merging 5 dataframes into just 1 with aggregated data.

Then creates graphs to analyze user consumption for each plan, to reach the conclusion of which plan generates more revenue.

Finally, perfoms some hypothesis tests to draw conclusions about the plans.

## Objectives
- Perform exploratory data analysis.
- Merge the 5 dataframes into 1 using the customer ID as a base.
- Create graphs to analyze user consumption for each plan.
- Perform hypothesis tests to draw conclusions about the plans.

## Tools and Libs used
- Python: Main language used for analysis.
- Pandas: Library for data manipulation and analysis.
- NumPy: Library for numerical operations.
- Matplotlib e Seaborn: Libraries for creating graphics.
- Scipy: Library for statistical analysis.

## Methodology
#### EDA
- Import libraries.
- Load the dataframes.
#### Preprocessing
- Identify and treat missing values.
- Identify and treat outliers.
- Merge the dataframes into 1 using the customer ID as a base.
#### Data Analysis
- Create graphs to analyze user consumption for each plan.
- Perform hypothesis tests to draw conclusions about the plans.

## Results
After cleaning and enriching the data, i sometimes use the pd.merge function to merge our 5 dataframes into just 1 dataframe with our necessary data aggregated in it. We use this dataframe to separately calculate the calling, messaging and internet data used by each user on each plan, then calculate the monthly revenue and draw conclusions based on this. We noticed that the Surf plan generates more revenue and is more profitable from the users' point of view, this makes this plan the one that attracts the most subscribers to the company, even though the ultimate plan is more expensive, its monthly revenue is lower because the surf plan has more users , there are rare occasions when users of the ultimate plan exceed the data offered by the plan.

## Learnings
- Data analysis: interpreting and extracting valuable insights from large volumes of data.
- Data cleaning: identifying and correcting missing, duplicate, and anomalous values.
- Creating graphics: using matplotlib and seaborn to visualize data in an intuitive and informative way.
- Data preprocessing: preparing data for analysis, including normalization and standardization.
- Use of libraries and tools: practical application of various libraries and tools from the Python ecosystem, such as Pandas, Numpy, Scipy Matplotlib and Seaborn.
- Hypothesis formulation: developing and testing assumptions about customer behavior based on data.
- Data-driven decision making: Using insights derived from data analysis to guide strategic decisions.
