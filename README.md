# Hypothesis-testing
Descriptive Hypothesis testing 
!DOCTYPE>
<html>
	<head>
      <title> AUTOLIB EXPLORATORY DATA ANALYSIS </title>
     </h1>
     <h1> HYPOTHESIS TESTING </title>
      <body>
        	<p>
Hypothesis testing is the systematic way of selecting samples from a group or population with the intention of making a detemination about the expected behaviour of the entire population

</p>
<p> 
Autolib is a car renting organisation. As the data scientist of Autolib company I am investigating the claims about the  blue car which is one of the brands of cars that is regularly rented out
</p>
       		 <p>
We will use python language and the pandas library to analyse the dataset collected in order to derive our solutions.
</p>
<p>
Problem Statement
We will be using the data collected in some few months from one of the company's outlets

Null Hypothesis
* Blue cars taken more during the weekends

Alternate Hypothesis
*Blue cars are not taken more during the weekends
This information is require so as to identify whether to bring in more blue cars from other stations during the weekends or not.
</p>

<p>
The link to the dataset we will be using is http://bit.ly/DSCoreAutolibDataset.It is a continuos dataset with information being updated everyday after the daily report
The data contains the following information;
Column name - Explanation
Postal code - Postal code of the area(in Paris)

Date - Date of the row aggregation

n_daily_data_points - number of daily points that were available for aggregation that day

DayOfWeek - Identifier of weekday (0:Monday- 6:Sunday)

Day_type - weekday or weekend

blueCars_taken_sum - Number of blue cars taken that date in that area

Bluecars_returned_sum - Number of blue cars returned that date in that area

Utilib_taken_sum - Number of Utilib taken that date in that area

utilib_returned_sum - Number of Utilib returned that date in that area

Utilib_14_taken_sum - Number of Utilib 1.4 taken that date in that area

Utilib_14_returned_sum - Number of Utilib 1.4 returned that date in that area

Slots_freed_sum - Number of recharging slots released that date in that area

Slots_taken_sum - Number of recharging slots taken that date in that area
</p>

<p>
I will test the data by using a stratified sample and the Z-test because I want to analyse enough samples so as to make sure there is minimal error.The alpha level is 0.05.
</p>

<p> After the test I realised that the Blue cars were mostly rented out on monday and least in Wednesday. Weekends strarting from Friday they were averagely rented.
Incase the company neede to bring in more cars they should think of bringng them in on Mondays.
</p>

      </body>
</html>
