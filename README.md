# Kickstarter Analysis

## Performing analysis on Kickstarter data to uncover trends 

#### To assist Louise in determining how different Kickstarter campaigns fared in relation to their launch dates and funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
#### Analysis was performed by creating a pivot table from the kickstarter dataset and then filtering it to display only theater campaign and the quantity of outcomes associated with each outcome type on a monthly timeline. The pivot table data was visualized using a line chart so that we can see the progression of success and/or failures over the course of the year.
- ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/93271297/139292126-699d15dd-7e61-4bca-b7d8-cc0ff6226849.png)

### Analysis of Outcomes Based on Goals
#### Analysis was performed by pulling data from Kickstarter dataset to create a new sheet that shows the number of outcomes for Play campaigns and which goal bracket they fall within. The Countifs() function was used to calculate the outcome quantities for each goal bracket. The Play campaign data was visualized using a line chart so that we can see how campaigns fared as their target goal increased.
- ![Outcomes Based on Goal](https://user-images.githubusercontent.com/93271297/139292162-a487961b-3f37-4ae1-b25f-9d3dcefb0b05.png)

### Challenges and Difficulties Encountered
- The biggest challenge encountered were the functions that needed to be used to pull the necessary data from the Kickstarter dataset. Ensuring that the criteria for those is correctly input then ensures that it is pulling the accurate data you need to visualize any trends.

## Results

- We can conclude that Theater campaigns have the most success when launched during the summer months of May, June, and July and that few campaigns are canceled throughout the year.

- We can conclude that Play campaigns typically have a higher success rate when the target goal is lower.
