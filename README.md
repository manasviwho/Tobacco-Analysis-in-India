# Tobacco Smoking Analysis in India

## Introduction
I was convinced that Uttarakhand has the highest number of cigarette smokers, mainly because so many people from my college started smoking.

## Questions
1. Which states have the highest percentage of daily smokers?
2. Is there a link between smoking habits, education level, and occupation?
3. What are the age patterns in smoking habits?
4. Do people from different states prefer different tobacco products (cigarettes, hookah, rolled, etc.)?
5. Is tobacco product promotion still prevalent in some states?
6. What are the most popular methods smokers use to quit?

## Dataset
The dataset is from the second Global Adult Tobacco Survey (GATS) conducted by the Ministry of Health and Family Welfare (MoHFW) India. The data can be found [here](https://extranet.who.int/ncdsmicrodata/index.php/catalog/861). _It's from 2016 and the current scenario may differ significantly_.

## Data Cleaning
The dataset had 464 columns, many of which were irrelevant (e.g., number of household members). I eliminated the unnecessary columns and cleaned and formatted the remaining data.

### Problems
Despite cleaning, the dataset had several issues:
- Responses like "Refused to Answer" or "Not Applicable" in many cells.
- Implausible values such as '100' for 'Number of Cigarettes Per Day' and similar issues for other tobacco products.

## Data Transformation
I created new variables and categories for age, products, and education level. I also aggregated data for state-wise and age-wise analysis.

## Analysis and Visualizations

[Overview] (Images/Overview.png) 

### Answers to Questions
1. **States with the Highest Percentage of Daily Smokers**: North-Eastern states, including Meghalaya, Tripura, Mizoram, Arunachal Pradesh, Sikkim, and Assam, rank in the Top 10.
2. **Education and Occupation**: A significant proportion of daily smokers have "Primary or Less" education, with many being "Daily Wage/Casual Labourers".
3. **Age Patterns**: Younger age groups exhibit distinct smoking patterns compared to older groups.
4. **Tobacco Product Preferences by State**: There are notable differences in product preferences across states. For instance, half of Tripura’s smokers use Hookah, whereas it is the least used product in most other states.
5. **Tobacco Promotion**: Tobacco product promotion has been observed in many states, with West Bengal leading.
6. **Quitting Methods**: The most popular methods for quitting include Cessation Clinics, Smokeless Tobacco, and Nicotine Replacement Therapy.

### Additional Findings
- Punjab, one of the states with the lowest daily smoker prevalence, has an average of 19 cigarettes per day, compared to Meghalaya, which has the highest prevalence with an average of 7 cigarettes per day.
- Females constitute only 3.82% of daily smokers.
- The majority of daily smokers are between 26-45 years old.
- Students make up only 0.82% of daily smokers (likely different in the current scenario).
