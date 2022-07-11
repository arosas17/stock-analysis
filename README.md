# Stock-Analysis

## Overview

A couple want to invest into green energy companies, believing that as more resources are used, green energy will become more in demand. In doing this, this couple has invested in a single company called DAQO New Energy Corp(DQ) without doing any research. Their is concern about diversifying their stocks and was given a list of stacks in order to look at. A VBA Macro was created so that the stocks may be organized and clearer to read so better investments may be made. However, we wanted to make to refactor the Macro to run better so that if the stock list was expanded, it would take less time to obtain the results. 



## Results
![VBA_Challenge_2017_Results](/Resources/VBA_Challenge_2017_Results.png)
![VBA_Challenge_2018_Results](/Resources/VBA_Challenge_2018_Results.png)

Based on the results seen in the images above over the two years of 2017 and 2018, green energy stocks have been doing very well overall. In 2017, all but one stock had a green cell color indicating that those stoack gained value. However, not only did these stocks gain value, but some large gains such as 199.4%, 129.5%, and even 23.1% can be considered a large gain. However, most of the stocks made a loss in 2018. This loss is still acceptable as losses in 2018 is not as large as the gains in 2017. For example, DQ had a large gain of 199.4% in 2017 but had a loss of 62.6% in 2018. Although, it would have been perferable that it would only see positive trends, DQ overall made a profit for anyone who invested in them in the 2017 market. This pattern is shown in many of the stocks with some few exceptions where the trend seem to have an overall decrease in value. The total daily volumes does not actually state too much because most of the volume given in 2018 shows moderate jumps and drops in volume. There are a few stocks that had major movement. These would be ENPH, jumping from a 220,000,000 total daily volume to a 610,000,000 total daily volume, and RUN, from a 270,000,000 total daily volume to a 500,000,000 total daily volume.


### Times to run in orginal code
![VBA_Challenge_2017_unrefactored](/Resources/VBA_Challenge_2017(Unrefactored).png)
![VBA_Challenge_2018_unrefactored](/Resources/VBA_Challenge_2018(Unrefactored).png)

### Times to run in refactored code
![VBA_Challenge_2017](/Resources/VBA_Challenge_2017.png)
![VBA_Challenge_2018](/Resources/VBA_Challenge_2018.png)

As mentioned before, the orginal script was refactored to order to make the Macro run smoother. The images above show that this was acheived by providing a decrease in run time from the original. The run time decrased from about 1.11 seconds to as low as the 0.12 seconds, which is almost a factor of 10. This suggests that the refactored script will run a little less than 10 times faster than the orginal. Now if the number of stocks in the list were to increase immensely, the refactored Macro will be better suited to handle it.  

## Summary

There are a few advantages in refactoring code such as, to make the code more organized and fluid. Refactoring code will give opportunity to make things easier to read. There is also some benefits in getting the code to run better. If the refactored and original Macros are compared, it is noticed that the refactored code has a faster run time than the original. It makes close no difference in time with the list at the moment, but if the list was ballooned to size that dwarfs its predecessor, the difference in time could be noticeable.

As much as these benefits from refactored code would help; refactoring does come with some costs. Errors may occur when refactoring a Macro which could make it time consuming. In this refactor, even though the edits were simple individually, many errors occurred when it was being performed making it somewhat a time consuming project. This can be accredited to the idea that working with a new code  (even a code you a somewhat familiar with) can be a difficult task and should obtain good understanding of the code when refactoring. A person would also have to take into account if the Macro would be utilized enough to be worth refactoring. 
