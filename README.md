# Twitter-Analysis-of-NG30daysoflearning
<img width="683" alt="intro" src="https://user-images.githubusercontent.com/105246702/177745974-32eeac96-3640-4257-9fcf-464492e18c2a.png">

# Introduction
This is a project to show what I learnt in Day 15 and 16 of the NG30daysoflearning. "Storytelling with PowerBi by [Paul]()"

# Problem Statement
[TheOyinbooke](https://twitter.com/TheOyinbooke/status/1523694387770789888?s=20&t=cMFdNmB-FERzi_jbe14iLw) and friends decided to set up a training NG30daysoflearning for the Nigerian University students affected by the ongoing ASUU strike. Their goal was to equip the students with the necessary skills, needed to kickstart a carrer in the Data world.

Few days ago I received a mail from one of the organisers, in which I was told to analyse the twitter engagement of the programme and draw out necessary insights that can be used to answer the big question **Was this programme a Success**

# Data Sourcing
Dataset was provided in two forms, of which any can be used
- [Jupyter notebook python file](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Twitter%20Data%20Web%20Scrape/30DLTweetsScrape.ipynb)
- [Csv file](https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/blob/main/Twitter%20Data%20Web%20Scrape/30DLTweets.csv)

Data was extracted from the web into PowerBi

# Data transformation
Data was cleaned in PowerQwery
- A column that contained both date and time from the raw data was split into two seperate columns
- The date column was transformed to get Day name which was then sorted by day number
- The time column was transformed to get the hours 
- Datatypes were validated and every other details was checked accordingly

# Data Visualisation
<img width="320" alt="front page" src="https://user-images.githubusercontent.com/105246702/177770814-898c5ab3-d8d0-48e0-8ce0-67cbba6cb0c8.png">

[Interact with report here](https://app.powerbi.com/view?r=eyJrIjoiMWRhNWViZWUtYTM4MS00NTVhLWI2YmMtZWNhMjYyNDA2OGE0IiwidCI6IjBjZmU3YmI2LTZhMzUtNDM4OS1hODQ4LTU1ZTdjZjZlN2NmMSJ9)

# Findings

### Total Engagement
<img width="278" alt="total insights" src="https://user-images.githubusercontent.com/105246702/177759683-cf25493f-0ba5-40b7-a8e3-31cf3f3818fe.png">


### 7pm time with highest engagement.
- **7pm** had the most activity with 52 tweets followed by 12pm at 49 and 11am at 46. This begs the question, Why was the activities higher at this time,a futher dive into this can help organisers make decisions as to whats the best time to have classes and more
<img width="294" alt="tweet hours" src="https://user-images.githubusercontent.com/105246702/177759745-926c0e65-7ae7-4923-9a4e-3a99dc2f931d.png">

### 7 days in a week and Wednesday is the most active day
- **Wednesday** topped the list with 155 . One will wonder if something special happens on this day, or if the organisers do something on this day that should be taken note of. Our dataset can't answer this questions but a survey carried out by the organisers can help answer it
<img width="137" alt="tweet day" src="https://user-images.githubusercontent.com/105246702/177759787-f3b08a8f-371e-4793-894e-50d23c16a863.png">


### Just 1 actual learner in the top 3 active participants
- Out of the Top 3 active participants only 1 is an acutual learner who is no 2 on the list, 
<img width="145" alt="top 3 active users" src="https://user-images.githubusercontent.com/105246702/177759860-3ab49c57-eeff-49b7-87a0-a9f0478c21b1.png">

- a futher research into this category showed that out of Top 20 participants, about 12 are actual learners. Why are the actual learners not topping this category?. From my research one would wonder maybe because of their audience size thus less engagements on their posts. 
<img width="149" alt="top 20 active participants" src="https://user-images.githubusercontent.com/105246702/177759951-499f5fe8-0dbf-47dc-a5b3-5ab82b20ea91.png">


### Lagos, a perfect location for physical gatherings
- In case of a data hangout or creation of a physical Hub, **Lagos** will be the go to location, most of the participants are located here.
- Also **USA** can be seen on the chart, showing the training went beyond the shores of Nigeria.
- 
 *In the dataset location had 71% validity, blank spaces and Nigeria was excluded so as to get a rough visualisation of this category*
 <img width="131" alt="location" src="https://user-images.githubusercontent.com/105246702/177760019-aec5f0ad-c3ec-458d-b627-506e4505bcd1.png">


### Announcements tweets getting most attention?
- A pattern can be seen from this category, in the most liked tweets, 9 are announcements except the first tweet which was by a participant and for the most retweeted all 10 are announcements.
<img width="322" alt="retweet" src="https://user-images.githubusercontent.com/105246702/177760070-58b20b99-8cae-4f59-a158-69a6f2c71dc7.png">



# Recommendations
- Organisers should carry out a survey to get clearer insights why Wednesday and 7pm are topping their various categories, this can be used to make more informed decisions about what time to hold classes and time they can get most of the attention of the participants
- Ways should be crated to showcase the actual participants posts and work to a larger audience, this will give room for more opportunities for them and collaborations with other Data Training Organisation
- Posts of the actual learners should have higher likes and retweets as this will help people know the participants are actually learning. An avenue should be created to help the learners showcasing their work reach a higher audience


 
