# Stock Analysis

## Overview of Project
Analyzing stock data to determine trends in the market. 

### Purpose
The purpose of this analysis is to understand how select stocks performed and ultimately apply this code to the entire stock market over the last few years. 

## Results
-	In 2017, the majority of stocks yielded a positive return with DQ yielding the highest return at 199.4%.

-	Using the original script, we can see that the execution time for 2017 was 0.2578125 seconds whereas the refactored script was able to run in .046875 seconds. 
-	In 2018, only 2 stocks yielded a positive return, ENPH and RUN. Comparatively, DQ had the worst return rate that year at -62.6%. 
-	Using the original script, we can see that the execution time for 2018 was .2578125 seconds whereas the refactored script was able to run in .046875 seconds. 

## Summary
### Advantages and disadvantages of refactoring code
  - Advantages: As noted above, refactoring code allows us to run the script faster while still maintaining the same functionality, ultimately improving the quality of the code. Refactoring can also help to reduce duplicate code and make the script easier to understand.
  - Disadvantages: While refactoring the code you may create bugs that didn’t exist before and can be time consuming to understand/correct. 
### Advantages and disadvantages of the original and refactored VBA script
  - Advantages/Disadvantages of the original script: The original script was still able to fulfill the functionality we needed to analyze those 12 stocks and no bugs were encountered when running the script. However, the code ran slower and likely cannot be applied to the entire stock market or will take a long time to execute unless it is refactored. 
  - Advantages/Disadvantages of the refactored script: The refactored VBA script was able to run faster and can be applied to more than just the 12 stocks we were analyzing. However, additional bugs were created when refactoring the code so it took more time in the moment to correct so that the code would run successfully. 
