Amazon Global Dashbord
Problem Statement
This dashbord helps the understand data year wise of selling and production by related to the customer and understand the growth and down in economy.

Since 2012,2013,2014 and 2015 having four year amazon global data and visualise the sales projection, product quantity ,KPI, and return by through sales by segment and sales by market.

Steps followed
Step 1 : Load data from execl into Power BI Desktop, dataset is a csv file.

Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

Step 3 : Also since by default, profile will be opened only rows so you need to select "column profiling based on entire dataset".

Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".

Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay")

Step 6 : In the report view, under the view tab, theme was selected.

Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view.

Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".

Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes. Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.

     Although, by default, while calculating average, blank values are ignored.
Step 10 : A bar, pie and donut charts was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender.

In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

Step 12 : In the report view, under the insert tab, two text boxes were added to the canvas, in one of them name of the airlines was mentioned & in the other one company's tagline was written.
Step 13 : In the report view, under the insert tab, using shapes option from elements group a rectangle was inserted & similarly using image option company's logo was added to the report design area.
Step 14 : Calculated column was created in which, customers were grouped into various age groups.
There are take reports below on dashbord
a) According 4 Year(2012,2013,2014,2015), estimate results globalwise. b)we work on sales by segmentation,sales by global market. c)Profit by customer name. d)Bottom 5 profit by product. e)Top 5 profit by product

Insights
A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

Total number of sales projection : 2.26 million(since - 2012) 2.68million(since - 2013) 3.41 million(since - 2014) 4.30 million (since - 2015)

Total number Product Quantity: 3022 (since - 2012) 3087 (since - 2013) 3242 (since - 2014) 3418 (since - 2015)

Total number of KPI 31K(since - 2012) 38K(Since - 2013) 48 k (since - 2014) 61 k (since - 2015)

According pie chart
#Sales by segment Since 2012 2013 2014 2015

Cunsumer      51.94%    54.67%    50.77%    49.8%
Home office   17.44%    16.4%     17.96%    20.12%
corporate     30.61%    28.93%    31.27%    30.08%
##According donut chart

#Sales by market Since 2012 2013 2014 2015

Asia          31.59%    32.27%    32.07%   31.93%
Europe        23.93%    26.8%     24.92%   27.45%
USCA          21.81%    18.18%    19.6%    20.03%
LATAM         17.04%    17.36%    17.86%   16.43%
Africa        5.63%     5.39%     5.55%    4.16%

       
##Profit by consumer Name

Since 2012

Names

sanjit chand
2.Elpida Rittenbach 3.carol Adams 4.Nathan Mautz 5.Greg tran

since 2013

1.Mike Gockeb 2.Keith Dawkins 3.Ellis Ballard 4.Fred hopkins 5.Christop Martinez

since 2014

1.Reymond Butch 2.Jane Waco 3.Tom Ashbrook 4.Bill Eplett 5.Hunter Lopez

since 2015

1.Tamara Chand 2.Adrian barton 3.Christop conant 4.Karen daniels 5.susan pistek

In world map show the where amazon market spread market from 2012 upto 201
