---
layout: default
---

[home](./). [cv](./cv.html). [research](./research.md). [teaching](./teaching.md). [thought](./thought.md). [hobby](./hobby.md). [failed projects](./failed.md).

### research 

<!--
#### research interests:
<ins>Topic:</ins> Targeting, Advertising, Diffusion, Entertainment & Commerce, Behavioral Economics & Consumer Behavior<br/>
<ins>Method:</ins> Causal Inference (Experimental and Observational), Machine Learning (Computer Vision and Reinforcement Learning)
-->

#### working papers (links coming soon):

<ins>**First Law of Motion: <br/>
Influencer Video Advertising on Douyin**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
**Jeremy Yang**<sup>*</sup>, Juanjuan Zhang, Yuhan Zhang

<ins>Abstract:</ins> This paper develops an algorithm to predict the effect of influencer video ads on product sales by computing a summary statistics that we term _Motion_. _Motion_ captures pixel-level spatio-temporal interaction between content engagement and product placement in a video. Analogous to a fundamental law in Newtonian mechanics, _Motion_ (sales conversion) is generated when the object (product placement) is impressed with a force (content engagement) in the space and time (video). We validate the algorithm with an analysis of 40,000 influencer video ads on Douyin, the Chinese version of TikTok and the largest short-video platform in the world. We exploit variation in video posting time to identify the causal effect of video ads on sales via difference-in-differences. Videos of higher _Motion_ are more effective in driving sales conversion. This effect is sizable, robust, and is more pronounced among impulsive, hedonic, lower-priced products, and more informative ads. We trace the mechanism to influencers’ incentives to optimize for engagement rather than sales. We discuss how product sellers can use _Motion_ as a novel contractual lever to mitigate the principle-agent problem for greater ROI.

presentations:<br/>
\- Social Analytics Lab (MIT, 2019/10)<br/>
\- PhD Seminar (MIT, 2020/5)<br/>
\- HBS Digital Doctoral Workshop (Harvard, 2020/11)<br/>
\- Marketing Seminar (MIT, 2020/11)<br/>


<ins>**Targeting for Long-term Outcomes**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]--> <br/>
**Jeremy Yang**, Dean Eckles, Paramveer Dhillon, Sinan Aral

<ins>Abstract:</ins> This paper studies the optimization of a targeting policy when the primary outcome of interest is observed only in the long-term. We build on the statistical surrogacy and off-policy learning literature to impute the missing long-term outcomes with a surrogate index and learn the optimal targeting policy on the imputed outcomes via a doubly robust approach. We apply our approach in large-scale proactive churn management experiments at the Boston Globe by targeting optimal discounts to its digital subscribers to maximize their long-term revenue. We first prove analytically that our approach is valid for policy evaluation and optimization, then we validate it empirically by comparing it with a policy learned on the ground truth long-term outcomes and show that they are statistically indistinguishable. Our approach also outperforms a policy learned on short-term proxies for the long-term outcome. We implement the optimal targeting policy via Bootstrapped Thompson Sampling (BTS), which allows us to update the optimal policy for each new cohort of customers to account for non-stationarity. Over three years, our approach had a net-positive revenue impact in the range of \$4-5 million compared to the Boston Globe's current policies.

presentations:<br/>
\- INFORMS Marketing Science (University of Roma Tre, 2019/6)<br/>
\- Advances on Field Experiments (University of Chicago, 2019/7)<br/>
\- Conference on Digital Experimentation (MIT, 2019/11)<br/>
\- HBS Digital Doctoral Workshop (Harvard, 2019/12)<br/>
\- NeurIPS CausalML Workshop (Vancouver Convention Center, 2019/12)<br/>
\- Marketing Seminar (MIT, 2020/5)<br/>
\- International Conference on Computational Social Science (MIT, 2020/7)<br/>
\- Quantitative Marketing and Economics (Stanford & UCLA, 2020/10)<br/>
\- INFORMS Annual Meeting (Virtual, 2020/11)<br/>
\- American Economic Association Annual Meeting (Virtual, 2021/1)<br/>

