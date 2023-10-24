# Module 1 Challenge 

Excel Challenge 

## Instructions

Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

1) Went to "conditional formatting" on the top of excel and clicked on "New Rule" and switched it to "Classic" then clicked on "Format Only Cells That Contain" a specific text containing the words Failed, Successful, Live, and Canceled. I assigned a different color for each word per the instructions. I applied this rule to all necessary cells within the column. 

Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.

1) Created the new column using the the insert column feature from excel. I used the ROUND formula to help me see how much money the campaign made in relation to its goal. I timesd it by 100 to get the value to match that of what the outcome showed for the done file. 

Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

1) Did the same step as the first instruction. Created a "New Rule" and used a "3 Color Scale" method and awarded each point the instructed number and color so that each cell transitions to its particular color according to the number in the "percent funded" column 

Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

1)  I used a simple formula =E12/H12 and then formatted the cell by number and gave it at most 2 decimal places 

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

1) Used the TEXTSPLIT function between the "Category and Sub-Category" column and used the backslash "/" as the separator and it instantly split between both columns 

Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

1) Created the pivot table. On the pivot table fields I put "country" under filters, "outcome" under column, "parent category" under row, and "count of outcome" under values. 

Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

1) Went to "insert" and clicked on "stacked column" then it portrayed the information I needed 

Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

1) Created the pivot table. On the pivot table fields I put "country" and "parent category" under filters, "outcome" under column, "sub-category" under rows, and "count of outcome" under values.  

Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

1) Went to "insert" and clicked on "stacked column" then it portrayed the information I needed 

Create a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.

1) Used the formula from the link provided in the module. Once I converted it to the default value, I went to "format cells" and formatted them per date. Then applied this to all the cells necessary 

Create a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

1) Used the formula from the link provided in the module. Once I converted it to the default value, I went to "format cells" and formatted them per date. Then applied this to all the cells necessary 

Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

1) Created a new pivot table in another sheet; put "parent category" and "years" under filters, "outcome" under columns, "Date Created Conversion" under rows, and "count of outcome" under Values

Now, create a pivot-chart line graph that visualizes this new table.

1) Used a 2-D stacked bar in the "Insert" side of excel to visualize the table 

I did have to google on several different occasions how to do the steps for each task assigned. I did not know that we were required to cite our sources until I was completely done with the project. I re-traced my steps to the best of my ability and here is what I was able to find. However, this might not be the entire list of what I used, but I tried:

https://www.exceldemy.com/excel-change-cell-color-based-on-value/
https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html
https://wallstreetmojo.com/round-excel-function/#:~:text=This%20formula%20takes%20two%20arguments,ROUND(D1%2C2).
https://support.microsoft.com/en-us/office/highlight-patterns-and-trends-with-conditional-formatting-eea152f5-2a7d-4c1a-a2da-c5f893adb621#:~:text=conditional%20formatting%20to.-,On%20the%20Home%20tab%2C%20click%20Conditional%20Formatting.,want%2C%20and%20then%20click%20OK.
https://www.ablebits.com/office-addins-blog/textsplit-function-excel-split-cells-strings/#:~:text=The%20TEXTSPLIT%20function%20in%20Excel,two%20of%20which%20are%20required.&text=Text%20(required)%20%2D%20the%20text%20to%20split.

—
Created by Jesse Olivarez for the University of Utah: Data Analytics Bootcamp
