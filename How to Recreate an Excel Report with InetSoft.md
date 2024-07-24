# How do I recreate my Excel report with InetSoft's tool?

This document contains instructions on how to recreate your Excel report using InetSoft's Style Intelligence. It covers the most common usage needs for table style reports.

# How do I recreate my Excel formulas in a table?

[Instructions](#inst)

[How do I include multiple lists in the same table?](#lists)

[How do I combine multiple pivot tables into one table?](#pivot)

[How do I group table columns under subheaders??](#sub)




# How do I combine multiple pivot tables into one table? <a name="pivot"></a>

This multilevel freehand table example uses the Orders Details dataset.

Begin by dragging out a freehand table element and selecting 'Edit'.

Then right click on a cell and click 'Insert Row'. Right click on a cell again and select 'Insert Rows/Columns'.

![](screenshots/insert-rows-columns.PNG)


Insert 3 extra columns, after the selection.

![](screenshots/insert-extra-rows-columns.PNG)





Add order date, sales team, and sales rep to the cells where they are pictured below.

![](screenshots/add-sales-team.PNG)



Select the cell containing order date, and set group to the month level. Set 'expand cell' to Vertical.

![](screenshots/set-grouping-to-by-month.PNG)

Make sure that on 'Sales Team', and 'Sales Rep', expand is set to Horizontal.

Next, move in Category and Product into the first two cells of the third row. Set expand to Horizontal.

Add 'Gross Amount' to the bottom cell of the second column.

![](screenshots/add-gross-amount-dimension.PNG)

Next, move 'Category' and 'Product' into the first two cells of the third column. Make sure expand on both is set to Horizontal.

![](screenshots/move-in-category-and-product.PNG)



Drag 'Gross Amount' into the bottom cell of the third column.

![](screenshots/drag-out-gross-amount-again.PNG)

Select the top two blank cells on the right. Right click  and select 'Merge Cells'.

![](screenshots/merge_cells.PNG)

Drag 'Customer' dimension into the merged cells. Make sure it is set on Horizontal.

![](screenshots/drag-customer-into-fourth-space-highlight.PNG)


Drag 'Gross Amount' measure into the bottom right cell.

![](screenshots/drag-gross-amount-into-fourth.PNG)

Click 'Finish'. You now have a freehand table which combines three pivot tables into one.


![](screenshots/combine-pivot-table-result.PNG) ![](screenshots/combine-pivot-table-result1.PNG) ![](screenshots/combine-pivot-table-result2.PNG)
