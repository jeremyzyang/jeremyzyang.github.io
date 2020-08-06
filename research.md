---
layout: default
---

[home](./). [cv](./cv.html). [research](./research.md). [teaching](./teaching.md). [thought](./thought.md). [hobby](./hobby.md). [failed projects](./failed.md).

### research (links to working papers coming soon) 

#### working paper:

<ins>**Targeting for Long-term Outcomes**</ins> [<a href="">paper</a>][<a href=" ">slides</a>]<br/>
**Jeremy Yang**, Dean Eckles, Paramveer Dhillon and Sinan Aral

<ins>Abstract:</ins> This paper studies the optimization of a targeting policy when the primary outcome of interest is observed only in the long-term. We build on the statistical surrogacy and off-policy learning literature to impute the missing long-term outcomes with a surrogate index and learn the optimal targeting policy on the imputed outcomes via a doubly robust approach. We apply our approach in large-scale proactive churn management experiments at the Boston Globe by targeting optimal discounts to its digital subscribers to maximize their long-term revenue. We first prove analytically that our approach is valid for policy evaluation and optimization, then we validate it empirically by comparing it with a policy learned on the ground truth long-term outcomes and show that they are statistically indistinguishable. Our approach also outperforms a policy learned on short-term proxies for the long-term outcome. We implement the optimal targeting policy via Bootstrapped Thompson Sampling (BTS), which allows us to update the optimal policy for each new cohort of customers to account for non-stationarity. Over three years, our approach had a net-positive revenue impact in the range of \$4-5 million compared to the Boston Globe's current policies.

presentations:<br/>
\- INFORMS Marketing Science (University of Roma Tre, 2019/6)<br/>
\- Advances on Field Experiments (University of Chicago, 2019/7)<br/>
\- CODE (MIT, 2019/11)<br/>
\- HBS Digital Doctoral Workshop (Harvard, 2019/12)<br/>
\- NeurIPS CausalML Workshop <br/> 
(Vancouver Convention Center, 2019/12)<br/> 
\- Marketing Seminar (MIT, 2020/5)<br/> 
\- IC2S2 (MIT, 2020/6)<br/> 

<ins>**First Law of Motion: <br/>
Influencer Video Advertising on TikTok**</ins> [<a href="">paper</a>][<a href=" ">slides</a>]<br/>
**Jeremy Yang**<sup>*</sup>, Juanjuan Zhang and Yuhan Zhang

presentations:<br/>
\- Social Analytics Lab (MIT, 2019/10)<br/>
\- PhD Seminar (MIT, 2020/5)<br/>

<!--
Abstract: TikTok is the most popular short video platform in the world with over 500M active users. We show three sets of early results using a unique dataset with detailed information on influencer created advertising videos, user engagement with the video (e.g., like, comment and share) and product page visits and sales on Douyin (the Chinese version of TikTok) : (1) by exploiting the differential timing of video posting, we use a difference in difference approach to estimate the causal effect of influencer advertising on product page visits and sales and calculate influencer ROI, (2) we use methods in computer vision to extract feature embeddings from the videos and show that video content and influencer fixed effect explains about the same amount of variation in sales, (3) somewhat surprisingly, user engagement with the video is not predictive of sales, it suggests that it might not be a good idea for brands to choose influencers based on past engagement if they want to generate short-term sales.
-->

<ins>**Information Revelation and Diffusion**</ins> [<a href="">paper</a>][<a href="">slides</a>]<br/>
T. Tony Ke, **Jeremy Yang**<sup>*</sup> 

presentations:<br/>
\- Marketing Seminar (MIT, 2017/11)<br/>

<!--
Abstract: We investigate how uncertainty affects information sharing behavior. Using data on the spread of scientific news regarding the discovery of Higgs boson on Twitter in July 2012 we find that: (1) the main effect of uncertainty reduction on sharing probability is positive, (2) there's positive peer effect (crowding in) in the pre announcement or rumor phase that is characterized by piecemeal release of signals that are informative but noisy (high to medium uncertainty), (3) peer effect becomes negative (crowding out) in the post-announcement phase when the discovery is officially confirmed (low uncertainty) and (4) because of the negative interaction between information uncertainty and peer effect, when the number of sharing peers exceed some threshold, individuals are more likely to share when uncertainty is higher. This result suggests that the crowding in effect in rumor phase tends to amplify diffusion while the crowding out effect after confirmation tends to suppress diffusion. This motivates a simple learning model that highlights the mechanism through which uncertainty interacts with peer effects to drive the pattern of diffusion and offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even when the content of information is holding fixed. We further corroborate the result by analyzing a broader dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015.
-->

