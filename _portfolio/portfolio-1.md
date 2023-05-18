---
title: "Text-based mutual fund strategy similarity"
excerpt: "item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---
This databank contains fund-year level "review" similarity ratio either on a cross-sectional level or a time-series level. I borrow the idea from Hoberg and Phillips (2010， 2016) and Cohen et al. (2020) for their insightful research. 

I crawl down all the mututal fund annually reports from EastMoney.com and complement the missing files from CNInfo.com. I extract the disscusion and prospectus section as raw copora, and calculate the either the cross-sectional or the time-series similarity score. The calculation method is based on the cosine similarity. 

For the cross-sectional similarity score, I compute the textual similarity of fund A and fund B on year t that belong to the same investment category. Then, I calculate the average similarity for the focal fund by taking average value of its similarity score with other funds. This measure is a simple replication of the famous Hoberg and Philips's business similarity (2010, 2016), but in the context of Chinese mutual fund market. Interestingly, this is a quite unique setting, which is totally different from the fund prospectus (Notable research by Simona Abis) or shareholder letters (Alexander Hillert who basically pioneered this one). However, there is still 

![shiba1](/images/portfolio/csbycategory.png)
