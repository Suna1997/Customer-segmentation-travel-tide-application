# Customer-segmentation-travel-tide-application
# Project Overview
In this project, you will segment customer data according to business needs and deliver data-driven recommendations based on your findings.


The project features three stages:

1-Familiarize yourself with the business context. Use SQL to extract a customer dataset. Explore the data at different levels of aggregation and form a plan for further analysis.
2-Make calculations related to the business context then segment customer behavior data with statistical and visual techniques using the appropriate tools.
3-Create an executive summary and slides of the customer segmentation results and record a video presentation.

# What is segmentation? 

It refers to a broad category of analytic techniques that allow us to group similar data points. In this project, data points will represent customers, who we will group according to their shopping behavior in the context of a very specific business initiative.
As mentioned, the focus of this Project is segmenting customers based on their shopping behavior. However, it is important to know that segmentation is a very general approach to data analysis broadly applicable to just about every domain. Whenever we suspect a dataset has some natural but hidden structure - we can use segmentation to reveal it. To see this, consider a non-business context like cancer diagnostics. Suppose we have an extensive collection of medical images that physicians have not reviewed for abnormalities. Segmentation can be used to cluster images with similar pixel patterns prior to review by human doctors. Then, instead of manually reviewing every image, doctors can sample images from each cluster to verify if any clusters correspond to abnormal images! This improves diagnostic speed, resulting in better patient care.

Back to business. From a business perspective, customer segmentation divides a customer database into groups to provide a tailored customer experience - rather than one size fits all. The business value of creating such groups is the ability to implement specific business strategies, including:


customized promotions (e.g. special offers, discounts)
personalized communications (e.g. targeted marketing emails)
specific account policies (e.g. credit line)

The role of a data analyst in driving business value is defining segmentations that are meaningful and aligned with business objectives. Segmentation projects can be somewhat more open-ended and require analysts to think about the problem space from multiple points of view. Thinking deeply about business needs, customer behavior, and creative ways to apply various analytical tools makes segmentation a rewarding challenge.

# TravelTide 

e-booking startup TravelTide is a hot new player in the online travel industry. It has experienced steady growth since it was founded at the tail end of the covid pandemic (2021-04) on the strength of its data aggregation and search technology, which is best in class. Customer feedback has shown, and industry analysts agree, TravelTide customers have access to the largest travel inventory in the e-booking space. 


Following the startup playbook, TravelTide has maintained a hyper-focus on building an unfair advantage along a limited number of dimensions - in this case, building the biggest travel inventory and making it easily searchable. Because of this narrow focus, certain aspects of the TravelTide customer experience are underdeveloped, resulting in poor customer retention. CEO Kevin Talanick is very motivated to retain and add value to existing customers with a Marketing strategy built on a solid understanding of customer behavior.


Meet Elena Tarrant, the new Head of Marketing. Elena has been brought on to supercharge the Marketing efforts at TravelTide. She is well known in the Marketing community as an expert in customer retention strategies, specifically rewards programs, an advanced feature proven to generate repeat business if executed well. 

Elena’s mission is to design and execute a fantastic personalized rewards program that keeps customers returning to the TravelTide platform. It is difficult to personalize rewards for customers without first understanding them, so for the project to be successful, Elena will need to lean on the data team for customer insights.

# Marketing 🤝 Data
You are on the Analytics team and responsible for supporting Elena’s rewards program project. Her subject matter expertise together with your data skills should result in a product reflecting marketing know-how and backed by solid evidence.  After an initial meeting, Elena sent a follow-up message, reproduced here:
  




Elena believes that to grab customer attention and maximize the likelihood they will sign up for the rewards program, we want to emphasize the perk we think they are most interested in when we ask them to sign up. To give us a clear picture of the difference our analysis will make, Elena has also shared some mock-ups of rewards program invitation emails. 




The email on the right is vague and requires customers to read through a bulleted list of equally emphasized rewards. The one on the left has specific messaging about a free cancellation perk. Elena’s marketing logic is that if we believe a subset of customers will be particularly interested in free cancellation, TravelTide has a much higher chance of getting them to sign up for rewards using the email on the left.


Our mission as Data Analysts is two-fold. First need to check if the data support Elena’s hypothesis about the existence of customers that would be especially interested in the perks she is proposing, then for each customer, assign a likely favorite perk. 


Here are some questions to consider as we reflect on the business problem and crack open the TravelTide database:


For each perk, what kind of travel behavior indicates affinity to the perk? For example, what kind of customer could be especially interested in a free checked bag?
Which fields in the database contain information about these behaviors? 
How should the data be set up (e.g., filtered, aggregated) to avoid a logically flawed segmentation analysis?

 # Dataset

 TravelTide stores its data in a relational database, which you can access here:

🐝
Beekeeper Studio

Beekeeper Studio is a popular open-source SQL editor that makes it easy to query databases. Please see the following page for the step-by-step instructions to get started:


postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766.us-east-2.aws.neon.tech/TravelTide
