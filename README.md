# Hotel-booking-capstone
**Objective**
  * our objectie is to find the insights from the data-set(hotel_booking).
  * we have to find the hidden information that is useful for the upgrading the bussiness of the hotel. 
## Data Cleaning and Feature Engineering

### (1) Removing Duplicate rows
All duplicate rows were dropped.

### (2) Handling null values
- Null values in column `country` were replaced by 'others'.
- Null values in column `children` were replaced by the mean of the column.
  

### (3) Converting columns to appropriate data types

- Changed data type of `children`, `company`, `agent` to int type.


### (5) Creating new columns
- Created new column `all_nights` by adding `stays_in_weekend_nights`+`stays_in_week_nights`.

## Exploratory Data Analysis

Performed EDA and tried answering the following questions:

```
 Q1) Which agent makes the most no. of bookings?
 Q2) Which room type is in most demand and which room type generatesthe  highest adr?
 Q3) Which meal type isthe  most preffered meal of customers?
 Q4) What isthe  percentage of bookings in each hotel?
 Q5) Which is the most common channel for booking hotels?
 Q6) Which are the most busy months?
 Q7) From which country most of the guests are comin ?
 Q8) How long do people stay at the hotels?
 Q9)  Which hotel seems to make more revenue?
 Q10)  Which hotel hasa  higher lead time?
 Q11)  What is preferred stay length in each hotel?
 Q12)  Which hotel has higher bookings cancellation rate.
 Q13)  Which hotel hasa  high chance that its customer will return for another stay?
 Q14)  Which channel is mostly used forthe  early booking of hotels?
 Q15)  Which channel hasa  longer average waiting time?
 Q16)  Which distribution channel brings betterrevenue-generatingg deals for hotels?
 Q17)  Which significant distribution channel has the highest cancellation percentage?
 Q18) Doesa  longer waiting period or longer lead time causes the cancellation of bookings?
 Q19) Whether not getting allotted the same room type as demand is the main cause of cancellation for bookings?
 Q20) Does not alloting the  same room as demanded affect adr? 
 Q21) What is the trend of bookings within a month?
 Q22) Which types of customers mostly make bookings?

```

Mainly performed using Matplotlib and Seaborn library and the following graph and plots had been used:
  -  Bar Plot.
   - Pie Chart.
   - Line Plot.
