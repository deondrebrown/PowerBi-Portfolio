# Project Overview & Background

Atlas Labs is a fictional technology company that wanted to understand its workforce better through data. The HR team needed a centralized Power BI solution to track employee metrics such as hiring trends, performance ratings, satisfaction levels, and attrition. Prior to this, they relied on static reports that offered limited visibility into what truly drives employee retention and engagement.

I built this Power BI dashboard to:
- Model and integrate multiple HR data sources into a unified view.  
- Develop calculated measures using DAX to analyze attrition and diversity metrics.  
- Create an interactive and visually engaging report that highlights key workforce insights for decision-makers.

The HR team’s goal was to monitor:
- Employee demographics and diversity representation.  
- Attrition and retention trends across departments, roles, and satisfaction levels.  
- Performance and education metrics to identify what factors may influence employee happiness and turnover.

---

# Data Structure

The project was designed using a **snowflake schema**, incorporating one central fact table and five supporting dimension tables:  
**Employee**, **EducationLevel**, **RatingLevel**, **SatisfiedLevel**, and **Date**.  

The Date table was created in Power BI to enable time-based analysis by year, quarter, month, and day. This structure provided the HR team with the flexibility to drill down across multiple levels of context — the who, what, when, where, and why behind every metric.

This model allowed for seamless integration of demographic, performance, and satisfaction data, providing the foundation for deeper analytics on employee behavior and organizational trends.

---

# Executive Summary

Through this project, I uncovered several key insights into Atlas Labs’ workforce:

- **Employee Overview:** Atlas Labs employed **1,470 people** since opening its doors, with roughly **1,200 active employees** at the time of analysis. As expected for a software company, the **Technology department** made up the largest share of the workforce.  
- **Attrition Insights:** The company’s **attrition rate stood at 16%**, prompting further exploration into the factors contributing to employee turnover.  
- **Diversity & Inclusion:** Demographic data revealed that most employees were between **20 and 29 years old**. Women represented only **2.7%** of the organization, while employees identifying as non-binary made up **8.5%**. Additionally, employees identifying as **White** had the highest average salaries, whereas those identifying as **mixed or multiple ethnic groups** had among the lowest.  
- **Actionable Findings:** These findings highlight opportunities for Atlas Labs to review its hiring and compensation strategies, improve diversity and inclusion efforts, and identify patterns in attrition linked to demographics and satisfaction levels.

This Power BI dashboard enables the HR team to easily navigate key workforce metrics, monitor hiring and diversity trends, and analyze employee satisfaction and attrition in one interactive report. It serves as a comprehensive HR analytics solution that turns raw data into meaningful insights for leadership decision-making.

📄 [View Power BI Dashboard (PDF)](Atlas%20Labs/Atlas%20Labs%20HR%20Analytics.pdf)


---

# Tools & Technologies Used
- **Power BI Desktop** – Data modeling, DAX calculations, and report design  
- **Power Query** – Data cleaning and transformation  
- **DAX (Data Analysis Expressions)** – Custom KPIs for attrition, performance, and diversity  
- **Excel** – Initial data staging and validation  

---

# Key Takeaways
- Built an end-to-end HR analytics solution using Power BI.  
- Implemented a snowflake data model for scalable workforce reporting.  
- Delivered diversity, attrition, and performance insights through dynamic visuals.  
- Improved HR’s ability to make data-driven decisions regarding retention and inclusion.

---

