# Amazon_Vine_Analysis

## Overview 

The data was first filtered to reflect the columns contained in the vine table created earlier. The following code was also used to filter the table to only include rows with 20 or more total votes. 

![filter](https://github.com/msprech/Amazon_Vine_Analysis/blob/13fefaf854597e8e7f5880d905c5ba87e88ec668/Screen%20Shot%202021-12-23%20at%203.26.29%20PM.png)

We then filtered again to include only rows where the helpful_votes column divided by the total_votes column was equal to or greater than 50%. 

![filter2](https://github.com/msprech/Amazon_Vine_Analysis/blob/13fefaf854597e8e7f5880d905c5ba87e88ec668/Screen%20Shot%202021-12-23%20at%203.26.41%20PM.png)






## Results 

* How many vine and non-vine review are there? 

After the data was filtered using the above specifications, there were no vine reviews recorded. The below snippet of code shows the resulting empty dataframe. 

![reviews](https://github.com/msprech/Amazon_Vine_Analysis/blob/13fefaf854597e8e7f5880d905c5ba87e88ec668/Screen%20Shot%202021-12-23%20at%203.26.08%20PM.png)

Non-vine reviews therefore made up all 403,807 remaining reviews. 

* How many vine and non-vine reviews were five stars? 

As there were 0 vine reviews, there were also 0 five-star vine reviews. 242,889 of the non-vine reviews were five stars. 

* What percentage of vine and non-vine reviews were five stars? 

![calculate](https://github.com/msprech/Amazon_Vine_Analysis/blob/13fefaf854597e8e7f5880d905c5ba87e88ec668/Screen%20Shot%202021-12-23%20at%203.25.53%20PM.png) 

Attempting to calculate a percentage of five-star vine reviews resulted in an error as a product of attempting to divide by 0. However, 60% of the non-vine reviews were five stars. 



