# Excel_challenge - By JayLaxami
Excel Challenge
**Background**

Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this week's Challenge, you will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

**Instructions**

Using the Excel workbook in your .zip file, modify and analyze the sample-project data and try to uncover market trends.

    Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is     currently live.
    
    Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.   

    Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should     transition to green at 100 and blue at 200.

    Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

    Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate      columns.

    Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

    Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

    Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

    Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

    The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site. that can be used to convert these timestamps      to a normal date.

    Create a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date               format.

    Create a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

    Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category     and Years.

Now, create a pivot-chart line graph that visualizes this new table.

**Crowfunding Goal Analysis**

Create a new sheet with 8 different columns:

    Goal

    Number Successful

    Number Failed

    Number Canceled

    Total Projects

    Percentage Successful

    Percentage Failed

    Percentage Canceled

    
**Goal Column Range**

In the Goal column, create 12 different rows with the following headers range:

        Less than 1000

        1000 to 4999

        5000 to 9999

        10000 to 14999

        15000 to 19999

        20000 to 24999

        25000 to 29999

        30000 to 34999

        35000 to 39999

        40000 to 44999

        45000 to 49999

        Greater than or equal to 50000

        
**Statistical Analysis**

Use Excel to evaluate the following values for the successful campaigns, and then do the same for unsuccessful campaigns:

    The mean number of backers

    The median number of backers

    The minimum number of backers

    The maximum number of backers

    The variance of the number of backers

    The standard deviation of the number of backers

