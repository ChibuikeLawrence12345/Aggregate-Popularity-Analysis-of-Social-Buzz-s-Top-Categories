# Aggregate Popularity Analysis of Social Buzz's Top Categories
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
The client provided **three datasets** for analysis:  

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

##  Summary & Recommendations  
- **Prioritize Animals and Science** content → consistently lead in popularity and align with user interests  
- **Capitalize on Healthy Eating** → strong engagement indicates partnership opportunities with food & health brands  
- **Double down on photos** → lower production cost vs. videos and highest engagement levels  
- **Leverage May and August/Q2** → peak posting months, ideal for high-visibility campaigns 

---

## Datasets
raw datasets(https://1drv.ms/f/c/B6F01BA262EFC1A3/Eupt8VG0yPlMgZyYyJDB_nsBCCtfpT-0nnVP0F83sDTc3A)

cleaned dataset(https://1drv.ms/f/c/B6F01BA262EFC1A3/EvjuFnlDcK9ClkWL_W544hABqi08fkmaOfhLX7Md5JggPQ)

---

##  Visuals  
Exported Charts(https://1drv.ms/f/c/B6F01BA262EFC1A3/En_iApsxOb9JmH3r9yAHWs4BQhf4oE3UQfi5NXsonrQ9DA)
  
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
👤 *Chibuike Lawrence*  
🔗 [LinkedIn](https://linkedin.com/in/chibuike-lawrence-2348b01b6)  
📧 lawchibuike12345@gmail.com  
