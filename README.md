# Social Buzz Project
This project is from the Accenture North America job simulation. I hypothetically worked with team members to analyze social buzz data and identify their top 5 content categories with the largest popularity score.


# About the company 
Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. They left in 2008 and both met in San Francisco to start their business. They started Social Buzz because they saw an opportunity to build on the foundation that their previous company started by creating a new platform where content took center stage. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. This ensures that trending content, as opposed to individual users, is at the forefront of user feeds.
Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.

# Business Problem 
Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain. Out of the 250 people working at Social Buzz, 200 of them are technical staff working on maintaining this highly complex technology.
Scale was a big problem of theirs and they are struggling to manage the scale with the resources that they currently have. The client is looking for help with the management of their journey into such a large scale.
Up until this point, they have not relied on any third party firms to help them get to where they are. However there are 3 main reasons why they are now looking at bringing in external expertise:
1) They are looking to complete an IPO by the end of next year and need guidance to ensure that this goes smoothly.
2) They are still a small company and do not have the resources to manage the scale that they are currently at. They could hire more people, but they want an experienced practice to help instead.
3) They want to learn data best practices from a large corporation. Due to the nature of their business, they have a massive amount of data so they are keen on
understanding how the world's biggest companies manage the challenges of big data.
To start our engagement with Social Buzz, we are running a 3 month initial project in order to prove to them that we are the best firm to work with. They are expecting the following:
- An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity

# Business Task 
* Conduct an analysis of Social Buzz content categories that highlights the top 5 categories with the largest aggregate popularity
* Gain and translate insights into actionable marketing strategies for Social Buzz
* Presentation of findings and recommendations to the Social Buzz executive team.

# Data Analysis Process
I will follow the 6 steps of the data analysis process - Ask, Prepare, Process, Analyize, Share and Act.

## 1. Ask 
* What are the top 5 content categories?

## 2. Prepare 
I am using the dataset provided to me by Accenture. This dataset consist of three data namely, contenet, reactions and reaction types. 

## 3. Process 
Check out the process [here](
* I used microsoft excel for this project 
* Using Microsoft Excel, I cleaned and prepped the data, making sure it was sparkling clean and ready for analysis. 
* I started by checking if the data types are accurate. I changed the date format to datetime.
* I checked for missing values of each data by filtering out blanks and deleting them.
* I checked for duplicates. There were no duplicates values.
* I removed columns that were irrelevant to the analysis like URL and user ID
* I joined the three datasets using power query with content ID being the primary key.
  

## 4. Analyze 
* I used the SUMIF function to aggregate the data by popularity score in order to get the top 5 categories.
* I used the COUNTIF function to check how many reactions are associated to the animals category which is the highest ranking category
* I also used the COUNTIF function to check the number of posts in each month 
* I created the Pivot table to summarize the data and charts to display the data

## 5. Share 
Findings


