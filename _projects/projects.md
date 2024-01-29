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
•	Defining Data Sources: Collaborating with the planning team, I gathered requirements for dashboard. I extracted master data from SAP and categorized it into various material categories. Using color-coded stock levels, I added an interactive visualization for current and future stock status relative to safety stock. For future weeks' projections, I used key figures from SAP Advanced Planning Optimizer(APO) planning books based on material types, such as total demand, total receipts, stock on hand, max stock, and safety stock.
•	Data Integration: While developing the dashboard, I faced data challenges where the data flow was inconsistent. I utilized SAP BI reports to access the latest data, although several data update issues persisted. After a couple of months of regular monitoring and updating process flow in Tableau, I refined the dashboard based on the feedback from trial runs. The refresh frequency aligned with the planning team's review schedule.

__Warehouse Capacity Dashboard__
•	Created Master Data file: I collaborated with the local warehouse team to understand their capacity calculations to solve the warehouse capacity issue. As system master data was unavailable for warehouse management, I had to create a master file detailing all materials used at the China plant, along with pertinent data for each SKU, including pallet size, maximum pallet quantity, batch size, MOQ, warehouse location, and storage location.
•	Dashboard Layout: The dashboard was divided into current and future week capacity, color-coded to indicate capacity levels compared with maximum available capacity. Future weeks' capacity was calculated using demand and consumption from SAP APO.

Results

•	Integrated Projected Stock Alert dashboard into weekly KPI review meetings, resulting in proactive management and fewer stock-outs.
•	Introduced weekly warehouse capacity review meetings using Warehouse Capacity dashboard, leading to a 95% reduction in overutilization issues.
•	Identified top contributors to capacity constraints for timely resolution.
•	Streamlined issue escalation and communication processes, resulting in an annual savings of approximately 3000 person-hours.
•	Dashboards were implemented across other Novo Nordisk production sites, generating indirect cost savings through reduced operational costs and efficient material management
<br><br>

## __Real-time Vehicle Detection and Classification in Aerial Scenes [Oct '17 - Mar '18]__ 
***

<p class="full-width"><img src="/public/pic006.jpg" style="width:36rem;height:20rem" align="left"/></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

- Identified the shortcomings of the existing one-stage object detectors for aerial scenes. To address their shortcomings, proposed a modified Convolutional Neural Network by introducing ConvRes blocks at multiple scales to preserve salient features of small-sized objects such as cars, trucks, planes, boats, and heavy vehicles in satellite and drone imagery using Darknet framework and CUDA.
- Generated a new data set by collecting aerial images from open sources and demonstrated the efficacy of the model by conducting experiments on three challenging data sets VEDAI, DLR-3K, and DOTA. 
- Benchmarked performance against the existing state-of-the-art approaches in terms of mAP, computational and space complexity.
- Above image is model's sample prediction in aerial view.
<br><br>

## __Retrieval Patterns of Physical Objects from Retail Sales [Oct '21 - Dec '21]__ 
***

<p class="full-width"><img src="/public/pic008.jpg" style="width:36rem;height:20rem" align="left"/></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

 - Implemented Prod2Vec model which uses the local product co-occurrence information established by the product sequences to create a distributed representation of products and recommends similar products. 
 - Performed comparative analysis of GloVe, FastText and Word2Vec models on retail product embeddings.
 - Above image is model's product embeddings visualised for one product and its neighbors in Tensorflow Embedding Projector. <br><br>

## __First-Person Activity Recognition in Videos [Oct '21 - Dec '21]__ 
***

<p class="full-width"><img src="/public/pic009.jpg" style="width:36rem;height:20rem" align="left"/></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

[Image Credits](http://michaelryoo.com/papers/cvpr2013_ryoo.pdf){:target="_blank"}<br>

 - Finetuned ImageNet pre-trained Resnet50 CNN model to serve as a feature extractor and using it performed classification task on JPL interaction video frames to identify activities such as hugging, waving, punching etc. in PyTorch and OpenCV. 
 - Temporal pooling was used to extract spatial features in a given time window. <br><br>

## __Airbnb Customer Review Sentiment Analysis [Oct '21 - Dec '21]__ 
***

<p class="full-width"><img src="/public/pic007.jpg" style="width:36rem;height:20rem" align="left"/></p><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

[Image Credits](http://www.gabormelli.com/RKB/Bidirectional_LSTM_%28BiLSTM%29_Model){:target="_blank"}<br>

 - Built a fair price prediction model for Airbnb listings using range of methods like support vector regression, random forest regression and gradient boosting models. 
 - Performed multi-class customer review sentiment analysis using pretrained word embeddings and bidirectional LSTM model using Tensorflow with training dataset consisting of 10+ million customer reviews. <br><br>
