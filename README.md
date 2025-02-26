![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Lab | Data Visualization in R

## Load dataset and libraries

Load the Superstore dataset and libraries needed.

## Boxplot
A summary table or boxplot can be useful to visualize the distribution of key variables.
Generate a boxplot to visualize Sales and another to visualizr Profit

## Bar Plots

Create a bar plot to show the top 10 orders with highest value of sales.

## Heatmap

Use a heatmap to visualize the pattern of missing data.

```r
# Install and load the VIM package if not already installed
library(VIM)

# Visualize missing data pattern
missing_pattern <- aggr(dataset, col=c('navyblue','red'), numbers=TRUE, sortVars=TRUE, labels=names(dataset), cex.axis=.7, gap=3, ylab=c("Missing data","Pattern"))
```

## Histogram 

Generate a histogram that can show the distribution of the Profit column.

## Bar Plots for Aggregated Data

Generate a bar plot that shows Total Sales by Category and a barplot that shows Profit by Category.

## Deliverables

- Submitted notebook (or file) with your responses to each of the exercises.

## Submission

- Upon completion, add your deliverables to git. 
- Then commit git and push your branch to the remote.
- Make a pull request and paste the PR link in the submission field in the Student Portal.

<br>

**Good luck!**