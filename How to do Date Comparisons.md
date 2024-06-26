Date compasrion allows a designer or end user to compare measures for two or more date ranges. The charts or crosstab with a date dimension, this function automatically becomes available in this component's menu. The document present some most common use cases




# Most Common Date Comparisons
[How do I compare this past week to the same week last year?](#week)

[How do I compare this past week to the previous week?](#previous)

[How do I calculate percent change year over year in a table?](#table)

[How do I compare two arbitrary periods?](#nonconsecutive)







# How do I compare this past week to the same week last year? <a name="week"></a>
[Instructions](#inst1)

[When starting with a previous week](#prev1)

[When comparing this past month to the same month last year](#month)

[When starting from the middle of a month](#middle2)

[When starting with a previous month](#prev2)

[When comparing periods of multiple months](#multiple2)

[When starting from the middle of a week](#middle1)

[When comparing periods of multiple weeks](#multiple1)




### Instructions<a name="inst1"></a>

The example is performed using the dashboard linked [here](https://www.inetsoft.com/public/app/viewer/view/global/Dashboards/Date%20Comparison)

Right click on the chart to see a menu of options, click on 'Date Comparison'.

![](screenshots/right-click-menu.PNG)
<br/>

Make sure you are on the 'Standard Periods' tab.  Enter '2' in 'Previous' and select 'Years' in the dropdown menu. Check box for 'Today' and 'Include Year For End Date'. Uncheck the box for 'From Beginning of Each Year To...'

![](screenshots/compare-two-years.PNG)

<br/>

Select 'Same Week' under 'Compare Data of',  'Year' in 'For Each', and 'Week' under 'Granularity'. Check box for 'Use Range End Date'. Click 'Ok'.

![](screenshots/compare-same-week.PNG)
<br/>
The chart should change to show only the two data points, one for the most recent week, and one for the same week last year.

![](screenshots/compare-same-week-result.PNG)


## How do I compare a previous week to the same week last year?<a name="prev1"></a>

Perform the steps above, except where it says 'Range End Date' uncheck the box for 'Today' and instead manually enter the last day of the week you want to compare with the same week last year.


## How do I compare this past month to the same month last year? <a name="month"></a><a name="month"></a>
Select 'Same Month' under 'Compare Data of',  'Year' in 'For Each', and 'Month' under 'Granularity'. Check box for 'Use Range End Date'. Click 'Ok'.
##  How do I compare a previous month to the same month last year?<a name="prev2"></a>
Perform the steps above, except where it says 'Range End Date' uncheck the box for 'Today' and instead manually enter the last day of the month you want to compare with the same month last year.
##  How do I compare the past thirty days starting in the middle of the month to the same thirty days last year?<a name="middle2"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end dates of both thirty day periods.
## How do I compare the past two or three months with the same months last year?<a name="multiple2"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end dates of the periods you want to compare.

## How do I compare the past seven days starting in the middle of the week to the same period last year?<a name="middle1"></a>
Use the  [Custom Periods](#arb) tab and enter date ranges of the seven day periods you want to compare.
## How do I compare the past two or three weeks with the same period last year?<a name="multiple1"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end date of the periods you want to compare.




<br/><br/><br/>




# How do I compare this past week to previous week? <a name="previous"></a>
[Instructions](#inst2)

[When comparing a current month to previous month](#prev3)

[When comparing seven day periods starting in the middle of the week](#rolling)


### Instructions<a name="inst2"></a>

The example is performed using the dashboard linked [here](https://www.inetsoft.com/public/app/viewer/view/global/Dashboards/Date%20Comparison)

Right click on the chart to see a menu of options, click on 'Date Comparison'.

![](screenshots/right-click-menu.PNG)
<br/>
Make sure you are on the 'Standard Periods' tab.  Enter '1' in 'Previous' and select 'Weeks' in the dropdown menu. Check box for 'Today' and 'Include Week For End Date'. Uncheck the box for 'From Beginning of Each Week To...'

![](screenshots/compare-one-week.PNG)

<br/>

Select 'All' under 'Compare Data of', and 'Week' under 'Granularity'. Click 'Ok'.

![](screenshots/compare-past-two-weeks.PNG)
<br/>
The chart should change to show only the two data points, one for the most recent week, and one for the same week last year.

![](screenshots/compare-past-two-weeks-result.PNG)

### How do I compare this past month to the previous month?<a name="prev3"></a>

Follow the instructions above, except select 'Months" instead of 'Weeks' in both dropdowns.

### How do I compare the past two seven day periods, starting in the middle of the week?<a name="rolling"></a>

Use the  [Custom Periods](#arb) tab and enter the start and end date of the periods you want to compare.

# How do I calculate percent change year over year in a table? <a name="table"></a>

[Instructions](#taleinst)

[When comparing this past month to the same month last year](#month2)

[When starting from the middle of a month](#middle3)

[When starting with a previous month](#prev4)

[When comparing periods of multiple months](#multiple3)

[When starting from the middle of a week](#middle4)

[When comparing periods of multiple weeks](#multiple4)


## Instructions<a name="taleinst"></a>



This example will use the crosstab table in the product return dashboard found in the InetSoft gallery


[here](https://www.inetsoft.com/evaluate/bi_visualization_gallery/dashboard.jsp?dbIdx=9)

![](screenshots/product-return-table.PNG)

Click on the ... button on the top right corner of the table to access menu options. Click 'Date Comparison'.

![](screenshots/table-menu.PNG)

Make sure you are on the 'Standard Periods' tab.  Enter '2' in 'Previous' and select 'Years' in the dropdown menu. Check box for 'Today' and 'Include Year For End Date'. Uncheck the box for 'From Beginning of Each Year To...'

![](screenshots/table-compare-past-two-years.PNG)

Select 'All' under 'Compare Data of', and 'Year' under 'Granularity'. Select '%Change & Value'. Click 'Ok'.

![](screenshots/table-percent-change-and-value.PNG)

The table should update with the most recent year displaying the original aggregates plus the percent change from the previous year.

![](screenshots/table-date-comparison-plus-percent.PNG)

## How do I compare this past month to the same month last year? <a name="month"></a><a name="month2"></a>
Select 'Same Month' under 'Compare Data of',  'Year' in 'For Each', and 'Month' under 'Granularity'. Check box for 'Use Range End Date'. Click 'Ok'.
##  How do I compare a previous month to the same month last year?<a name="prev4"></a>
Perform the steps above, except where it says 'Range End Date' uncheck the box for 'Today' and instead manually enter the last day of the month you want to compare with the same month last year.
##  How do I compare the past thirty days starting in the middle of the month to the same thirty days last year?<a name="middle3"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end dates of both thirty day periods.
## How do I compare the past two or three months with the same months last year?<a name="multiple3"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end dates of the periods you want to compare.

## How do I compare the past seven days starting in the middle of the week to the same period last year?<a name="middle4"></a>
Use the  [Custom Periods](#arb) tab and enter date ranges of the seven day periods you want to compare.
## How do I compare the past two or three weeks with the same period last year?<a name="multiple4"></a>
Use the  [Custom Periods](#arb) tab and enter the start and end date of the periods you want to compare.


# How do I compare two arbitrary periods?<a name="nonconsecutive"></a>

[Comparing Arbitrary Periods](#arb)

[Instructions](#inst3)

[Adding additional periods for comparison](#add)

## Comparing Arbitrary Periods with the Custom Periods Tab<a name="arb"></a>
In addition to comparing nonconsecutive months, the Custom Periods tab can also be used for other comparisons of arbitrary periods, such as comparing the past 7 days starting in the middle of the week, the past 30 days starting in the middle of a month, or comparing clusters of multiple weeks or months. Follow the directions below but enter date ranges that address your query.


## Instructions<a name="inst3"></a>
This example will show how to compare two nonconsecutive months from the same year. Right click on the chart to see a menu of options, click on 'Date Comparison'.

![](screenshots/right-click-menu.PNG)
<br/>
If you want to compare two nonconsecutive months, such as March and May, of the same year or different years, click the 'Custom Periods' tab on the top right of the Date Comparison menu. When in the 'Custom Periods' tab, enter the start and end dates of the months you want to compare and click 'OK'.

![](screenshots/compare-non-consecutive-months.PNG)

The chart should change to show only the two data points, one for each month you entered the date ranges of.

![](screenshots/compare-non-consecutive-months-result.PNG)

##  How do I compare three or more months?<a name="add"></a>
You may compare as many periods as you like in the 'Custom Periods' tab, click the + button underneath the visible date ranges to add more periods.

![](screenshots/add-additional-custom-ranges.PNG)

