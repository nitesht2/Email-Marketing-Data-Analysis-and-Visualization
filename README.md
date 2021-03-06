# Email Marketing Data Analysis and Visualization

## About
In this project I will create a dashboard for an email marketing campaign that will give an overview and idea of how a marketing manager could use this dashboard to find the insight.

Dataset can be found [here](https://github.com/nitesht2/Email-Marketing-Data-Analysis-and-Visualization/blob/main/Email_marketing_Data.csv)

## Business Task:
The marketing manager wants to find out key answers to the following questions for the campaign:

- When to send the email?
- Who is the targeted customer?
- What campaign is to be executed?

## Tools:
- Microsoft Excel
- Tableau

## Dashboard:
The public link for the dashboard can be found [here](https://public.tableau.com/app/profile/nitesh.thapa/viz/EmailMarketingCampaignDashboard_16533555057360/EmailMarketingDashboard)

![image](https://user-images.githubusercontent.com/50633864/170101183-ae525d10-a854-4f09-8916-4311e7ceb1c2.png)


## Findings:
I found out that the click-through rate for the master email list is extremely low compared to the other two lists. The reasons for low click through might be due to following reason:
- Poor Content
- High Bounce Rate


![image](https://user-images.githubusercontent.com/50633864/170100583-40eb0c68-4d82-4800-a307-1a4400d2cf1c.png)

- Poor content can be tracked by using a metric called “unsubscribe rate”, which is in the raw data file. The unsubscribe rate is the percentage(%) of users who click unsubscribe from the email campaign list. The reason it is such a good metric is that, if customers are getting emails that they don’t care about, then most likely they will unsubscribe. Another way to summarize is, that if the customer is not opening the email then it means that the email tag line might not be great or the timing is not good for the customer to open. But if they unsubscribe then it is a strong indicator that the customer won't care about the content which means our content is poor.

- Secondly, bounce rate is the percentage of email addresses in the list that actually don’t receive the message because it was received by a recipient mail server. This means if we are collecting these email lists in our database maybe some of them are bad or people are not using and it's time to clean up the raw data files. Also, we could potentially find out the people who are bouncing and find the correct email to lower the bounce rate. 

