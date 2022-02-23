## Overview:
This phase 1 project is intended to act as a presentation for Microsoft to assist their entry into the movie industry.

### Here is a link to my finished jupyter notebook:
(https://github.com/DtonesOD1/dsc-phase-1-project-v2-3/blob/master/student.ipynb)

### Here is a list of references I used to help in my coding:
Suppressing scientific notation:
https://www.tutorialspoint.com/how-to-repress-scientific-notation-in-factorplot-y-axis-in-seaborn-matplotlib ,               https://stackoverflow.com/questions/36780948/seaborn-matplotlib-how-to-repress-scientific-notation-in-factorplot-y-axis          

Beautiful Soup tutorial: www.youtube.com/watch?v=XVv6mJpFOb0

Converting integers: https://stackoverflow.com/questions/32464280/converting-currency-with-to-numbers-in-python-pandas

Removing outliers on boxplots: https://stackoverflow.com/questions/22028064/matplotlib-boxplot-without-outliers

Ignoring float error warning: https://stackoverflow.com/questions/12041982/numpy-floatingpointerror-invalid-value-encountered-in-subtract-not-reproducib

Agg Functions: https://datascienceparichay.com/article/pandas-groupby-median/

Dropping duplicates: https://stackoverflow.com/questions/23667369/drop-all-duplicate-rows-across-multiple-columns-in-python-pandas

Creating subset dataframes: https://stackoverflow.com/questions/19237878/subsetting-a-python-dataframe

Regression plots and other seaborn visuals: https://seaborn.pydata.org/tutorial/regression.html , https://seaborn.pydata.org/tutorial/function_overview.html
   
   
   ## Overview:
   
   Tasked with making 3 recommendations to Microsoft which was achieved by importing data, cleaning it, then visualize and interpret it.
   
   ## Business Problem:
   
   The purpose of this presentation is to solve the problem Microsoft has of not knowing where to begin within the movie industry. 
   To help solve these problem I made a few hypotheses and ran the data accordingly, they were:

    -Is there a correlation between a higher budget and higher box officer earnings?
    -Is there a correlation between a higher number of theater showings and higher earnings?
    -Does a particular genre of movie tend to have a better return on investment than the others?
    -Do ratings play a role in how much money a movie will make?  
    
   ## Data:
   
   The data was imported from IMDB and web-scraped from The Numbers.
   Cleaning involved removing NaN's, adding and dropping colums, converting objects to floats/integers, removing duplicates, etc.
   
   The data was then presented in dataframes and some basic functions were applied to show counts, median/means and ROI.
   From there visuals were created that further highlighted the data that was used to make the conclusions. 
   
   ## Modeling:
   
   Data was then used to create a table of most popular genres, high and low rated movies by genre and box office/ROI returns by genre
   
   ## Evaluation:
   
   After gathering some simple data and taking a pragmatic approach to analyze and interpret it, I believe the key to Microsoft's success lies within its      ability to afford what the more common movie makers cannot. Microsoft can give themselves their best chance at premium earnings at the box office by        investing more into the production budget and the number of theaters their movies are released in.

   In the beginning of the presentation I hypothesized that higher budgets and theater counts earn more at the box office and from what we learned that        seems to be statistically true. I also asked if there was a particular genre that tended have better returns and whether ratings had any effect on those    returns. What we say is that ratings are distributed pretty evenly, except for the Horror genre. When looking at the horror genre we see that it yielded    fantastic returns despite the fact that they were far more likely to garner poor ratings.   
   
   ## Conclusion:
    
    An Action movie with a budget of over 200 million dollars and released in a minimum of 4,100 theaters.
    
    A Musical with a budget of 100 million and released in a minimum of 3,500 theaters.
    
    A horror movie with a budget of approximately 20 million and released in approximately 3,200 theaters.


   
   ***
   
   ## My Files in this Repo:
   #### Zipped Data: 
   
   The data from IMDB title and ratings files were used
   #### README: 
   
   Containing project info and sources
   
   #### Student.ipynb:
   
   The jupyter notebook containing the code and presentation
   
   #### Phase1Project.pdf:
   
   A slide show of the presentation
   
   
   
   
