# excel-A-Z
Excel learns your patterns, organizing your data to save you time. Easily create spreadsheets from templates or on your own and use modern formulas to perform calculations.

## Data Cleaning
1. Setup problem Statement
2. Fixing preliminary analysis(complete, consistent and accurate)
3. Fixing misspellings/typo
4. Checking for bias

## Data Cleaning importance
1. To ensure high integrity.
2. To check bias involved in data
3. data should be in-line with problem statement
4. Data should have complete sample size.
5. There should be uniformity in data.

## Data Analysis
1. Understanding problem Statement
2. Adjusting and formatting Data(lookup, data fromatting, pivot table, data validation)
3. Finding Appropriate relationship between datasets.

## Data Visualization
1. Delivering data in most efficient way.
2. Helps making critical decisions in an unbiased manner.

## Function
They are predefines instructions that perform specific calculations
Syntax: =Fromula(Range of cells)
1. =COUNTIF(Range, Condition) : Count the number of cells that match a specific condition
2. =LEN(text) : Returns the length of Text String
3. =LEFT/RIGHT(text, values) : Return Specific number of characters
4. =CONCATENATE(cell1, cell2) : combines multiple text cells into single cell.
5. =TRIM(cell) : remove empty spaces at the start

## LOOKUP FUNCTIONS
### 1. Vlook Up
A Function that searches for a certain values in a column to return a corresponding piece of information.
=VLOOKUP(value, table array, column_index_num, true/false)
True: Approximate Ma tch
False: Exact Match
![alt text](https://cdn.extendoffice.com/images/stories/doc-excel/excel-vlookup-function/doc-vlookup-function-1.png)

### 2. Hlook Up
A Function that searches for a certain values in a row to return a corresponding piece of information.
=HLOOKUP(value, table array, row_num, true/false)
True: Approximate Match
False: Exact Match
![alt text](https://cdn.extendoffice.com/images/stories/excel-functions/hlookup-function/doc-hlookup-function-1.png)

## CONDITIONAL FORMATTING
How the cell looks when value meets specific condition.
Icon Set
Arrow Explanation: by default, for 3 icons, Excel calculates the 67th percent and 33th percent. 67th percent = min + 0.67 * (max-min) = 2 + 0.67 * (95-2) = 64.31. 33th percent = min + 0.33 * (max-min) = 2 + 0.33 * (95-2) = 32.69.  A green arrow will show for values equal to or greater than 64.31. A yellow arrow will show for values less than 64.31 and equal to or greater than 32.69. A red arrow will show for values less than 32.69.
![alt text](https://cdn.educba.com/academy/wp-content/uploads/2019/03/Conditional-Formatting-For-Blank-Cells.png)

## DATA VALIDATION
Allows one to control what can and cannot be entered.
![alt text](https://www.customguide.com/images/lessons/excel-2019/excel-2019--data-validation--01.png)

## PIVOT TABLES
A table used to sort, count, group, total or reorganize data stored in table. It helps us change rows into columns and column into rows.
It can be grouped and perform advance calculations on them.
![alt text](https://www.iaao.org/education/online/809/tutorials/PivotTables/SelectPivotTable.jpg)