# Row Health Marketing Insights - Project Overview

Founded in 2016, Row Health is a medical insurance company serving thousands of customers throughout the United States. In 2019, they launched a new set of marketing campaign categories spanning topics like wellness tips, the affordability of their plans, and preventative care. 

Now that they’ve hired a new data team and are strategizing their marketing budget for the year, the company would like to build more understanding of the effectiveness of these campaign categories and how they relate to signups and subsequent patient claims.

The entity relationship diagram can be found [here](https://github.com/madeleinevarda/RowHealth_analysis/blob/main/ERD.png). 

# Executive Summary

Healthcare campaign performance analysis reveals "Health for All" as the standout program with a 2.94% signup rate, primarily driven by its Health Awareness campaign (3.72% signup rate). Post-pandemic trends show "Compare Health Coverage" and "Healthy Living" campaigns dominating customer acquisition, though "Compare Health Coverage" carries the highest average claim amount ($410) and has accumulated $3.9M in total claims. Significant spikes in both signup and claim metrics correlate with COVID-19 peaks, with April 2020 showing the most dramatic increases across most campaigns. Several underperforming programs, notably "Golden Years" (0.01% signup rate) and "Benefit Updates" (0.02% signup rate), require immediate evaluation or termination, while successful campaigns like "Healthy Living" present opportunities for expansion despite moderate costs per signup.

# Insights Summary

In order to evaluate campaign performance, we focused on the following key metrics:

* **Signup Rate:** The percent of people who see a campaign and subsequently sign up for a Row Health plan.
* **Cost per Signup:** The average dollars spent in order to acquire a signup from each campaign.
* **Click through Rate:** The percent of people who see a campaign and click on the associated link.


## Click Through Rate and Cost per Click 

* Golden Years Security demonstrates poor performance with the highest Cost Per Click (CPC) at $0.48 and lowest Click-Through Rate (CTR) at 1.72%, especially when compared to Health for All, which achieved a remarkable 36% CTR and $0.05 CPC with significantly fewer impressions (120,492 vs. 348,510).
* The Healthy Living and Tailored Health Plans campaigns have nearly identical total impressions (Healthy Living at 1,372 and Tailored Health Plans at 1,398), but show notable differences in performance. Healthy Living has a higher CTR (9.62% vs. 6.62%) and slightly lower CPC ($0.05 vs. $0.06). Additionally, Healthy Living offers more diverse campaigns across 17 claim categories, compared to Golden Years Security's limited 6 categories, indicating a more comprehensive and potentially more appealing approach.
* The Summer Wellness Tip campaign stands out with the second-highest CTR at 17.01% and the lowest CPC at $0.02, making it a strong candidate for continued investment and potential expansion. Its efficient performance suggests it has found an effective way to engage the target audience with minimal cost.

## Signup Rate and Cost

* The Health Awareness Campaign was most successful in terms of overall signups (3,727), with the "Healthy Living" initiative driving this success through its impressive 3.72% signup rate and 3,279 signups. The campaign also included a "Product Promotion" initiative, which had a notably lower signup rate of 0.82% and 266 signups.  
* Golden Years Security campaign is performing extremely poorly with a near-zero (0.01%) signup rate, only 23 signups, and the highest cost per signup at $124. The second highest cost per signup is 61% lower.
* While the overall Healthy Living campaign shows promise with a high 28% signup rate, its inititatives reveal significant variability. The Policy Information inititatives has a modest 0.46% signup rate, Health Tips at 0.22%, and most notably, the Offer Announcement has 0 signups despite 281,960 impressions. 
* Almost all campaigns experienced a significant signup spike in April 2020 during the peak of COVID-19, with some campaigns like Tailored Health Plans and Preventative Care Plans showing additional high peaks in subsequent months, potentially correlating with different COVID strains and healthcare concerns.

## Claims Rate 

# Reccomendations 

* Reallocate marketing resources from Golden Years Security to more effective campaigns like Health for All
* Golden Years Security needs immediate radical restructuring or should be completely eliminated due to its ineffectiveness.
* The Healthy Living campaign needs a deep-dive analysis into why some inititatives, most notably Offer Announement, are drastically underperforming and potentially require complete redesign or discontinuation.

# Dashboard

The dashboard can be found in Tableau Public here. This dashboard enables users to filter by X, X, and X and focuses on trends in X,X, and X. 

# Presentation Sample

The presentation created for the marketing team walks through the insights and reccomendations above and can be found here. Some extracts are presented below for easy viewing. 
