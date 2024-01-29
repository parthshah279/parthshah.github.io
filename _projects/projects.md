---
layout: page
title: Projects
permalink: /Projects
---
## __Tableau dashboard for projected stock alert and warehouse capacity at Novo Nordisk__ 
***

Problem Statement: 

Challenges were encountered in the production planning process due to occasional delays in raw material shipments, quality issues, and deviations in product manufacturing. The absence of a comprehensive real-time visibility tool for future projections led to inefficiencies in planning long lead-time materials, causing disruptions in production lines. Manual monitoring, in response to frequent changes in production plans, posed challenges in warehouse management, occasionally resulting in overutilization issues. A forward-looking capacity outlook was lacking, necessitating reactive responses to warehouse capacity constraints and other production-related issues.

Goal: 

Provide real-time visual insights using an innovative business intelligence tool for the long-term stock projections and warehouse capacity

Actions:

__Projected stock alert dashboard__ 
- Defining Data Sources: Collaborating with the planning team, I gathered requirements for dashboard. I extracted master data from SAP and categorized it into various material categories. Using color-coded stock levels, I added an interactive visualization for current and future stock status relative to safety stock. For future weeks' projections, I used key figures from SAP Advanced Planning Optimizer(APO) planning books based on material types, such as total demand, total receipts, stock on hand, max stock, and safety stock.
- Data Integration: While developing the dashboard, I faced data challenges where the data flow was inconsistent. I utilized SAP BI reports to access the latest data, although several data update issues persisted. After a couple of months of regular monitoring and updating process flow in Tableau, I refined the dashboard based on the feedback from trial runs. The refresh frequency aligned with the planning team's review schedule.

__Warehouse Capacity Dashboard__
- Created Master Data file: I collaborated with the local warehouse team to understand their capacity calculations to solve the warehouse capacity issue. As system master data was unavailable for warehouse management, I had to create a master file detailing all materials used at the China plant, along with pertinent data for each SKU, including pallet size, maximum pallet quantity, batch size, MOQ, warehouse location, and storage location.
- Dashboard Layout: The dashboard was divided into current and future week capacity, color-coded to indicate capacity levels compared with maximum available capacity. Future weeks' capacity was calculated using demand and consumption from SAP APO.

Results

- Integrated Projected Stock Alert dashboard into weekly KPI review meetings, resulting in proactive management and fewer stock-outs.
- Introduced weekly warehouse capacity review meetings using Warehouse Capacity dashboard, leading to a 95% reduction in overutilization issues.
- Identified top contributors to capacity constraints for timely resolution.
- Streamlined issue escalation and communication processes, resulting in an annual savings of approximately 3000 person-hours.
- Dashboards were implemented across other Novo Nordisk production sites, generating indirect cost savings through reduced operational costs and efficient material management
<br><br>

## __Development of API stock simulation file via Alteryx at Novo Nordisk__ 
***

Problem Statement: 

Novo Nordisk faced a challenge in managing five types of purchased APIs, essential for producing up to 40 insulin products for both domestic and international markets. To adhere to Chinese tax and government regulations, APIs were procured for two locations—Bonded and Non-Bonded. Existing SAP APO customization, while plant-specific, lacked support for location-based planning within the same plant. Consequently, demand for domestic and export markets was combined under the same API SKU, leading to manual API procurement management using Excel, taking 4-5 hours for a single instance.

(API Info - An API stands for Active Pharmaceutical Ingredient. It is crucial item for insulin production. In simple terms, a few kilograms of API can produce a batch of 450,000 insulin cartridges after dilution with excipients like Hydrochloric Acid and Sodium Hydroxide.)

Goal: 

Develop an API stock simulation file that integrates data sources, updating automatically on a weekly basis.
Actions: 

- Defined necessary data points and identified required data sources: Semi-finished product demand from APO, converted into API requirements based on the Bill of Materials; Current stock levels from SAP ECC; Information on API batches categorized by location and type; Estimated remaining time for batch releases in quality control; Records of current purchase orders and their expected arrival dates.
- Overcame challenges with unavailable or incompatible data reports by identifying SAP BI reports in consultation with internal teams.
- Crafted an Alteryx flow incorporating logic based on lead times, quality release times, consumption patterns, stock on hand, purchase order dates, etc.
- Addressed timing issues causing discrepancies by shifting reporting frequency to Tuesdays to align with updates to certain BI reports on Monday afternoons. Refined the file over several weeks, incorporating stakeholder input to eliminate errors and automate projections for future weeks.

Results:

- Developed a file executing in just five minutes, saving planners 4-5 hours weekly, and automatically emailing simulation results to stakeholders.

- The file served multiple purposes, including API procurement planning, financial reporting, simulations for order prioritization, and optimization of transportation methods, such as shifting from sea to air freight when necessary.
<br><br>

## __Re-utilization of GIS bay items into other projects at ABB (Cost optimization project)__ 
***

Problem Statement: 

