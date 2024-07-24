# How do I recreate my Excel report with InetSoft's tool?

This document contains instructions on how to recreate your Excel report using InetSoft's Style Intelligence. It covers the most common usage needs for table style reports.

[How do I combine multiple pivot tables into one table?](#pivot)

[How do I include multiple lists in the same table?](#lists)

[How do I group table columns under subheaders??](#sub)




# How do I combine multiple pivot tables into one table? <a name="pivot"></a>

This multilevel freehand table example uses the Orders Details dataset. We will be creating a table that combines pivot tables displaying orders by month broken down by team and salesperson, product category and product, and company.

Begin by dragging out a freehand table element and selecting 'Edit'.

Then right click on a cell and click 'Insert Row'. 

![](screenshots/insert-row-highlight.png)


Right click on a cell again and select 'Insert Rows/Columns'.

![](screenshots/insert-rows-columns-highlight.png)


Insert 3 extra columns, after the selection.

![](screenshots/insert-extra-rows-columns-highlight.png)

Drag out dimension 'Order Date' into the bottom left cell. 

![](screenshots/order-date-into-bottom-left-column-highlight.png)

Select the cell containing order date, and set group to the month level. Set 'expand cell' to Vertical.

![](screenshots/set-grouping-to-by-month-highlight.png)



Add dimensions Sales Team' and 'Sales Rep' to the cells where they are pictured below.

![](screenshots/add-sales-team-highlight.png)





Make sure that on 'Sales Team', and 'Sales Rep', expand is set to Horizontal.

Add 'Gross Amount' to the bottom cell of the second column.

![](screenshots/add-gross-amount-dimension.PNG)

Next, move dimensions 'Category' and 'Product' into the first two cells of the third column. Make sure expand on both is set to Horizontal.

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
