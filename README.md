# stock-analysis
## Background
Steve, a recent finance graduate, is helping his parents with their investments. In particular, his parents have decided to invest in green energy but have done very little research. Using VBA, we helped Steve analyze stock data from Dago New Energy Corporation (DQ), along with data from a few other green energy stocks. The data analysis sheet that we completed for Steve worked well, but there were a few things that could be improved. 

### Purpose
The purpose of this assignment is to refactor the macro that we previously built to improve it's performance. 

## Original versus Refactored Script
One of the major changes we are making to the code to improve is is getting rid of a nested loop. Three output arrays are used instead. 

![image](https://user-images.githubusercontent.com/105028515/174450469-bbf484a0-b2a2-43e2-85ff-13b9683c47dc.png)

## Results
The efficiency of the code was determined by measuring how long it took to analyze the data. Below are time screenshots from the original script and refactored script for the year 2017 and 2018. As you can see, the refactored script ran faster than the original script for both years.

### Original Script - Run Time
![2017RunTime_00](https://user-images.githubusercontent.com/105028515/174449916-49982ea4-26f1-45f0-8c5a-165ea25ac3eb.png)
![2018RunTime_00](https://user-images.githubusercontent.com/105028515/174449920-cb03267f-b8bd-4bf5-8822-20e6c83b9a59.png)

### Refactored Script - Run Time
![VBA_Challenge_2017](https://user-images.githubusercontent.com/105028515/174449896-7b96af74-4e35-4e5b-ae12-c64f4f70bb10.png)
![VBA_Challenge_2018](https://user-images.githubusercontent.com/105028515/174449908-a55abc04-393b-425c-8958-3bc7c0c8fdb7.png)

## Summary
Refactoring code refers to editting code to improve it in someway without changing it's behavior. In many cases, refactoring code is advantageous as it "cleans up" the code, making it easier to read, understand, and maintain. This process usually makes the code more efficient as well. However, it can sometimes be a long process to refactor code, and if one is not being careful or does not fully understand the original code, they run the risk of breaking the code and even entire macro entirely. In the above example, refactoring our code for Steve resulted in not only a cleaner code, but it also became more efficient as seen in the screenshots of the run time in the results section above. Comparatively, the original code took much less time to generate as opposed to the refactored code which in total took the time of the original code plus the time to refactor. 
