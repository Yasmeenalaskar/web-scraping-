# web-scraping-
 Extraction and copying  data from a website into a structured format using web-scraping technique.
 ![img4](https://user-images.githubusercontent.com/59575205/123017743-e21d5500-d3d5-11eb-849c-0185b55a33a0.png)

 # Project Objectives:
 Google play store is brimming with a lot of untapped data with a prominent potential to drive app-making businesses to success. Also meaningful and actionable insights can be drawn for developers to work on and capture the google market!. Here, I explored using data science technique which is web scraping to retrieved data from one of the largest app markets in the world, the Google Play Store. Furthermore I tried to explore google play data to find answers to questions of my interest which are:
 - 	Do all the applications in the Top Charts have a rating higher than 4 stars?
 - 	What is the category that has the most paid apps ? What is the category that has the most free apps?
 - 	What’s the most frequent category of applications in Top Charts page?
 - 	What is the app company in Top Charts page that got the most number of downloads? in what category?
 - 	What is the app company in Top Charts page that got the best rate? in what category?


# Data Collection :
By using Web-scraping technique which is extraction and copying of data from a website into a structured format using python. Users download apps for various usage purposes. For that reason I scraped top charts since it shows the most apps preferred by users so I can study these apps’ features that made them appear in the top charts. I scraped 384 apps data and fill them into data frame with applying some analysis and visualization techniques.
## Data overview
Thw data consists of a 384 of rows, each row represent an application in top chart page that has several feature , which is :
•	Name
•	Category
•	number of rates
•	stars
•	number of downloads
•	Price
•	Company name
![Img5](https://user-images.githubusercontent.com/59575205/123016483-5acee200-d3d3-11eb-9f1b-687da32a833f.png)
Attribute | Description
------------ | -------------
Name | Application name (qualitative nominal)
Category | Category the app belongs to (qualitative nominal)
number of rates | Number of users  rating  the app (quantitative ratio)
stars | Overall user rating of the app(qualitative ordinal)
number of downloads | Number of user downloads/installs for the app (quantitative ratio)
Price | Price of the app (quantitative ratio)
Company name | Application developer (qualitative nominal)


# Some Data Analysis 
**Do all the applications in the Top Charts have a rating higher than 4 stars?**
The answer of question is no , as observed applications in the data that scraped from google play most of them higher than 4 stars 213 (73%) out of 290 application in top chart but not all of them as shown in the graph below. So the applications in google play don’t need to be more than 4 stars to be in top chart as there is an applications less than 4 in it.
<img width="602" alt="img6" src="https://user-images.githubusercontent.com/59575205/123016900-450dec80-d3d4-11eb-9599-6378adb0d5e4.png">

**What is the category that has the most paid apps ? What is the category that has the most free apps?**
<img width="400" alt="img6" src="https://user-images.githubusercontent.com/59575205/123017004-78e91200-d3d4-11eb-8214-142538993b51.png">
<img width="400" alt="img6" src="https://user-images.githubusercontent.com/59575205/123017006-7a1a3f00-d3d4-11eb-9df8-de7d0f5c0616.png">

The graph that shows license type and count describes the number of top charts apps that are paid and free. The paid apps in the top charts are 100 app. However free apps are 189 so we notice that most apps in the top charts trends to be free. On the other hand, the second graph shows apps category and count of license types(free or paid) i.e. each  category is divided into two bars which represent license type count .You can notice that entertainment category has the most free apps in the top charts while education category has the most paid apps in the top charts. While other categories differ between free and paid in different proportions

**What’s the most frequent category of applications in Top Charts page?**
![img10](https://user-images.githubusercontent.com/59575205/123017255-e1d08a00-d3d4-11eb-9e53-e81806d679c3.png)
From this bar chart graph, you can notice that entertainment apps are the most frequent in the top charts with 24 apps. The categories that came after entertainment in the top charts as the most frequent are action, education and puzzle with 17 apps for each. 

You can find the rest of the analysis in this shared document :

## Future work :
Build machine learning models that helps decision makers to decide whether the app they may developed will be downloaded by the expected users or not (Add more features and data)
