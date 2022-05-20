# The Silver Tsunami - Pewlett Hackard Analysis

## Project Overview
With a significant portion of the work force in the age of retirement upon the horizon, create a report that accounts of the labor needs cause by a large retirement group. 

## Resources:
- Data Source: .csv listed in initial data folder
- Software: PgAdmin 14, VS Code 

## Results
Utilizing SQL (Postgres), these queries revealed a dire labor necessity with over 72k employees retiring soon. 

<img src="https://github.com/e-sycheung/Pewlett_Hackard_Analysis/blob/main/images/unique_titles.jpg" style=" width: 480px ; height: 380px">

- Creating a query of possible retirement. This shows which employees are retiring and in which departments help with planning the resources on the hiring ramp up. However, there was a process, since originally the query outputted several employees’ multiple times. A sort was created to ensure that we only got one entry per employee number.   

<img src="https://github.com/e-sycheung/Pewlett_Hackard_Analysis/blob/main/images/me.jpg" style=" width: 500px ; height: 320px">


- Creating a query of mentorship eligibility. This gave us the number of count of staff that can participate in the mentorship. The hope is to be able to plan out the growth of current employees to mitigate the obstacles that come with a change like this.

<img src="https://github.com/e-sycheung/Pewlett_Hackard_Analysis/blob/main/images/sidebyside.jpg" style=" width: 480px ; height: 280px">

- Creating a count by titles. This table allows insight into what positions the recruiters in the company will start needing to source for. 
This graph below shows the potential need for the company. Then next graph shows the count of the mentorship eligibility which gives an idea of the severity lay on the mentors. 

### Further Inquiries

<img src="https://github.com/e-sycheung/Pewlett_Hackard_Analysis/blob/main/images/birthorder.jpg" style=" width: 480px ; height: 350px">


- A query was created to sort the retiring list by birth year to see exactly which employees will be retiring first (born in 1952) and to address those with highest priorities. 

<img src="https://github.com/e-sycheung/Pewlett_Hackard_Analysis/blob/main/images/newq.jpg" style=" width: 280px ; height: 320px">

- Then a count was performed. These are positions that will need to be addressed with the highest priority. 