#### publication:
<ins>**Interdependence and the Cost of Uncoordinated Responses <br/>
to COVID-19**</ins> [<a href="https://www.pnas.org/content/early/2020/07/29/2009522117">paper</a>]<br/>
**_Proceedings of the National Academy of Sciences (2020)_** <br/> 
David Holtz, Michael Zhao, Seth G. Benzell, Cathy Y. Cao, M. Amin Rahimiana, **Jeremy Yang**, Jennifer Allen, Avinash Collis, Alex Moehring, Tara Sowrirajan, Dipayan Ghosha, Yunhao Zhang, Paramveer S. Dhillon, Christos Nicolaides, Dean Eckles, Sinan Aral

<ins>Abstract:</ins> Social distancing is the core policy response to COVID-19. But as federal, state and local governments begin opening businesses and relaxing shelter-in-place orders worldwide, we lack quantitative evidence on how policies in one region affect mobility and social distancing in other regions and the consequences of uncoordinated regional policies adopted in the presence of such spillovers. We therefore combined daily, county-level data on shelter-in-place and business closure policies with movement data from over 27 million mobile devices, social network connections among over 220 million of Facebook users, daily temperature and precipitation data from 62,000 weather stations and county-level census data on population demographics to estimate the geographic and social network spillovers created by regional policies across the United States. Our analysis showed the contact patterns of people in a given region are significantly influenced by the policies and behaviors of people in other, sometimes distant, regions. When just one third of a state’s social and geographic peer states adopt shelter in place policies, it creates a reduction in mobility equal to the state’s own policy decisions. These spillovers are mediated by peer travel and distancing behaviors in those states. A simple analytical model calibrated with our empirical estimates demonstrated that the “loss from anarchy” in uncoordinated state policies is increasing in the number of non-cooperating states and the size of social and geographic spillovers. These results suggest a substantial cost of uncoordinated government responses to COVID-19 when people, ideas, and media move across borders.

<ins>**How do Successful Scholars Get their Best Research Ideas? <br/>
An Exploration**</ins> [<a href="https://mitsloan.mit.edu/shared/ods/documents/?PublicationDocumentID=5970">paper</a>]<br/> 
**_Marketing Letters (2019)_** <br/> 
Cathy Cao, Xinyu Cao, Matthew Cashman, Madhav Kumar, Artem Timoshenko, **Jeremy Yang**<sup>*</sup>, Shuyi Yu, Jerry Zhang, Yuting Zhu, Birger Wernerfelt

<ins>Abstract:</ins> We interview 24 marketing professors to ask how they got the ideas for 64 of their papers. More than three quarters of the papers were inspired by holes in the literature, by a “stylized fact” that the current literature cannot explain, or by an interaction with a manager. The rest fall into several smaller categories that to a large extent can be seen as special cases of the three big ones. We describe how papers from each of the three big categories help move the literature forward. We also illustrate the range of situations contained in each category by way of several examples. Among the authors we interview, most do not use a single source. As these authors become more senior, managerial contacts play an increasing role, while the balance between literature and stylized facts appears to be unchanged.

<!-- #### revise & resubmit:-->

#### selected work in progress:

<ins>It is the Possibility of Recognition not the Recognition itself that Increases Future Effort and Performance: A Field Experiment in Online Learning </ins> [writing] <br/> 
<ins>Using Bounded Outcome to Improve the Design of Exploration Policy</ins> [analysis & writing] <br/> 
<ins>Sequential Paywall Design with Reinforcement Learning</ins> [pilot experiment] <br/> 
<ins>Misinformation on COVID-19</ins> [data collection] <br/> 
<ins>Intertemporal Budget Allocation</ins> [experiment preparation]
<!--
<ins>Information Revelation and Diffusion</ins> [analysis & writing] <br/>
-->

*authors listed in alphabetic order

[home](./)
