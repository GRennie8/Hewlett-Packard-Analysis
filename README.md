# Pewlett Hackard Analysis

## Overview of analysis

For this challenge I have been working with Pewlett Hackard as they are due to experience a "Silver Tsunami" in which a large number of employees are set to retire after many years with the company. Instead of having a large chunk of their workforce retiring, they want to introduce a mentoring program: experienced and successful employees stepping back into a part-time role instead of retiring completely. Their new role in the company would be as a mentor to the newly hired folks. 

The purpose of this analysis is to determine the number of retiring employees per title, and identify employees who are eligible to participate in the mentorship program. 


## Results

 - There is a significant number of Senior level employees expected to be retiring soon. 50,842 are expected to retire out of the 72,458 retirees.
 
<img width="226" alt="Screen Shot 2022-06-20 at 7 15 52 PM" src="https://user-images.githubusercontent.com/104115586/174700322-0c7ec91d-60ff-44d0-891b-072b966d4dda.png">

- Similarly, Engineers (Senior and non-Senior) make up nearly half (48.6%) of all employees expected to retire soon.


- There is an issue with the number of employees eligible for the mentorship. There are only 1,549 eligible for the mentorship program compared to the 72,458 employees eligible to retire, which is just over 2%.

The table below shows the number of retirees to the number of employees who are eligible to be mentors.

<img width="420" alt="Screen Shot 2022-06-20 at 7 22 44 PM" src="https://user-images.githubusercontent.com/104115586/174700295-9dc39096-9651-4cc0-a31d-0d2835ddb80e.png">


<img width="377" alt="Screen Shot 2022-06-20 at 7 21 33 PM" src="https://user-images.githubusercontent.com/104115586/174700313-8d021823-92d4-4c17-926d-5e3acc96f4bc.png">

## Summary

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

72,458 roles need to be filled.

### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

There are 1549 employees qualified to be mentors. This means there would be 46 employees for every one mentor. Far from ideal! One suggestion to rectfiy this would be to alter the search parameters within the "mentorship_eligibilty". Currently, it is searching for all employees born in 1965, ten years younger than the employees at retirement age. A small change to include employees also born in 1964 yields a much higher number of employees eligible to be mentors.

Changing the birthdate to 1964 increased the number of mentorship-ready employees from 1549 to 19,905.

![Screen Shot 2022-06-20 at 8 46 24 PM](https://user-images.githubusercontent.com/104115586/174705617-49e6fcfe-2b09-40a6-9038-3c9984890190.png)

New count:

![Screen Shot 2022-06-20 at 8 45 12 PM](https://user-images.githubusercontent.com/104115586/174705585-e39dd790-bd8f-4ff2-b3a2-0625d166586f.png)

Making this change to our table would give Pewlett Hackard the oppurtunity to present this idea to much more employees, thus requiring less uptraining and outside recruitment. If all employees agree to be mentors, there could be one mentor for only 3 employees.





