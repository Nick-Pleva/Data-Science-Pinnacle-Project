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
Here are the graphs that we created. One is for rating over time for TV shows, and one is for rating over time with movies. Each graph displays a higher frequency of ratings when the time gets closer to the year 2020, and each graph shows more rated R movies and shows. There is also a noticible dip right when COVID started, which makes sense. We will now use these graphs to cultivate our first machine learning model: linear regression.

<img width="850" height="507" alt="image" src="https://github.com/user-attachments/assets/4d390910-3ede-493d-9743-166a043f8160" />
<img width="850" height="507" alt="image" src="https://github.com/user-attachments/assets/d1834997-371e-42f1-a0c5-81a002229f22" />

We want to try and predict the ratings of TV shows and movies. The question we want to answer is, "Is there a correlation between the rating of a movie and both it's title and genre?". We want to use the "listed in" and the "title" columns to try and predict the "ratings" column. 

We started off with getting a count of how many different themes there were. If there were too many, then the model might not do as well because there wouldn't be enough correlation to base it's prediction off of. If there were too little, then there would not be a correlation to keep track of, but for the opposite reason. We took a count and there was about 20-25 genres for movies and same for TV shows. This is enough for a correlation. 