ABB faced a challenge when a customer cancelled an order for 7 bays of Gas Insulated Switchgear (GIS), resulting in the stored materials lingering in the warehouse due to legal constraints. After two years, the management decided to disassemble the bays and repurpose the materials for other projects. The difficulty lay in orchestrating the physical disassembly on the lean manufacturing shop floor and integrating the process seamlessly into the SAP system without disrupting regular production.

Goal: 

Maximize the use of materials from the canceled order in ongoing and future projects, thereby reducing obsolescence.

Action: 

- Formed a cross-functional team, comprising representatives from project management, engineering, planning, production, testing, quality, and warehouse. Took a leadership role as a representative from the planning team, coordinating efforts across departments and providing regular updates to the Management team.
- Assigned tasks to specific departments: the warehouse team handled the transportation and unpacking, production managed the disassembly, engineering and quality teams conducted inspections and decision-making, and the planning team, maintained stock count and allocated materials to future projects.
- Addressed challenges in aligning project timelines, scheduling meetings, and overcoming departmental hesitation by developing a tailored process for the project.

Result:

- Leveraged the diverse expertise of the team, encompassing technical, commercial, and system-related knowledge, facilitating informed decision-making.

- Achieved significant cost savings of $500,000 by repurposing materials from the canceled order into various ongoing projects. Completed the entire process in 6 months, seamlessly integrating with regular production activities.
<br><br>

## __Reduction of Slow moving and Obsolete inventory in Philippines and Vietnam at Diageo__ 
***

Problem Statement:  

In October 2020, six months into the COVID-19 pandemic, the company faced a significant challenge as sales started to decline due to restrictions and shutdowns in Philippines and Vietnam market. By the time company recognized the drop in demand, the company had already accumulated a substantial amount of high inventory and in-transit inventory with a 60-day lead time. Most items had over 180 days of inventory, posing a risk to the company's financial health.

Goal: 

Reduce the slow moving and obsolete by $1 million 

Actions:

- Inventory Categorization: The first action involved categorizing the slow-moving inventory into three groups based on aging - items older than 2 years, 1-2 years old, and 4-12 months old.
- Cross-Functional Collaboration: Recognizing the need for a holistic approach, I organized a cross-functional meeting involving teams from sales and marketing, logistics, quality, and demand planning. The goal was to collectively address the inventory challenges. The team identified 10-15 stock keeping units (SKUs) each month to focus on. This targeted approach ensured a systematic and efficient handling of the slow-moving inventory.
- Old SKU Strategy: For the older SKUs, specific strategies were implemented, including promotion activities and rework for festive packaging to stimulate sales and reduce the aging inventory.

Results:

- At the end of six months, the company successfully addressed the slow-moving inventory challenge and exceeded expectations. The company had set a reduced SLOB (Slow-Moving and Obsolete) target of 1 million USD, but the actual achievement was an impressive 2.5 million USD. 

- This accomplishment was particularly noteworthy as it was achieved in the challenging business environment of the Philippines and Vietnam during the ongoing COVID-19 pandemic. The combination of strategic categorization, cross-functional collaboration, and targeted actions on specific SKUs contributed to this successful outcome.

 <br><br>

## __Improved Case fill rate (CFR) to 98% in Philippines at Diageo__ 
***

Problem Statement:   

At Diageo, I managed the supply chain for the Philippines from the UK and Singapore. The typical transit time for products from order placement to reaching the market was approximately 90 days, comprising 60 days in transit and 30 days for order processing. However, the case fill rate was stagnating at around 94%, with shipping delays and the onset of the Covid-19 pandemic being major contributing factors. The lack of real-time information and live tracking of orders exacerbated the situation, and the planning team struggled to have timely on-hand data.

Goal: 

Improve the Case fill rate (CFR) by 3-4% in next 6 months.

Actions:

- Database Implementation for Live Order Tracking: I proposed the creation of a database (DB) to facilitate live tracking of orders. For that, I collaborated with logistics partners to obtain daily data on order movements and implemented a nightly run to update the DB with the latest information. The DB was streamlined over a month to align with the management's reporting requirements.
- Priority-Based Customer Clearance: I utilized the live order tracking data to predict expected delivery times. After that, I implemented a system to prioritize customer clearance based on specific customer requirements and stock levels, Ensuring efficient and timely clearance for high-priority orders.
- Daily Measurement and Root Cause Analysis: I Recommended a shift from weekly to daily measurement of the case fill rate and introduced a systematic approach to identifying and documenting reasons for any shortfalls. Emphasized the importance of continuous monitoring to quickly identify and address issues.

Results:

- Improved Case Fill Rate: The case fill rate increased from 94% to an impressive 98% within six months.

- Clear Communication with Customers: Daily measurement and analysis allowed for transparent communication with customers regarding delivery expectations.

- Focus on Root Causes: The ability to identify and address issues on a daily basis led to a focused effort on resolving root causes, particularly shipping delays and other factors impacting case fill rate.

- Customer Satisfaction: The proactive approach and enhanced communication resulted in increased customer satisfaction, demonstrating the positive impact of the implemented strategies.

 
 <br><br>
