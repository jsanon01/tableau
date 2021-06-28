# Tableau Bootcamp


### Introduction

Founded in 2003 in Mountain View, Tableau Software is an American interactive data visualization software company focused on business intelligence.  

Deploy in the cloud, on-premises, or natively integrate with Salesforce CRM. Connect to all of your data with fully integrated AI/ML capabilities, governance and data management, visual storytelling and collaboration.  with Tableau.

![Tableau](https://github.com/jsanon01/tableau/blob/main/images/tableau.png)

### Tableau has 3 main parts or sections:
- Connect (left pane) --> to different file format or DB servers 
- Open (middle pane) --> is where workbooks and worksheets take place
- Discover (right pane) --> contains various links such as training, get started ...

### Tableau has 3 types of canvases or pages
Tableau has 3 different types of cancases or pages that we can use to create and present data analysis results:

- Worksheets --> are good to create visualizations
- Dashboards --> are suitable to combine various worksheets.
- Stories --> are sheets that contain sequence of worksheets and dashboards that work together to convey information.

## Example of Worksheet
![Worksheet](https://github.com/jsanon01/tableau/blob/main/images/worksheet.png)

## Example of Dashboard (with 3 worksheets)
![Dashboard](https://github.com/jsanon01/tableau/blob/main/images/dashboard.png)

### Dashboard Interaction 

![Funel](https://github.com/jsanon01/tableau/blob/main/images/funel.png)

If you click on the funels of the 3 worksheets, they will interact together.
When clicking on specific state, you'll have some interactions: 
- Sales by States (interaction of specific state)
- Coffee Sales (sales by specific state)
- Seasonal Fluctuation (fluctuation of clicked state)

<!--
### Columns = dimension (not aggregated) vs Rows = measure (aggregated)

Columns are not only X-axis but also represent dimemsions, which categorize or segments the data.

Dimensions are qualitative in nature and mathematical operations like SUM(), AVG(), can't be done on them. 

Rows are not only Y-axis nut also represent measures.

Measures always represent numerical data meaning operations and aggregations can be performed on them.

#### Blue means discrete values and deals with a list or category. | Such example is a car's gear number with only 5 speeds.

#### Green means measure values and deals with a range or continuous values | Such example is the current speed of a car

#### Measure can also be used for mathematical operations.

-->
### Data Types

Tableau uses the following Data Types:

- String        - Number            - Boolean

- Date          - Date & Time       - Geographic


#### It is possible to convert some fields from one type to another.

#### => Dashboard's purpose in Tableau is to tell a story, which contains data, visuals, and narrative.
#### => Workbooks contain various dashboards and visualizations
#### => Discover pane is like a gold mine for Tableau to learn tips and tricks.


### Relevant Questions about the storytelling

- Who is our audience?
- What is our purpose?
- What data do we have?


### Values of date_part

Many functions in Tableau use date_part, which is a constant string argument.

The valid date_part values that we can use are:

- Year      => 4-digit year                      
- Quarter   => 1-4
- Month     => 1-12                             
- Day       => 1-31
- Weekday   => 1-7                            
- Week      => 1-52
- Hour      => 0-23                              
- Minute    => 0-59
- Second    => 0-60

<!-- 
#### DATEPART not only is "discrete by default" but also returns an integer.
#### DATETRUNC not only is "continuous by default" but also use rounding operations.



- Join is done at the row level.

- Blending is done at the agrgegation level.

### Hosting a 'Static website' for SKOUBI Landscaping on AWS S3 bucket
[Skoubi Landscaping](https://skoubi.s3.amazonaws.com/index.html)

-->
