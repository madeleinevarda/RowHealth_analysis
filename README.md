# Row Health Marketing Insights - Project Overview

Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. 

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims.

The entity relationship diagram can be found [here](https://github.com/madeleinevarda/RowHealth_analysis/blob/main/ERD.png).

The Tableau Dashboard can be found [here](https://public.tableau.com/views/rowhealth/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

The full presentation can be found [here].

# Insights Summary

In order to evaluate campaign performance, we focused on the following key metrics:

* **Click through Rate:** The percent of people who see a campaign and click on the associated link.
* **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
* **Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.

## Click through Rate (CTR) and Cost per Click (CPC) 

* Golden Years Security demonstrates poor performance with the highest Cost Per Click (CPC) at $0.48 and lowest Click-Through Rate (CTR) at 1.72%, especially when compared to Health for All, which achieved a remarkable 36% CTR and $0.05 CPC with significantly fewer impressions (120,492 vs. 348,510).
  
* The Healthy Living and Tailored Health Plans campaigns have nearly identical total impressions (Healthy Living at 1,372 and Tailored Health Plans at 1,398), but show notable differences in performance. Healthy Living has a higher CTR (9.62% vs. 6.62%) and slightly lower CPC ($0.05 vs. $0.06). Additionally, Healthy Living offers more diverse campaigns across 17 claim categories, compared to Golden Years Security's limited 6 categories, indicating a more comprehensive and potentially more appealing approach.
  
* The Summer Wellness Tip campaign stands out with the second-highest CTR at 17.01% and the lowest CPC at $0.02, making it a strong candidate for continued investment and potential expansion. Its efficient performance suggests it has found an effective way to engage the target audience with minimal cost.

## Signup Rate and Cost

* The Health Awareness Campaign was most successful in terms of overall signups (3,727), with the "Healthy Living" initiative driving this success through its impressive 3.72% signup rate and 3,279 signups. The campaign also included a "Product Promotion" initiative, which had a notably lower signup rate of 0.82% and 266 signups.
    
* Golden Years Security campaign is performing extremely poorly with a near-zero (0.01%) signup rate, only 23 signups, and the highest cost per signup at $124. The second highest cost per signup is 61% lower.
  
* While the overall Healthy Living campaign shows promise with a high 28% signup rate, its inititatives reveal significant variability. The Policy Information inititatives has a modest 0.46% signup rate, Health Tips at 0.22%, and most notably, the Offer Announcement has 0 signups despite 281,960 impressions.
  
* Almost all campaigns experienced a significant signup spike in April 2020 during the peak of COVID-19, with some campaigns like Tailored Health Plans and Preventative Care Plans showing additional high peaks in subsequent months, potentially correlating with different COVID strains and healthcare concerns.

## Claims Rate 

* Compare Health Coverage's campaign's exceptionally high average claim amount of $410 is primarily driven by the Customer Testimonial initiative, which has an astronomical average claim of $499. With total claims reaching $3,902,045, this raises serious questions about the campaign's cost-effectiveness and sustainability. The second-highest average claim amount comes from Preventitive Care News at $271, further highlighting the financial burden of this campaign.
  
* The Compare Health Coverage campaign experienced dramatic claim amount fluctuations during the pandemic, with significant spikes in August-September 2019 (74% increase) and a peak between April-May 2020 (94.1%).
  
* Notably, glucose monitoring claims dominated pre-pandemic but have since reduced in proportion, while entirely new claim categories like wound care, chemotherapy, CPAP/BiPAP supplies, and hospice care supplies only emerged in 2023, suggesting potential shifts in healthcare coverage or data collection methodologies.

# Reccomendations 

* **Overhaul/Discontinue:** Completely overhaul or discontinue the Golden Years Security campaign due to its extremely poor performance, as this campaign is consuming resources without delivering meaningful results. Reallocate its budget to more successful initiatives like the Health Awareness or Summer Wellness Tip campaigns, which demonstrate significantly better engagement and cost-effectiveness.
  
* **Investigate:** The Customer Testimonial initiative, part of the Compare Health Coverage campaign, is driving extraordinarily high claim amounts. Conduct a thorough review to understand why these claims are so high.
  
* **Expand/Invest More Resouces:** Exploit campaigns like Healthy Living and Compare Health Coverage which showed significant engagement during and after pandemic peaks. Within the Health for All campaign, focus on health awareness-type initiatives, and less on product promotion-type initiatives, which had low signup rate and CTR.

# Dashboard

This dashboard enables users to filter by plan, state, and campaign type and focuses on trends and values in marketing, signup, and claim metrics.

![Dashboard](https://github.com/user-attachments/assets/a6c7d17f-30a4-44d4-83b8-5bfd8e1ef0cd)

# Presentation Sample

The presentation created for the marketing team walks through the insights and reccomendations above and can be found here. Some extracts are presented below for easy viewing. 
