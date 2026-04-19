# Data-Science-Pinnacle-Project

### Check in 1:
##### \- What has been done?
  Within our project so far, it has been about organizing our data so that we can easily implement what we want to accomplish, along with visualizing the data so we know where to go from here. 
  
  We started with putting our data into a pandas dataframe. This way, we can manipulate it more easily. Then, we took out all of the columns that were not relevant, and removed the null values. It removed noise in our dataset, and now we have a clean, organized dataset that we can use for our graphs. 

  With our graphs, we wanted to make two graphs that displayed the rating vs TV show, and rating vs Movie. These are the main data columns we want to focus on, and viewing them in graph form will help us understand the data. 

##### \- What is next?
Next we want to look over what the graphs displayed and figure out what specifically we want to analyze. We also are also going to start figuring out exectly how we will be using the data later on when making the various ML tests.


### Check in 2:
#### \- What has been done?
Here are the graphs that we created. One is for rating over time for TV shows, and one is for rating over time with movies. Each graph displays a higher frequency of ratings when the time gets closer to the year 2020, and each graph shows more rated R movies and shows. There is also a noticible dip right when COVID started, which makes sense. 

<img width="850" height="507" alt="image" src="https://github.com/user-attachments/assets/4d390910-3ede-493d-9743-166a043f8160" />
<img width="850" height="507" alt="image" src="https://github.com/user-attachments/assets/d1834997-371e-42f1-a0c5-81a002229f22" />


#### Logistic Regression

After a bit of thought we decided to change our idea of using linear regression to using logistic regression to fit the question "Does the duration or number of seasons a piece of media have an influence from what its rating is?". Logistic allows us to look at a random duration and shows us what the probability is of finding a movie/show with each rating. There are a few things that might need to be tuned up with the code for this, but as of right now the graphs of the ratings crossed with the duration look pretty good, showing the trends of the ratings from a shorter duration to longer duration. By the looks of it, it is much better at doing this with movies because the duration is in minutes and varies a lot. Meanwhile, shows is by season, so the more seasons there are, the less shows you will find, along with the range only being around 1 to 18 seasons in the data.

<img width="846" height="545" alt="image" src="https://github.com/user-attachments/assets/00118978-f78d-4a8e-8e3b-005a3d5b6681" />
<img width="855" height="545" alt="image" src="https://github.com/user-attachments/assets/26d008d1-8061-49fa-99f2-8f7f2695a849" />


#### Random Forest
