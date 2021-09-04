# Stock Analysis

### Overview

##### The purpose of this analysis was to compare stock performance in recent years and outpout the data in a communicable manner. During the challenge, code that was written during the module was refactored so that Steve can apply the macro to a larger data set in the future. 

### Results

![image](https://user-images.githubusercontent.com/88811124/132108261-ac23cbe8-336f-4659-bb9c-715612e91ddf.png) ![image](https://user-images.githubusercontent.com/88811124/132108271-32def49b-8f7f-4e49-809b-5881f5ba56c5.png)

##### The tickers I analyzed performed much better in 2017 than they did in 2018. 
##### After refactoring my code, the code ran in roughly 1/3 of the time as it did previously.

![image](https://user-images.githubusercontent.com/88811124/132108540-7f6e55f5-fd4c-45ff-a36e-40f83d18765a.png)

##### By creating a tickerIndex variable and three output arrays, a nest loop was able to be avoided. This way, the entire data set for the given year wouldn't have to be looped through for each ticker, only once. 

### Summary

##### The advantages to refactoring code include cutting down on runtime and simplification for the purposes of debugging and readability. The only disadvantage of refactoring code would be the time it requires, and if the refactoring is worth that time. In this particular example, the refactor was certainly worth it. The issue with the original script is it's scalability. As the data set grows, the runtime increase substantially. Refactoring the original script made the code much more applicable for multiple situations as opposed to our limited data set. 

