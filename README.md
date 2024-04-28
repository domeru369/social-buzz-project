# Social Buzz Project
This project is from the Accenture North America job simulation. I hypothetically worked with team members to analyze social buzz data and identify their top 5 content categories with the largest popularity score.


# About the company 
Social Buzz was founded by two former engineers from a large social media conglomerate, one from London and the other from San Francisco. They left in 2008 and both met in San Francisco to start their business. They started Social Buzz because they saw an opportunity to build on the foundation that their previous company started by creating a new platform where content took center stage. Social Buzz emphasizes content by keeping all users anonymous, only tracking user reactions on every piece of content. There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. This ensures that trending content, as opposed to individual users, is at the forefront of user feeds.

Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively.

# Business Problem 
Due to their rapid growth and digital nature of their core product, the amount of data that they create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain. Out of the 250 people working at Social Buzz, 200 of them are technical staff working on maintaining this highly complex technology.

Scale is a big problem of theirs and they are struggling to manage the scale with the resources that they currently have. The client is looking for help with the management of their journey into such a large scale.

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
I was tasked with conducting an analysis to identify their top 5 categories.
* Conduct an analysis of Social Buzz content categories that highlights the top 5 categories with the largest aggregate popularity
* Gain and translate insights into actionable marketing strategies for Social Buzz
* Presentation of findings and recommendations to the Social Buzz executive team.

# Data Analysis Process
I will follow the 6 steps of the data analysis process - Ask, Prepare, Process, Analyize, Share and Act.

## 1. Ask 
* What are the top 5 content categories?

## 2. Prepare 
I am using the dataset provided to me by Accenture. This dataset consists of three data namely, content, reactions and reaction types. 

## 3. Process 
Check out the sheets on excel [here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fdomeru369%2Fsocial-buzz-project%2Fmain%2FA%2520CLEANED%2520DATASET%2520SHOWING%2520THE%2520TOP%25205%2520CATEGORIES.xlsx&wdOrigin=BROWSELINK)
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
### Findings
For the presentation deck, click [here](https://github.com/domeru369/social-buzz-project/blob/main/social%20buzz%20presention.pptx) 

![image](https://github.com/domeru369/social-buzz-project/assets/147932481/deaf369d-2a6f-4947-8b10-a69007157d1a)

The top 5 most popular categories on Social Buzz, ranked by the popularity score
* Animals: The clear winner! People love seeing cute cats, funny dogs, and all sorts of amazing creatures on Social Buzz with a score of 73271

* Healthy Eating: Looks like users are a health-conscious bunch! Healthy recipes, fitness tips, and wellness content are a big hit. 

* Food: Food is always a crowd-pleaser. From delicious dishes to mouthwatering desserts, food content keeps people engaged.

* Science: There's a thirst for knowledge on Social Buzz! Science content and interesting facts are a winning formula.

* Technology: People are curious about the latest tech trends and gadgets. Sharing tech news and reviews keeps users coming back for more.

* Bonus Find: We noticed a higher score for healthy eating compared to general food. This suggests users might be particularly interested in healthy lifestyle content.

* 16 Content Categories: Your platform boasts a diverse range of content, with 16  unique categories like Food, Science, and Animals.

* Animals : Social Buzz users are animal lovers! The "Animals" category alone sparked a whopping 1,926 reactions!

* January Rush: People seem to be more social in January, with this month seeing the highest volume of posts. Perhaps it's a way to reconnect after the holidays?


![image](https://github.com/domeru369/social-buzz-project/assets/147932481/0c110619-9700-4f9f-9fc6-8db1e09ce3c8)

Additionally, it can be seen from this chart the % split of popularity between the top 5 categories. There is not much difference between the share of each category, however, the difference between the 1st most popular, animals and the 2nd most popular, science, is the largest gap equal to 1.1%.

In business terms, this could suggest that the most popular category, animals, is tailing away from the rest of the categories and may continue to get more and more popular. To avoid an issue where 1 content category consumes the entire platform, it will be important to ensure that any algorithms used to govern the content on the platform gives a fair balance to the content categories.


![image](https://github.com/domeru369/social-buzz-project/assets/147932481/40c5a33c-fc0b-48b7-9256-2142a700b396)

It seems there are distinct periods where Social Buzz sees an increase in user activity:
January: This could be due to people reconnecting after the holiday season and sharing New Year's resolutions or experiences.

May: Perhaps this coincides with holidays or events like Mother's Day, graduations, or the start of summer in some regions, leading to increased social sharing.

December: The holiday season is naturally a time for increased social interaction, with people sharing gift ideas, festivities, and celebrations.

Summer (July & August): This could be due to people having more free time during vacations, holidays, or warmer weather, leading to them spending more time online and sharing experiences.


## 6. Recommendations 
1. Content Strategy by Category:
* Animals & Science: Double down on factual and visually engaging content. Partner with animal shelters, science communicators, or educational institutions to create high-quality * videos, infographics, or live streams.
* Healthy Eating: Embrace the health-conscious user base! Partner with healthy food bloggers or fitness influencers to develop recipes, workout tips, or healthy lifestyle challenges.

2. User Engagement & Personalization:
* Leverage User Behavior: Use data to personalize content recommendations for each user. Show users more of what they love (e.g., suggesting healthy recipes to users who engage with healthy eating content).
* A/B Test & Experiment: Test different content formats (videos vs. images) and themes within categories to see what resonates most with users.

3. Grow Content Reach:
* Partner with Influencers: Find influencers who align with top categories and collaborate on sponsored content or challenges.
* Run Targeted Campaigns: Leverage Social Buzz's targeting features to promote content to specific user segments based on their interests (e.g., healthy eating content to users who engage with fitness content).

4. Embrace Real-time Data:
* Implement real-time analytics tools: Gain continuous insights into user behavior and content performance.
* Track key metrics: Monitor user engagement, platform usage, and content performance to measure the success of your strategy.


## 7. Next steps 
* This ad hoc analysis is insightful, but its time to take this analysis further into large scale production for real time understanding of your business.


