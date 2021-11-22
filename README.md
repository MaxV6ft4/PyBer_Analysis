# PyBer Analysis

## Overview
In this project I have performed analysis the ride-sharing data specifically for each type of city.  To do so, I created a summary dataframe with an index containing the three city types (rural, suburban and urban), and a multiple-line graph displaying the total fares for each city type on a week-to-week basis for the months of January - April.

## Results

![Summary DataFrame](https://github.com/MaxV6ft4/PyBer_Analysis/blob/main/Screenshots/Summary_DF.png)

 - not surprisingly, urban cities contained the largest amount of rides, drivers and total fares, as well as the smallest average fare both per ride and per driver, while rural cities contained the inverse: the smallest amount of rides, drivers and total fares, and the largest average fare for both ride and driver.
 - the total number of rides for rural cities was 125, 5% of the grand total.
      - this was 500 less than the total number of rides for suburban cities (625, 26% of the grand total) and 1500 less than the total number rides for urban cities (1625 and 68% of the grand total).
 - the total number of drivers for rural cities was 78, 3% of the grand total.
      - this was 412 less than the total number of drivers for suburban cities (490, 16% of the grand total) and 2327 less than the total number rides for urban cities (2405 and 81% of the grand total).
 - the total amount of fares for rural cities was $4,237.93, 7% of the grand total.
      - this was $15,028.40 less than the total amount for suburban cities ($19,356.33, 30% of the grand total) and $35,526.45 less than the total amount for urban cities ($39,854.38, 63% of the grand total).
 - the average fare per ride for rural cities was $34.62, $3.65 greater than the average fare for suburban cities ($30.97) and $10.09 greater than the average fare for urban cities ($24.53).
 - the average fare per driver for rural cities was $55.49, $15.99 greater than the average fare for suburban cities ($39.50) and $38.92 greater than the average fare for urban cities ($16.57).

![Total Weekly Fares By City Type](https://github.com/MaxV6ft4/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.jpg)

 - for urban cities, the total weekly fares started at just under $1700 at the beginning of January, then steadily increased through February and reached its high point on March 10 ($2470.93).  The price remained in the $2000 range for the rest of the month, except for a slight dip in the last week, before rebounding to just over $2400 in early April.
 - for suburban cities, the total weekly fares began at around $720 at the beginning of January, increasing to a high of just under $1220 in the middle of the month before decreasing through early February, at which point the fares rebounded and drastically increased to $1412.74 in the last week.  Then the price slammed to just below $1000 within one week, followed by a dull March where the price remained between $900-$1100.  It fell to just about $800 in the beginning of April before rebounding to late February highs towards the end of the month.
 - for rural cities, the total weekly fares began at around $190 at the beginning of January, zigzaging its way through the month before reaching a high of $333.08 on Feb 3, at which point the price dipped to a low of $95.82 in the middle of the month, only to rocket to $1412.74 just before the end of the month.  In March, the price hovered in the $300 range until the end of the month, where the price propelled to a yearly high of $500.  The price then decreased in April, settling at around $300 and remaining that way for the rest of the month.
