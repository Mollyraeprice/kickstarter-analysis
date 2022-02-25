# Kickstarting with Excel

## Overview of Project

Make clear the outcome of the Kickstarter campaign based on their launch date and goal amount.

### Purpose

My client, Louise the playwright, had previously used excel data to help lay the groundwork for her plan with crowdfunding for her new play, Fever. She was almost fully funded in a short amount of time. Still interested in the crowdfunding analytics, Louise asked me to find the correlation between the success of the campaign, the launch date of the campaign and the amount of the campaign funding goal. 

## Analysis and Challenges. Explain how you performed your analysis using images and links to code, as well as any challenges you encountered and how you overcame them. If you had no challenges, describe any possible challenges or difficulties that could be encountered.

My first analysis was of the success of theater productions based on the month they were launched. The second analysis was based on the outcomes of the fundraising based on the amount of the goal. My second analysis took some time because of the COUNTIFS formula. I had to learn each step of the formula and the purpose of it. I also had inputted data incorrectly in one of my formulas so my ‘number successful’ was different than my count with filters on when I was double checking my work. Lastly, setting up the line chart without the directions of the parameters exposed my lack of understanding of the datasets in the pivot chart. It took some tinkering and google, but I was able to learn along the way.

## Results

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/98489681/155790309-9bace10c-d188-43ef-99c1-31489c189293.png)

Looking at the theater outcomes based on launch date, one can right away see that the beginning of the summer is a great time to launch a crowdfunding campaign. Also, the waves of success and failure actually move the same way interestingly enough. So, although the success of the campaigns drops over the course of the summer, so does the failed numbers. But one great note about the data, is that there are always more successful outcomes than failed outcomes. 


### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/98489681/155790479-5a0fc42f-9599-4fab-920e-585c5d8afe3d.png)

At first glance, the second analysis is confusing because the lines mirror each other, but it’s because there are only two data points and its set in percentages. Looking at the percentage successful, you can see that campaigns do much better with low goals. Once the goals are hitting $15,000 to $20,000, the number of successful campaigns start losing out to the number of failed campaigns. Although, there seems to be a sweet spot between $35,000-$40,000 for successful campaigns. If needed, more analysis could be done on the group of plays in this dataset, but it would be limited. Louise may need more data on this specific group. I could create an analysis based on a specific goal range with a successful outcome and see how many backers there are along with other data sets we have available. We might be able to come up with the “perfect crowdfunding campaign” for Louise that will give her almost exact specifications that will help her future plays succeed.
