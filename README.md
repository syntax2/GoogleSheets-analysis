# hospital-charges-analysis
we will have a large dataset that involves hospital treatement charges form acrooss the states in the united states,
using this raw data we will prepare a report that shows which are the cheapest health providers for a particular type of illment across the country.
we will accomplish in google sheets using the feature such as formatting , filtering, sorting,conditional formatting with and emphasis on the quality and the persentability of the reports.
We are going to analyse this "raw" dataset and prepare a "report" having the list of providers treating a specific ailment in a particular state of USA. Subsequently, we will rank providers by the cost of treatment.

Such a "report" will be extremely useful to government agencies and patients across the state. Instead of analysing the entire dataset, they will now use this report to find the cheapest healthcare provider in their city. Think of this report like a sorted "Yellow Pages" or "Dictionary".

first task:
we will find out how much it cost a person who lives in a certain area to take treatment in a specific area. (select providers treating chest pain in california)
- create a filter then filter by value and select 'chest pain' in DRG Definition and 'ca' in provider state.
second task:
now we have to find the chepest and most expensive provider from the result we get from the previous step.
-when we apply sort but it will not give us the desired result because the $ sign is there so first we have to find and replace the '$',
go into Edit > find and replace 
then sort 'Average Covered Charges' 
RESULTS:
- chepest provider in California for chest pain is "MADERA COMMUNITY HOSPITAL"
- EXpensive provider in California for chest pain is "DOCTORS MEDICAL CENTER"

you know state is a very large region so i want to know who are the cheapest and most expensive health care provider in my city.
- select the entire data set and Data > sort by range > sort by header , here you can apply layer of soting i.e second sort will apply on the result of first sort.

-> now we will createa a new sheet with the results we find above and make that data tidy by deleting the unnecessary colums.
task: in which area medicare will pay me more
- the amount showed in sheet can be more simple and easy to read if we remove the decimal (bcz they will not be a factor in decision makinh).
 we will use shift + ctrl + down arrow and then reduce the number of decimals.
 
 
