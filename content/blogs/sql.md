---
title: "Unveiling the Performance of A Movie Rental Business: An SQL Analysis"
date: 2024-04-01T22:53:58+05:30
draft: false
github_link: "https://github.com/gurusabarish/hugo-profile"
author: "Phi Nguyen"
image: /images/projects/powerbi.jpg
description: ""
toc:
---

I was tasked with a vital project to analyze the performance of our Movie Rental Business, with a focus on providing valuable insights for potential acquirers and enhancing our company’s ability to showcase its strengths. Through detailed SQL queries, I aimed to deliver a clear and compelling picture of the business's operational health and financial performance.

## 1. Understanding Our Customer Base

To begin with, I tackled the challenge of understanding our customer base. I restructured the customer data to provide a clearer picture of their activity status, transforming it from numerical values to more descriptive labels like 'Active' and 'Non-Active'. This change made the data more intuitive and user-friendly.
\
I then compiled a detailed list that includes:
* Customer Names: First and last names.
* Store Affiliations: Which store they are associated with.
* Activity Status: Whether they are currently active or not.
* Complete Addresses: Street address, city, and country.

This detailed overview equips potential acquirers with essential information about our customer demographics and geographical distribution, which is crucial for assessing market reach and engagement.

{{< figure src="/images/sql1.png" alt="Scholarship Management" >}}

## 2. Evaluating Customer Value
Understanding the financial impact of our customer base was a key focus. By aggregating data on customer rentals and payments, I created a report highlighting:

- Customer Names: First and last names.
- Country: Their country of residence.
- Total Rentals: The total number of rentals made by each customer.
- Total Payment Amount: The sum of payments received from each customer.


Sorting by total payment amount helps identify our most valuable customers, providing potential acquirers with insight into customer loyalty and revenue generation. This information is essential for evaluating the business’s financial performance and future growth potential.
{{< figure src="/images/sql2.png" alt="Scholarship Management" >}}

## 3. Detailed Inventory Analysis
I also provided a comprehensive overview of our inventory, showcasing:

- Store ID and Inventory ID
- Film Titles and Ratings
- Rental Rates and Replacement Costs


This data offers a clear picture of the film assortment available at each store and the associated costs. Additionally, I summarized inventory counts by film rating at each store, giving insight into inventory distribution and demand.
{{< figure src="/images/sql3.png" alt="Scholarship Management" >}}

## 4. Investor and Advisor Transparency
Transparency regarding our board of advisors and investors was crucial. I compiled a list that includes:
- Names and Titles
- Company Associations: For investors

This list provides potential acquirers with a clear understanding of the individuals and entities involved in our business, enhancing their insight into our governance and stakeholder relationships.
{{< figure src="/images/sql4.png" alt="Scholarship Management" >}}

## 5. Analysis of Replacement Costs
Finally, I analyzed inventory based on replacement costs, detailing:

- Film Count and Average Replacement Cost: Categorized by store and film category.
- Total Replacement Cost: For each film category at every store.

This analysis helps potential acquirers understand the financial implications of changes in film popularity and inventory costs. It provides valuable insight into how we manage and mitigate inventory-related expenses.
{{< figure src="/images/sql5.png" alt="Scholarship Management" >}}

## Explore: Interactive Insights with Power BI
To gain deeper insights into the data extracted from the SQL reports, I have imported the five generated tables into Power BI. This powerful tool allows for a more detailed and interactive analysis. Sit back and enjoy the video, where I showcase the insights and visualizations derived from this data, offering a comprehensive view of the business performance.

[Click Here to Watch My Project Video](https://youtu.be/uNPPWKbOTjo)
