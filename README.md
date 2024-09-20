# Evaluate-a-Manufacturing-Process
Analyze the manufacturing_parts table and determine whether the manufacturing process is performing within acceptable control limits:.

Create an alert that flags whether the height of a product is within the control limits for each operator using the formulas provided in the workbook.
The final query should return the following fields: operator, row_number, height, avg_height, stddev_height, ucl, lcl, alert, and be ordered by the item_no.
The alert column will be your boolean flag.
Use a window function of length 5 to calculate the control limits, considering rows up to and including the current row; incomplete windows should be excluded from the final query output.
