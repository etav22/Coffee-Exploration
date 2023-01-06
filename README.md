# Purpose 
This was the final project for my Introduction to Data Science Programming class (as part of my master's degree). For this project, we were tasked with doing an Exploratory Data Analysis (EDA) of either an instructor-chosen dataset or any dataset we found online (with instructor approval). Since my teammates and I love coffee, we decided to choose a dataset around that topic ☕️ 

# Data
We got our data from the [coffee-quality-database](https://github.com/jldbc/coffee-quality-database) github repo in which `jldbc` scraped the data from the Coffee Quality Insitute. For further information on the data, check out the repo!

# Structure
Seeing as the defined task was quite simple (conduct EDA with no advanced statistical methods), the structure of this repo is quite simple. Here is an explanation on each of the components in the repo:

- `final_report.pdf`: The written report we had to compose with the EDA we conducted on our dataset.
- `presentation.pdf`: Findings that we presented to our classmates during one of our live sessions.
- `notebooks`: The notebooks that I specifically worked on. The `eda.ipynb` generates a dataset called `arabica_coffee_cleaned.csv` which then feed the `farm_conditions.ipynb` notebook. 

All of the work you'll find in this repo is work that I composed/contributed to. My main contributions were in the form of:

- Cleaning the dataset and engineering new features
- Investigating the effects of farm characteristics and methods the coffee quality
- Composing the bulk of the presentation
- Writing the bulk of the "Data Cleaning, Validating, and Exploring" and "Question 2" on the final report