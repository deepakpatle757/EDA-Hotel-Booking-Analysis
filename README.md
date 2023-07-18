# Hotel Booking Analysis
# Project Summary -
This project is related to Hotel Booking and has two hotel descriptions, i.e City Hotel and Resort Hotel. This dataset contains a total of 119390 rows and 32 columns.In this, we divide the data manipulation workflow into three categories: Data collection, data cleaning and manipulation, and EDA(exploratory Data Analysis).As Further moved i.e Data collections first step to find different columns which is done by coding Head(), tail(), info(), describe(), columns() and some others method used for data collections, some of the columns name is updated here i.ehotel, is_canceled, lead_time, arrival_date_year, arrival_date_month, arrival_date_week_number, arrival_date_day_of_month, stays_in_weekend_nights.As we further moved we find unique value of each columns and generate a list in tabular form and also check the dataset type of each columns’ find some columns not in accurate data types which correct it later done in Data cleaning part and as well as duplicates data items must be removed as we find duplicates items equal to 87396 which is dropped from dataset later.

Before visualize any data from the data set we have to do data wrangling. For that, we are checked the null value of all the columns. After checking, when we are getting a column which has more number of null values, dropped that column by using the 'drop' method. In this way, we are dropped the 'company' column. When we are find minimal number of null values, filling thse null values with necesary values as per requirement by using .fillna()

Different charts are used for data visualization so that better insights and Business objective is attained.

# Project Goal
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. Purpose of our study is to find the best time to book a hotel room. The optimal length of stay in order to get the best daily rate. Study on special requests.We explore and analyze the data to discover important factors that govern the bookings.

# Exploratory Data Analysis:-
In this study we have sample data about the hotel industry that is not processed for use. Unprocessed data gives inaccurate results. To process this data is called data cleaning. We have cleaned the data by handling null values, outliers and dropping unwanted columns.

# Data Cleaning
# Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.

Country: - This has null values less than 5% thus the null values are filled with the mode value.

Children and babies: - There are only 4 null values so the null value is filled with mean

# Handling Outliers
An outlier is an extremely high or extremely low data point relative to the nearest data point and the rest of the neighboring co-existing values in a data graph or dataset we work with. We have used the Interquartile range method to handle outliers. To find the interquartile range (IQR), ​we first find the median (middle value) of the lower and upper half of the data. These values are quartile 1 (Q1) and quartile 3 (Q3). The IQR is the difference between Q3 and Q1

# Data study
i) UNIVARIATE ANALYSIS: Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

ii) BIVARIATE ANALYSIS: Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

iii) MULTIVARIATE ANALYSIS Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.

# Data Visualization :-
Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. The graphs used here for study are: -

Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.

Geo Mapping.

# Business objective attained as follows:
1.For hotel business to flourish few things which we need to consider is high revenue generation, customers satisfaction and employeee retention.

2.We are able achieve the same by showing the client which are the months which are high in revenue generation by pie chart distribution

3.Increasing the revenue achieved by bar chart distribution of which type room are most reserved and what are the months likely for visitors

4.So for these the client can be well prepare in advance so that minimum grievances would be faced by clients in long run and would help in further enhancement of their hospitality

5.Outliers like higher the visitor then adr has reduced drastically was shown in scattered plot so in off season client can engage with offices for bulk booking this will aslo help extra revenue generation

6.We are are able to shoe the trend of arrivals of visitor at client locations through which client engaged visitos well advance for there entaertainment and leisure activities

7.We where also able to co relate the values showing the max and min percentage between them so that the percenytage lying those numbers can be enhanced by various medium

# Conclusion
1.Maximumm guest are arriving in 2016. among of all of the years.

2.City Hotel seems to be more preferred among travellers and it also generates more revenue & profit.

3.Most number of bookings are made in July and August as compared rest of the months.

4.Room Type A is the most preferred room type among travellers.

5.Guest less styaing the hotel as hotel increase the ADR.

6.Most number of bookings are made from Portugal & Great Britain.

7.Most of the guest stays for 1-4 days in the hotels.

8.For long staying in hotel. customers prefers the Resort Hotel and for short staying customer prefers the City hotel

9.less than 5% of customers are reatined by the hotels.

10.Around one-fourth of the total bookings gets cancelled. More cancellations are from City Hotel.

11.City hotel has high no. of Waiting days.thus city hotel is more busy.

12.In July,Auguest,September the price of city hotel is highest. and for same month the price of resort hotel is less.

13.The Online-TA method is most preferble for customers.

14.Transient and transient-party type of customers are coming more in hotels.

15.The length of the stay decreases as ADR increases probably to reduce the cost.

16.The hotels which serves the BB meal are prefer by customers.

17.More no of special Request are seems to be in City hotel by customers.
