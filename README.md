This only reference for Core Designer Cert + using Gemini is correct 70% with files below
Spearman correlation - 'GDP per capita'
https://quizlet.com/639360584/bis-375-exam-flash-cards/
https://www.cliffsnotes.com/study-notes/5437727

 ### NOT SURE: --------------------------------------------------------------------------
In which of the following visual recipes is the Pre-filter step NOT available?
- Window

In the assessment project, if you removed stock_code as the Partitioning column from the Window recipe,...?
- No


 ### VERIFIED: --------------------------------------------------------------------------

Which of the following statements are true of scenarios? Select two that apply.
- The "Last runs" tab of a scenario will list all runs of a scenario.
- To launch a scenario when there are changes in a SQL database, you should use the "Trigger on a SQL query change".

For the assessment project, how would a failed ... Distinct recipe output... Build scenario?
- None of these

Metric and checks cannot be computed on which of the following objects?
- Columns with over 20 categories...

In the assessment project, why did the first build of the Product_Aggregated dataset fail?
- Its root path...

In the assessment project, from your calculations of the top 5 customers from each year, which customerid represented the third highest total revenue in 2009?
- 15061

Which two settings are required in order to run a Top N recipe? Select two answers.
- The number of top and/or bottom 
- At least one column to sort by

What two settings are the absolute minimum requirement in order to run a Pivot recipe? Select two answers.
- At least one aggregation to populate...
- Pivot column

In the assessment project, what was the average quantity for the stock item "84077" (World War 2 Gliders Asstd Designs) that was sold during the week of "2010-11-01"?
- 402.26

Which of the following is NOT an example of a metric?
- Whether or not a column has more than 3 missing values

In the assessment project, after retaining only records with a quantity greater than or equal to 2000 units, what was the 4 week rolling average on total quantity sold for the stock item 84077 on 2010-11-29?
- 3097.5

In the assessment project, for stock item 22197, what was the largest gap in days between any two weeks of qualifying purchases in the windowed output?
- 182

Imagine a Flow with more than 100 datasets and recipes. Which views are most likely to provide useful information for identifying the parts that take a long time to compute? Select two choices.
- count of records 
- connections and recipe engines

In the assessment project, after looking at the recipe engine Flow view, a colleague suggests changing all of the recipe engines to Spark. Is this a good idea?
- No, this is not setting...

Which of the following Formulas correctly uses the substring function to retrieve only the last two characters of a string column named "my_column"?
- substring(my_column, -2)

In the assessment project, at what step in the "Initial Build" scenario, does the scenario fail?
- At Step #3, a check on column counts fails or cannot be evaluated.

The output to a Window recipe will have the same number of rows as its input dataset.
- Sometimes true.

In the assessment project, what is the value returned by the data quality rule on the record count of the Distinct recipe output? 
- WARNING

Your dataset contains the predicted revenue for five customers, where rows contain the values of 2565, 4398, 3571, 4432, and 5598. You have configured the Top N recipe to retrieve the top and bottom row and sort the data in descending order. Which of the following best represents the values in the output dataset?
- 5598, 2565

In the assessment project, if you removed stock_code as the Partitioning column from the Window recipe, could you still find the rolling average for each stock_code?
- No, removing these groupings changes

Which of the following is the correct Formula expression for creating a column that outputs “True” if the number of characters in a column called “Free Text Response” is greater than 50, and otherwise “False”?
- if(length(strval("Free Text Response")) > 50, "True", "False")

Which of the following is a required component for a scenario?
- A sequence of steps...

In the assessment project, a colleague suggest replacing the Stack recipe with a Join...?
- No

The ___________ recipe offers a Computed Columns step to create a new column with a ___________. Assuming the input dataset is SQL-based, select two choices that are true.
- Window, SQL expression
- Group, DSS Formula

In the assessment project, which of the following is NOT one of the ten most common product descriptions in the output to the Distinct recipe?
- Strawberry Ceramic Trinket Box

In which of the following visual recipes is the Pre-filter step NOT available?
- Prepare

Which of the following statements about the Window recipe is true?
- In order to correctly compute the rank for each row, an Order column must be specified.

In the assessment project, the Group recipe that creates the Product_Aggregated Dataset uses a Post-filter step to remove products with low quantities of sales. It would have been more efficient to use a Pre-filter step.
- False. The column used as the filter condition is only created in the Group step.

Metrics cannot be computed on which of the following objects?
- Recipes

Which of the following is a required component for a scenario?
- A sequence of steps or a custom script to run when the scenario launches.
