# 🧾 MS_Power_BI_Financial_Products_Sales_By_Agents_Analysis

This Power BI project analyzes the performance of 11 agents tasked with selling financial (insurance) products over the phone. The goal was to visualize call and sales data to understand which agents performed best and what factors may have contributed to their success.

📂 Project Overview
Dataset Source: Kaggle
Domain: Sales Analytics / Financial Products
Tools Used: Power BI, Power Query, DAX, imgbb.com (for image hosting)

📊 Key Features
Overview Report Page:
- Bar chart showing Revenue per Agent
- Line overlay showing Total Call Duration
- Ranked table of agents by Total Sales
- Call statistics for all agents

Agent Dashboard Page:
- Filters to one agent at a time (via visual interaction)

Displays:
- Total number of calls made
- Total call duration
- Number of successful and unsuccessful calls
- Revenue generated
- Sales conversion rates (percentages)

Image Integration:
- Each agent has a corresponding profile image.
- Clicking on an agent’s image or bar chart filters to their dashboard.
- Images hosted using imgbb.com and displayed using Image by CloudScope visual.

🔍 Data Cleaning & Transformation
- Removed invalid rows (e.g., negative call durations)
- Replaced negative durations with 0 where clients didn’t answer
- Standardized text columns and calculated:
- Revenue = Number of Sales × $150
- Full Name = First Name + Last Name

Split original dataset into:
- Agents Table (one row per agent)
- Sales Table (one row per call attempt)

🧠 Insights Gained
- Highest-earning agent did not have the most calls or longest total call time

Sales success appears to depend more on:
- Agent skill
- Client targeting
- Possibly external factors (not in dataset)

📸 Image Handling in Power BI
To visualize agent photos:
- Downloaded & resized agent images
- Uploaded to imgbb.com
- Added the image URLs to the Agents table
- Used "Image by CloudScope" custom visual to display standalone agent images

⚠️ Note: A stable internet connection is needed for image rendering in Power BI.

🚀 Getting Started
To explore or replicate this project:
- Clone/download this repository
- Open the .pbix file in Power BI Desktop
- Ensure internet access for hosted images to display properly
- Interact with visuals by clicking on agent bars or images

📌 Use Cases
- This report/dashboard can be adapted for:
- Sales Agent Performance Reviews
- Call Center Monitoring
- Commission-Based Tracking
- KPI Dashboards for Team Leads

Author
Selorm Etse-Forfoe
Data Analyst | Virtual Assistant | IT Support Specialist | Educator
📧 selorm.etse5@gmail.com
🌐 LinkedIn: https://linkedin.com/in/selorm-etse-forfoe/

📎 License
This project is open source and free to use for educational and non-commercial purposes.
