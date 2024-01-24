# Aerofit : Descriptive Stats & Probability
## Problem Statement:
Leveraging the customer data collected by Aerofit consisting of the Gender, Age, Income, Weekly Usage, Fitness, Marital Status and Miles run on treadmill to identify characteristics which make the customer buy a particular treadmill out of KP281, KP481 and KP781 in the increasing order of expenditures. Further providing recommendations of treadmill for future orders/customers based on their profile.

* Tech Stack: Python, Applied Statistics, Pandas, Matplotlib, Seaborn, Data Cleaning, Data Visualization
## Recommendations and Customer Profiling
### Customer Profiles for KP781
1) Only people having incomes greater than 70k have run over 220 miles and all of then use KP781.
2) Recommend KP781 if one or more conditions are satisfied along with a necessary condition of Income > 70000:-
    - Education Level >= 18
    - Usage days > = 5 
    - Fitness Levels = 5 
    - The person runs more than 150 miles(80% of them use KP781)
3) Never Recommend KP781 if one or more of these conditions are satisfied:-
    -  Education Levels < 14
    -  Fitness < 3
    -  Age < 20
    -  Income < 45000
    -  Miles run < 50

### Customer Profiles for KP281:

1) Women having incomes below 70k and age > 40 
2) Customers having income in range 60k-70k and usage days=3 
3) Customers having income in range 45k-50k and usage days=2 
4) Customers having income in range 35k-45k and usage days=4 
5) Customers having income in range 50k-60k and usage days=4
6) Customers with Fitness=4, age closer to 40 and income 50k-60k
7) Customers with Education Level=16, Age>32 and income 45k-50k
8) Customers with Education Level=16, Age>45 and income 60k-70k
9) Customers with Age in 25-30 and 35-40 having incomes in range 35k-45k 
10) Customers with 40+ Age and 60k-70k income
11) Women with incomes < 35k and whose miles run < 105 
12) Customers with usages=5, incomes in range 35k-45k and who run more than 140 miles
13) Customers with Fitness=5, incomes < 70k and Incomes in 45k-50k
14) Customers with Education level=15 having incomes less than 35k
15) Customers with Usages=3, miles run < 70 and Age>40
16) Customers with Usages=2 and Age between 25-30

### Customer Profiles for KP481:

1) Women having incomes below 70k and age between 32-37 
2) Customers with age < 25, incomes in range 50-60k and the miles run is in the range 100-150
3) Customers with Fitness=4, age in range 25-32 and income 50k-60k
4) Customers with Education Level=16, Age< 22 and income 45k-50k
5) Customers with Education Level=16, Age< 35 and income 60k-70k
6) Customers with 35-40 Age and 60k-70k income
7) Women with incomes < 35k and whose miles run >105
8) Men with incomes 60k-70k and who tread in range 100-150 miles 
9) Customers with Fitness=4, incomes < 45k-50k and who run more than 100 miles
10) Customers with Education level=13 having incomes in ranges 45-60k
11) Customers with Usages=2 and Age>40
