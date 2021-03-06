# *Social Media Analytics with Tableau*
> ### Karlina Ho || DGT HUM 199 			

#  💻  Table of Contents
1. [Introduction](#Introduction)
    + [Purpose](#purpose)
    + [Who is this For?](#who-is-this-for)
2. [Social Media Analytics](#social-media-analytics)
    + [Importance](#importance)
    + [What are KPI's?](#what-are-kpis)
4. [Frequently Asked Questions](#frequently-asked-questions)
5. [Preparing for Tableau: Tutorial](#preparing-for-tableau-tutorial)
    + [Installing Tableau Desktop](#installing-tableau-desktop)
    + [Exporting Facebook Page's Insights Data for Tableau](#exporting-facebook-pages-insights-data-for-tableau)
5. [Tableau: Data Visualizations](#tableau-data-visualizations)
    + [Importing Social Media Data into Tableau: Facebook](#importing-social-media-data-into-tableau-facebook)
    + [Creating Basic Data Visuazalitons in Tableau](#creating-basic-data-visualizations)
6. [Analyzing Basic Data Visualizations](#analyzing-basic-data-visualizations)


# 💻  **Introduction**
## *Purpose* 
* Learn how to export data directly from social media platforms such as Facebook from social media marketing campaigns to create data visualizations on Tableau by importing social media data onto the platform. 
* Data visuzalizations can be used for analyzing and making informed decisions to optimize future social media campaigns and content. 
* This specific tutorial is aimed at importing Facebook Business Account data into Tableau, as Facebook is the [most common](https://www.statista.com/statistics/259379/social-media-platforms-used-by-marketers-worldwide/#:~:text=As%20of%20January%202021%2C%20Facebook,percent%20did%20so%20via%20Instagram.) social media platform for marketers. 

## *Who is This For?* 
* This tutorial was created by an aspiring marketer interested in pursuing a career in digital marketing, and is dedicated to beginning digital marketers. Specifically, these beginners are individuals interested in personally analyzing their social media analytics on their business Facebook account and creating a story through basic [data visualizations](https://www.tableau.com/learn/articles/data-visualization#:~:text=Data%20visualization%20is%20the%20graphical,outliers%2C%20and%20patterns%20in%20data.) to share with their company internally, investors externally, or clients. Although this tutorial is not an extensive step-by-step guide on how to create data visualizations on Tableau, this guide will lay the foundation to begin making informed decisions about digital marketing strategies. Additionally, multiple external sources are linked to build skills.

# 💻 **Social Media Analytics**
## *Importance*
* For businesses, marketers, influencers, and more, interpreting [social media analytics](https://www.ibm.com/topics/social-media-analytics) remain crucial in understanding the behaviors and wants of their target audiences including: 
  * Uncovering of social media trends and products/services that consumers respond postively to  
  * Understanding consumer attitudes, conversations, and responses to social media content 
  * Improving existing in-house and user-generated content 
  * Recognizing competitor social media strategies and the effectiveness of their social media campaigns 
* As a result, the development and improvement of products, business operations, and consumer experience can be postively influenced through these analyzations. However, how do we intepret these mass amounts of data on our social media accounts? 

## *What are KPI's?*
* Key performance indicators, or KPI's are defined measurable metrics that companies and individuals track on their social media platforms to analyze both their performance on social media platforms as well as their return on investments regarding social media expenditures. Read more about the importance of KPI's for your organization [here](https://www.linkedin.com/pulse/5-reasons-why-kpis-important-your-companys-growth-louise-leith-/). 

# 💻 **Frequently Asked Questions**
* Can I use A Facebook Data Connector?
  * Yes, you may! Unfortunately, if your laptop does not have the latest version of Tableau installed, you will be unable to connect your Facebook data. Consequently, importing the data straight from your Facebook page as a csv. file may be best! However, if you're still interested, [click here](https://www.tableau.com/solutions/workbook/facebook-connector) to learn how to extract your data into Tableau. 

* Can I Import Any Other Type of Social Media Analytics into Tableau?
  * Yes, absolutely. To access the data, you must connect your specific social media platform to Tableau. For a more detailed tutorial to connect your desired social media platform to Tableau, [watch this video](https://www.youtube.com/watch?v=lIHhVW8DAls&list=LL&index=7&t=1345s). Instructions begin on 12:14! 

* How Can I Make a More Sophisticated Graph on Tableau, such as Changing the Color, Adding More Columns and Rows, etc.?
  * There are an endless amount of data visualizations you can create on Tableau. To create a specific data visualization, refer to this [guide](https://help.tableau.com/current/pro/desktop/en-us/getstarted_buildmanual_ex1basic.htm) created by Tableau to add depth to your graphs. If you are interested in created a social media dashboard for your large data set, refer to this [video](https://www.youtube.com/watch?v=gGZ5-cn5ePk) for design inspiration. This tutorial covers the basics of Tableau.  

# 💻 **Preparing for Tableau: Tutorial**
This tutorial uncovers the basics of how brands can benefit through the storytelling of Facebook analytics through ***data visualizations*** via Tableau. 
* [Tableau](https://www.tableau.com/why-tableau/what-is-tableau) is a visual analytics platform and is used for reporting and analyzing data. This tutorial is dedicated towards individuals that have not installed Tableau Desktop, and are looking to see if this data analyzation tool is right for them. Users must download Tableau Desktop and not Tableau Public to access web applications and data source connectors. If you are a student, tableau is free. [Click here](https://www.tableau.com/academic/students) to learn more. If you have a product key, [click here](https://help.tableau.com/current/pro/desktop/en-us/license_activation.htm). 

## *Installing Tableau Desktop*
  * ### Step 1: Visit [Tableau](https://www.tableau.com/products/desktop)<img width="850" alt="Screen Shot 2022-05-10 at 9 18 46 AM" src="https://user-images.githubusercontent.com/79784875/167675667-067e320a-7d9a-49a6-a85a-d7f536c43f14.png">
  * ### Step 2: Click "Try Now"<img width="850" alt="Screen Shot 2022-05-10 at 9 19 52 AM" src="https://user-images.githubusercontent.com/79784875/167675884-a6b7b582-ae72-4877-98da-b3f8ee860aaa.png">
  * ### Step 3: Begin Your Free Trial <img width="850" alt="Screen Shot 2022-05-10 at 9 21 31 AM" src="https://user-images.githubusercontent.com/79784875/167676162-ca3e3737-6d0b-4d40-8e2d-5eb27a257c38.png"> 
  * ### Step 4: Create a Tableau Account and Request Free Trial  <img width="850" alt="Screen Shot 2022-05-10 at 9 22 27 AM" src="https://user-images.githubusercontent.com/79784875/167676364-90d45a0f-de6c-4184-b96e-a1bbab87ed19.png">
    <img width="850" alt="Screen Shot 2022-05-10 at 9 24 12 AM" src="https://user-images.githubusercontent.com/79784875/167676738-b3097d20-c030-48d1-aca3-42e33425f464.png">
  * ### Step 5: Begin Downloading the .exe File  <img width="850" alt="Screen Shot 2022-05-10 at 8 56 53 AM" src="https://user-images.githubusercontent.com/79784875/167671327-ab727200-3594-4bcb-b23d-1de19b2a323c.png">
  * ### Step 6: Open the File and Accept the Terms and Conditions. Click "Install." <img width="850" alt="Screen Shot 2022-05-10 at 8 58 17 AM" src="https://user-images.githubusercontent.com/79784875/167671588-9a105fd2-daef-422b-84f0-0a8f3a190715.png">
  * ### Step 7: Fill Out the Registration Window <img width="700" alt="Screen Shot 2022-05-10 at 9 29 23 AM" src="https://user-images.githubusercontent.com/79784875/167677697-7f81fbd0-c22d-4bba-9b90-46c18fe0bb50.png">
  * ### Step 8: Access Your Tableau Start Screen <img width="850" alt="Screen Shot 2022-05-10 at 9 32 07 AM" src="https://user-images.githubusercontent.com/79784875/167678136-0768ec73-c37e-4233-ae94-5c3f4f401d28.png">

## *Exporting Facebook Page's Insights Data for Tableau* 
  * ### Step 1: From your Facebook News Feed, click the "Pages" button in the left menu.<img width="850" alt="Screen Shot 2022-05-30 at 10 50 37 PM" src="https://user-images.githubusercontent.com/79784875/171101953-4f2ebcd3-6140-4a67-88e8-f2dac10fc89c.png">
  * ### Step 2: Select your desired Facebook Page "<img width="850" alt="Screen Shot 2022-05-30 at 11 13 11 PM" src="https://user-images.githubusercontent.com/79784875/171104958-02ce171e-7a55-4f45-9b43-4e41fd638a9c.png">
  * ### Step 3: Click the "Insights" Tab on the left menu <img width="850" alt="Screen Shot 2022-05-30 at 11 15 56 PM" src="https://user-images.githubusercontent.com/79784875/171105318-a53873a6-b8da-485a-96ca-77d00a9f12b6.png">
  * ### Step 4: Click "Export Data" <img width="850" alt="Screen Shot 2022-05-30 at 11 33 18 PM" src="https://user-images.githubusercontent.com/79784875/171107730-884e35b6-aead-4d1a-be12-ad3bdf3ccb22.png">
  * ### Step 5: Select desired data type, file format, and date range. CSV file recommended for Tableau. <img width="850" alt="Screen Shot 2022-05-30 at 11 34 19 PM" src="https://user-images.githubusercontent.com/79784875/171107875-49b18a8c-2a14-4830-a3f7-e29468929f28.png">
  * ### Step 6: Export Data <img width="850" alt="Screen Shot 2022-05-30 at 11 37 39 PM" src="https://user-images.githubusercontent.com/79784875/171108320-35cb01cd-114b-46aa-aa76-80ef8794b25b.png">

# 💻 **Tableau: Data Visualizations**
## *Importing Social Media Data into Tableau: Facebook*
  * ### Step 1: Access Your Tableau Dashboard and click "Text File" <img width="1051" alt="Screen Shot 2022-05-31 at 12 35 04 AM" src="https://user-images.githubusercontent.com/79784875/171118182-ffa0e43f-7801-4f19-ab9b-af6f2e9bd2c8.png">
  * ### Step 2: Locate and Import your csv. file into Tableau <img width="1081" alt="Screen Shot 2022-05-31 at 12 35 46 AM" src="https://user-images.githubusercontent.com/79784875/171118339-efed4080-04c0-4a7b-bb28-11357f6a4b87.png">
  * ### Step 3: Wait for your Facebook Insight to Load onto Tableau <img width="1045" alt="Screen Shot 2022-05-31 at 12 36 49 AM" src="https://user-images.githubusercontent.com/79784875/171118519-ee58f324-cb2b-4823-b8b2-e55ffbd0a54c.png">

# 💻*Creating Basic Data Visualizations*
* Once you data is successfully uploaded into Tableau, you can then create data visualizations to measure your [key performance indicators](https://blog.hootsuite.com/social-media-kpis-key-performance-indicators/). For this specific tutorial, we will be using Tableau to answer, "When Should I Post to Obtain the Greatest Reach?" 
  * ### Step 1: Create a New Worksheet in Tableau <img width="950" alt="Screen Shot 2022-05-31 at 12 57 20 AM" src="https://user-images.githubusercontent.com/79784875/171122530-6847ef7f-c048-4525-bc32-d1531128efed.png">
  * ### Step 2: Drag Desired Data from Data Pane into Respective Rows and Columns. This will "build a view," or create a data visualization. This is not your final data visualization. <img width="1280" alt="Screen Shot 2022-05-31 at 1 16 09 AM" src="https://user-images.githubusercontent.com/79784875/171126151-323b1a5d-b873-4efd-b9f4-7a5c9dd8f504.png">
  * ### Step 3: To Further Explore your Data, [click here](https://help.tableau.com/current/pro/desktop/en-us/getstarted_buildmanual_ex1basic.htm) to learn more. Your data visualization will evolve as you continue to explore the tools Tableau has to offer. <img width="1280" alt="Screen Shot 2022-05-31 at 1 15 27 AM" src="https://user-images.githubusercontent.com/79784875/171126004-6ece90a0-2d3d-4fdf-98b5-4acd40fee1df.png">

# 💻 *Analyzing Basic Data Visualizations*
Once you create your desired data visualizations, you can begin analyzing the data by posing questions around your KPI's you chose to analyze. For this tutorial our chosen KPI was the number of unique accounts reached from each post.
*Through this data visuzation, we are able to see that the greatest number of accounts reached was through a Facebook photo that was posted at 5:55pm. The post that recieved the 2nd highest number of accounts was posted about three hours beforehand (2:46pm). As a result, this data visuzation uncovers a potential posting time for our account— late afternoon to early evening. Upon further inspection, the average time of the top 5 posts that garnered the highest reach is about 3:30pm, suggesting for the social media account to become most active at that time.  
* Now, we are able to dig further into the content and consider other variables such as: 
  * What medium were these posts? Were they videos, static images, carousels, Reels, etc.?
  * Were any of these posts associated with a specific campaign? 
  * What tags or hashtags were used to garner greater visability? 
  * What are commenters saying about the post. What are their reactions? 
  * What kind of content is reaching the most people?  
* These discussions allow marketers to make informed decsions about future social media posts and marketing campaigns and improve upon their existing strategies. 
<p align="center">
    <img width="658" alt="Screen Shot 2022-05-31 at 1 26 01 AM" src="https://user-images.githubusercontent.com/79784875/171128163-201c6d7a-978b-437b-ad55-71fecf2371b4.png">

    










 
                 
                 
                 
                