<!--
Abstract: TikTok is the most popular short video platform in the world with over 500M active users. We show three sets of early results using a unique dataset with detailed information on influencer created advertising videos, user engagement with the video (e.g., like, comment and share) and product page visits and sales on Douyin (the Chinese version of TikTok) : (1) by exploiting the differential timing of video posting, we use a difference in difference approach to estimate the causal effect of influencer advertising on product page visits and sales and calculate influencer ROI, (2) we use methods in computer vision to extract feature embeddings from the videos and show that video content and influencer fixed effect explains about the same amount of variation in sales, (3) somewhat surprisingly, user engagement with the video is not predictive of sales, it suggests that it might not be a good idea for brands to choose influencers based on past engagement if they want to generate short-term sales.
-->

<ins>**Information Revelation and Diffusion**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
T. Tony Ke, **Jeremy Yang**<sup>*</sup> 

presentations:<br/>
\- Marketing Seminar (MIT, 2017/11)<br/>

<!--
Abstract: We investigate how uncertainty affects information sharing behavior. Using data on the spread of scientific news regarding the discovery of Higgs boson on Twitter in July 2012 we find that: (1) the main effect of uncertainty reduction on sharing probability is positive, (2) there's positive peer effect (crowding in) in the pre announcement or rumor phase that is characterized by piecemeal release of signals that are informative but noisy (high to medium uncertainty), (3) peer effect becomes negative (crowding out) in the post-announcement phase when the discovery is officially confirmed (low uncertainty) and (4) because of the negative interaction between information uncertainty and peer effect, when the number of sharing peers exceed some threshold, individuals are more likely to share when uncertainty is higher. This result suggests that the crowding in effect in rumor phase tends to amplify diffusion while the crowding out effect after confirmation tends to suppress diffusion. This motivates a simple learning model that highlights the mechanism through which uncertainty interacts with peer effects to drive the pattern of diffusion and offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even when the content of information is holding fixed. We further corroborate the result by analyzing a broader dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015.
-->

<ins>**Award no longer Motivates once it's Awarded:<br/>
A Field Experiment in Online Learning**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
Fan Bi, Qiang Feng, **Jeremy Yang**<sup>*</sup> 

<ins>Abstract:</ins> This paper studies the effect of social recognition and symbolic award on students’ effort and performance in an online English course in China. Students are randomly assigned to classes and take quizzes on a weekly basis. We conduct a two stage randomized experiment in which we first randomly assign classes to two treatment groups (pre-announced private or public recognition) and a control group, then within each treated class we randomly assign some students to receive the recognition and award conditional on their past performance. We find that students who received the award exert _less_ effort in the future compared to students with similar past performance but didn’t receive the award due to randomization. There’s no significant difference in future performance. We also find that students who didn’t receive the award due to randomization exert more effort and score higher in the future compared to students with similar past performance in the control group. There’s no effect on students at lower end of the performance distribution who wouldn’t have had the chance to be awarded. Perhaps surprisingly, there’s also no difference between public and private recognition. Taken together, our results show that award only motivates when it's not awarded. In other words, award is an effective motivating tool ex ante, but not ex post.

presentations:<br/>
\- Organizational Economics Lunch (MIT, 2020/10)<br/>

#### publications:
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
<ins>Sequential Paywall Design with Reinforcement Learning</ins> <br/>
[pilot experiment completed] <br/> 
<ins>Intertemporal Budget Allocation in Digital Advertising</ins> <br/>
[experiment preparation] <br/>
<ins>Misinformation on COVID-19</ins> [data collection]

<!--
<ins>Information Revelation and Diffusion</ins> [analysis & writing] <br/>
<ins>Using Bounded Outcome to Improve the Design of Exploration Policy</ins> [analysis & writing] <br/> 
-->
*Authors made equal contribution and are listed in an alphabetic order

[home](./)
