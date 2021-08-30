# Progressive Web Application -- Budget Tracker
## User Story
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 

## Acceptance Criteria
* GIVEN a budget tracker without an internet connection
* WHEN the user inputs an expense or deposit
* THEN they will receive a notification that they have added an expense or deposit
* WHEN the user reestablishes an internet connection
* THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated

## Deployed App 
https://ltv-budget-tracker.herokuapp.com/

## Offline Functionality
*Simulating offline network connection and created entries:*
![image](https://user-images.githubusercontent.com/81693557/131270643-8d242ad9-1604-4651-9f9e-0b43209be49d.png)
*Entries stored in IndexedDB:*
![image](https://user-images.githubusercontent.com/81693557/131270659-6de074bd-43ed-420e-9b69-fba9357c2458.png)
*Refreshed page shows entries posted once user is back online:*
![image](https://user-images.githubusercontent.com/81693557/131270795-4119bf21-2af7-4f43-9159-1cd9cbe87d83.png)


## Manifest Sample
![image](https://user-images.githubusercontent.com/81693557/131270749-b90835a7-cbf1-4fa6-9194-15943440f13d.png)



