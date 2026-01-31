# Aggregate Popularity Analysis of Social Buzz's Top Categories - Accenture
##  Introduction  
This project looks at engagement trends for **Social Buzz**, a fast-growing social media and content company.  
The goal was to identify **which content categories are most popular with users** and how the company can use these insights to **increase engagement and unlock revenue opportunities**.  

---

##  Problem Statement  
Social Buzz generates over **100,000 posts every day** – more than **36 million pieces of content per year**.  
With so much data, it’s not immediately clear **which categories truly drive engagement**.  

The client needed a **clear, data-driven answer** to a critical question:  
 *What are the top five content categories by aggregate popularity, and how can Social Buzz capitalize on them?*  

---

##  About the Dataset  
The client *(Accenture North America: Data Analytics and Visualization Job Simulation)* provided **three datasets** for analysis:  

1. **Content** – *1,001 rows, 6 columns*  
   - Fields: Content ID, User ID, Type, Category, URL  
   - Shows the type of content posted and its category.  

2. **Reactions** – *25,554 rows, 5 columns*  
   - Fields: Content ID, User ID, Type, Datetime  
   - Captures how users reacted to posts.  

3. **Reaction Types** – *17 rows, 4 columns*  
   - Fields: Type, Sentiment, Score  
   - Maps reaction types to sentiment and weight.  

---

##  Business Questions  
1. How many unique content categories exist?  
2. Which category is most popular overall?  
3. Which type of content gets the most reactions?  
4. Which month saw the highest post volume?  
5. Which single post received the most reactions?  

---

##  Methods & Tools  

### **Excel Concepts Applied**  
- **Data Cleaning** → removed duplicates, blanks, and unnecessary columns  
- **Error Checking** → corrected errors to maintain accuracy  
- **Data Type Conversion** → formatted IDs and dates properly  
- **INDEX + MATCH** → combined datasets on Content ID and User ID  
- **Data Modeling** → created a clean model for Power BI  

### **Power BI Concepts Applied**  
- **ETL** → imported datasets into Power BI and transformed them in Power Query  
- **Visualizations** → bar charts comparing categories, content types, and reactions  

---

##  Findings  
1. **16 unique content categories** exist  
2. **Animals** is the most popular category with **1,897 reactions (~22% of all engagement)**  
3. **Photos** drive the most user reactions compared to videos and text  
4. **May and August** saw the highest number of posts  
5. The most engaging single posts came from the **Animals** category  

---

##  Summary & Actionable Recommendations  
1. **Optimize the Content Mix (The 60/30/10 Rule)**

Action: Allocate 60% of the budget to Animals & Science (the proven engagement drivers), 30% to Healthy Eating (the high-growth partnership niche), and 10% to experimental content.

Detail: This follows the Pareto Principle, ensuring you "double down" on your winners to maximize ROI while still leaving room for new revenue opportunities.

2. **Monetize through Partnerships (The "Revenue" Play)**

Action: Build a media kit specifically targeting Health, Wellness, and Organic Food brands.

Detail: The strong engagement in Healthy Eating proves you have a high-value audience. Pitch "sponsored recipe" posts or "health tip" segments to brands looking for an engaged community.

3. **Shift Production to High-ROI Formats (The "Efficiency" Play)**

Action: Transition the primary posting format to High-Quality Photography rather than long-form video.

Detail: Photos have the highest engagement and lower production costs. Use the time and money saved from video production to increase your posting frequency of photos.

4. **Execute "Pulse" Marketing Campaigns (The "Timing" Play)**

Action: Schedule your biggest annual launches or high-value brand deals during May and August (Q2/Q3).

Detail: These are your "Peak Performance" windows. Avoid launching new major projects in slower months; instead, save your best content to ride the natural wave of high user activity during these months.

**Summary for Stakeholders**

By shifting focus to Photos within the Animals and Science niches, we can decrease production costs while increasing reach. We should concentrate our biggest brand partnerships in Q2 and Q3 to maximize ROI.

---

## Datasets
raw datasets[(https://1drv.ms/f/c/B6F01BA262EFC1A3/Eupt8VG0yPlMgZyYyJDB_nsBCCtfpT-0nnVP0F83sDTc3A)]

cleaned dataset[(https://1drv.ms/f/c/B6F01BA262EFC1A3/EvjuFnlDcK9ClkWL_W544hABqi08fkmaOfhLX7Md5JggPQ)]

---

##  Visuals  
Exported Charts[(https://1drv.ms/f/c/B6F01BA262EFC1A3/En_iApsxOb9JmH3r9yAHWs4BQhf4oE3UQfi5NXsonrQ9DA)]
  
- Category by Aggregate Popularity → `visuals_category_by_aggregate_popularity.jpg`  
- Content Type by Reactions → `visuals_content_type_by_reactions.jpg`  
- Posting Trends by Month → `visuals_posts_by_month.jpg`  
- Category by Reactions → `visuals_categories_by_reactions.jpg`  

---

##  Repository Structure  
social-buzz-analysis/
│
├── data/
│ ├── raw/ # raw datasets
│ ├── cleaned/ # cleaned datasets
│ └── README.md
│
├── visuals/ # exported charts
│
└── README.md # this file


---

##  Skills Demonstrated  
- **Data Cleaning & Preparation** (Excel, Power Query)  
- **Data Modeling** (combining datasets)  
- **Visualization** (Power BI Visuals/Charts)  
- **Data Storytelling** (turning analysis into recommendations)  

---

##  Contact

For questions or collaborations, contact:
- **Name** : Chibuike Lawrence

- **Email** : [lawchibuike12345@gmail.com]

- **LinkedIn** : [https://www.linkedin.com/in/chibuike-lawrence-2348b01b6]

- **GitHub** : [https://github.com/ChibuikeLawrence12345]
