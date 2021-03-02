---
layout: default
---

[home](./). [cv](./assets/files/CV.pdf). [research](./research.md). [teaching](./teaching.md). [thoughts](./thought.md). [personal](./hobby.md). [failed projects](./failed.md).

### research 

My dissertation is on learning to design and deliver interventions. I'm honored to be the winner of the 2021 Best Doctoral Dissertation Proposal Award at the American Statistical Association (Marketing Section).

<!--
#### general interests:
<ins>Topic:</ins> Video Advertising, Targeting Interventions, <br/>
Entertainment Commerce, Incentive Design<br/>
<ins>Method:</ins> Computer Vision, Reinforcement Learning, <br/>
Natural Language Processing, Causal Inference
-->

#### working papers:

<ins>**First Law of Motion: <br/>
Influencer Video Advertising on TikTok**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
**Jeremy Yang**<sup>*</sup>, Juanjuan Zhang, Yuhan Zhang

<!-- \- _Job Market Paper_<br/> -->

<ins>Abstract:</ins> This paper develops an algorithm to predict the effect of influencer video advertising on product sales. We propose the concept of _motion_, a summary statistic that captures the extent to which a product is advertised in the most engaging parts of a video. We locate product placement with an object detection algorithm, and estimate pixel-level engagement as a saliency map by fine-tuning a deep 3D convolutional neural network on video-level engagement data. Motion is then defined as the pixel-level, engagement-weighted advertising intensity of a video. We validate the algorithm with nearly 40,000 influencer video ads on TikTok, the largest short video platform in the world. We leverage variation in video posting time to identify the causal effect of video ads on product sales. Videos of higher motion indeed lift more sales. This effect is sizable, robust, and more pronounced among impulsive, hedonic, and lower-price products. We trace the mechanism to influencers' incentives to promote themselves rather than the product. We discuss how various stakeholders in entertainment commerce can use the motion metric in a scalable way to optimize content, align incentives, and improve efficiency.

presentation:<br/>
\- Marketing Innovation (MBA Core) Guest Lecture (MIT, 2021/5)<br/>
\- Marketing Seminar (Peking University, 2021/3)<br/>
\- Job Talk Seminar (Erasmus University, 2021/3)<br/>
\- Job Talk Seminar (Columbia University, 2021/2)<br/>
\- Job Talk Seminar (University of Toronto, 2021/2)<br/>
\- Job Talk Seminar (University of Virginia, 2021/2)<br/>
\- Job Talk Seminar (University of Washington, 2021/1)<br/>
\- Job Talk Seminar (Cheung Kong Graduate School of Business, 2021/1)<br/>
\- Job Talk Seminar (Harvard University, 2021/1)<br/>
\- Job Talk Seminar (HEC Paris, 2021/1)<br/>
\- Job Talk Seminar (Purdue University, 2021/1)<br/>
\- Job Talk Seminar (Hebrew University of Jerusalem, 2020/12)<br/>
\- Global Center For Big Data in Mobile Analytics (Temple University, 2020/12)<br/>
\- Conference on AI/ML (NYU, CMU & Temple University, 2020/12)<br/>
\- Job Talk Seminar (University of Hong Kong, 2020/11)<br/>
\- Human Cooperation Lab (MIT, 2020/11)<br/>
\- Conference on Digital Experimentation (MIT, 2020/11)<br/>
\- Marketing Seminar (MIT, 2020/11)<br/>
\- Marketing Innovation (MBA Core) Guest Lecture (MIT, 2020/11)<br/>
\- HBS Digital Doctoral Workshop (Harvard University, 2020/11)<br/>
\- PhD Seminar (MIT, 2020/5)<br/>
<!-- \- Social Analytics Lab (MIT, 2019/10)<br/> -->

<ins>**Targeting for Long-Term Outcomes**</ins><br/> 
**Jeremy Yang**, Dean Eckles, Paramveer Dhillon, Sinan Aral <br/> 

[<a href="https://arxiv.org/pdf/2010.15835.pdf">paper</a>] [[slides](./assets/files/targeting.pdf)] [<a href="https://www.dropbox.com/s/olf0gance8x95ag/targeting_informs.mov?dl=0">talk</a>] [<a href="https://www.dropbox.com/s/8wrw9wznyfplf5p/policy_learning_lecture.mp4?dl=0">lecture</a>] [<a href="https://twitter.com/deaneckles/status/1323396125601210372?s=20">tweet</a>] [<a href="http://ide.mit.edu/news-blog/blog/new-methods-improve-customer-targeting-business-outcomes">media</a>] 

Minor revision at _**Management Science**_<br/>

\- _Winner of the Best Paper Award at the INFORMS Annual Meeting (2020/11)_<br/>
\- _Nominated for the Best Student Paper Award at WISE (2020/11)_<br/>
\- _Accepted for Presentation at the QME Conference (2020/10)_<br/>
\- _Accepted for Presentation at NeurIPS (CausalML Workshop) (2019/12)_<br/>

<ins>Abstract:</ins> Decision-makers often want to target interventions (e.g., marketing campaigns) so as to maximize an outcome that is observed only in the long-term. This typically requires delaying decisions until the outcome is observed or relying on simple short-term proxies for the long-term outcome. Here we build on the statistical surrogacy and off-policy learning literature to impute the missing long-term outcomes and then approximate the optimal targeting policy on the imputed outcomes via a doubly-robust approach. We apply our approach in large-scale proactive churn management experiments at _The Boston Globe_ by targeting optimal discounts to its digital subscribers to maximize their long-term revenue. We first show that conditions for validity of average treatment effect estimation with imputed outcomes are also sufficient for valid policy evaluation and optimization; furthermore, these conditions can be somewhat relaxed for policy optimization. We then validate this approach empirically by comparing it with a policy learned on the ground truth long-term outcomes and show that they are statistically indistinguishable. Our approach also outperforms a policy learned on short-term proxies for the long-term outcome. In a second field experiment, we implement the optimal targeting policy with additional randomized exploration, which allows us to update the optimal policy for each new cohort of customers to account for potential non-stationarity. Over three years, our approach had a net-positive revenue impact in the range of $4-5 million compared to _The Boston Globe_'s current policies.

presentation:<br/>
\- American Economic Association Annual Meeting (Virtual, 2021/1)<br/>
\- Workshop on Information Systems and Economics (Virtual, 2020/12)<br/>
\- Inference and Statistics Reading Group (Lyft, 2020/12)<br/>
\- INFORMS Annual Meeting (Virtual, 2020/11)<br/>
\- Analytics Lab Guest Lecture (MIT, 2020/11)<br/>
\- Quantitative Marketing and Economics (Stanford University & UCLA, 2020/10)<sup>**</sup><br/>
\- International Conference on Computational Social Science (MIT, 2020/7)<br/>
\- Initiative on the Digital Economy Annual Conference (MIT, 2020/5)<br/>
\- Marketing Seminar (MIT, 2020/5)<br/>
\- NeurIPS CausalML Workshop (Vancouver Convention Center, 2019/12)<br/>
\- HBS Digital Doctoral Workshop (Harvard University, 2019/12)<br/>
\- Conference on Digital Experimentation (MIT, 2019/11)<br/>
\- Advances on Field Experiments (University of Chicago, 2019/7)<br/>
\- INFORMS Marketing Science (University of Roma Tre, 2019/6)<br/>

<!--
Abstract: TikTok is the most popular short video platform in the world with over 500M active users. We show three sets of early results using a unique dataset with detailed information on influencer created advertising videos, user engagement with the video (e.g., like, comment and share) and product page visits and sales on Douyin (the Chinese version of TikTok) : (1) by exploiting the differential timing of video posting, we use a difference in difference approach to estimate the causal effect of influencer advertising on product page visits and sales and calculate influencer ROI, (2) we use methods in computer vision to extract feature embeddings from the videos and show that video content and influencer fixed effect explains about the same amount of variation in sales, (3) somewhat surprisingly, user engagement with the video is not predictive of sales, it suggests that it might not be a good idea for brands to choose influencers based on past engagement if they want to generate short-term sales.
-->

<ins>**Identification and Bias-Amplification:<br/>
Latent Space Approach to Social Contagion on Observational Networks**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
**Jeremy Yang** <br/>

<ins>Abstract:</ins> In social networks, ego behavior is usually a function of the behaviors of her alters'. However, such social contagion or peer effect is hard to identify empirically using observational networks due to endogeneity in tie formation. The latent space models have been proposed under the assumption of assortative mixing as a method of modeling the underlying tie generating process, and it also has been used to adjust for unobserved homophily. At the meantime, Pearl (2009, 2010) suggested that adjusting for one common cause of treatment and outcome might actually increase the net bias by amplifying the bias introduced by an unadjusted confounder. The first part of the paper is on identification: I fit a latent space model to a classic dataset on the diffusion of medical innovation (Coleman et al., 1957,1966) to identify social contagion. The second part is on bias-amplification: I extend Pearl's framework to a nonlinear system and then use simulation to demonstrate that latent space adjustment can sometimes amplify the net bias, thus it should be used with caution.

<ins>**Uncertainty and Information Diffusion**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
T. Tony Ke, **Jeremy Yang**<sup>*</sup> 

<ins>Abstract:</ins> We investigate how uncertainty affects information diffusion. We analyze a dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015 where rumors are verified to be true or false at different time. We exploit the difference in the timing of verification to estimate the causal effect of uncertainty reduction on diffusion via difference-in-differences. We find that in some events the verification _decreases_ diffusion even for rumors that are true. This motivates a microfounded social learning model on the network that highlights the mechanism through which uncertainty shapes individual's incentive to share and thereby changing the pattern of diffusion. The model also offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even for information with similar content. 

presentation:<br/>
\- Marketing Seminar (MIT, 2017/11)<br/>


<ins>**Award No Longer Motivates Once You Are Awarded:<br/> 
A Field Experiment in Online Learning**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
Fan Bi, Qiang Feng, **Jeremy Yang**<sup>*</sup> 

<ins>Abstract:</ins> This paper studies the effect of social recognition and symbolic award on students’ effort and performance in an online English course in China. Students are randomly assigned to classes, study the materials and take quizzes on a daily basis. We conduct a two stage randomized experiment in which we first randomly assign classes to two treatment groups (pre-announced private or public award given out every week) and a control group, then within each treated class we randomly assign some students to actually receive the award conditional on their performance in the past week. We find that students who received the award exert _less_ effort in the future compared to students with similar past performance but did not receive the award due to randomization. They also do not exert more effort in the future than students with similar past performance in the control group. Students who did not receive the award due to randomization exert more effort and score higher in the future compared to students with similar past performance in the control group. There’s no difference between public and private recognition. Taken together, our results suggest that it is the possibility of being awarded (ex ante) that increases future effort and performance, receiving the award (ex post) actually lowers future effort. In other words, symbolic awards don't have a continuing motivating effect after you are awarded.

presentation:<br/>
\- PhD Seminar (MIT, 2020/10)<br/>
\- Organizational Economics Lunch (MIT, 2020/10)<br/>

<!--
Abstract: We investigate how uncertainty affects information sharing behavior. Using data on the spread of scientific news regarding the discovery of Higgs boson on Twitter in July 2012 we find that: (1) the main effect of uncertainty reduction on sharing probability is positive, (2) there's positive peer effect (crowding in) in the pre announcement or rumor phase that is characterized by piecemeal release of signals that are informative but noisy (high to medium uncertainty), (3) peer effect becomes negative (crowding out) in the post-announcement phase when the discovery is officially confirmed (low uncertainty) and (4) because of the negative interaction between information uncertainty and peer effect, when the number of sharing peers exceed some threshold, individuals are more likely to share when uncertainty is higher. This result suggests that the crowding in effect in rumor phase tends to amplify diffusion while the crowding out effect after confirmation tends to suppress diffusion. This motivates a simple learning model that highlights the mechanism through which uncertainty interacts with peer effects to drive the pattern of diffusion and offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even when the content of information is holding fixed. We further corroborate the result by analyzing a broader dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015.
-->

#### publications:
<ins>**Interdependence and the Cost of Uncoordinated Responses <br/>
to COVID-19**</ins> <br/>
David Holtz, Michael Zhao, Seth G. Benzell, Cathy Y. Cao, M. Amin Rahimiana, **Jeremy Yang**, Jennifer Allen, Avinash Collis, Alex Moehring, Tara Sowrirajan, Dipayan Ghosha, Yunhao Zhang, Paramveer S. Dhillon, Christos Nicolaides, Dean Eckles, Sinan Aral

**_Proceedings of the National Academy of Sciences (2020)_** [<a href="https://www.pnas.org/content/early/2020/07/29/2009522117">paper</a>]<br/>

<ins>Abstract:</ins> Social distancing is the core policy response to COVID-19. But as federal, state and local governments begin opening businesses and relaxing shelter-in-place orders worldwide, we lack quantitative evidence on how policies in one region affect mobility and social distancing in other regions and the consequences of uncoordinated regional policies adopted in the presence of such spillovers. We therefore combined daily, county-level data on shelter-in-place and business closure policies with movement data from over 27 million mobile devices, social network connections among over 220 million of Facebook users, daily temperature and precipitation data from 62,000 weather stations and county-level census data on population demographics to estimate the geographic and social network spillovers created by regional policies across the United States. Our analysis showed the contact patterns of people in a given region are significantly influenced by the policies and behaviors of people in other, sometimes distant, regions. When just one third of a state’s social and geographic peer states adopt shelter in place policies, it creates a reduction in mobility equal to the state’s own policy decisions. These spillovers are mediated by peer travel and distancing behaviors in those states. A simple analytical model calibrated with our empirical estimates demonstrated that the “loss from anarchy” in uncoordinated state policies is increasing in the number of non-cooperating states and the size of social and geographic spillovers. These results suggest a substantial cost of uncoordinated government responses to COVID-19 when people, ideas, and media move across borders.

<ins>**How Do Successful Scholars Get their Best Research Ideas? <br/>
An Exploration**</ins> <br/>
Cathy Cao, Xinyu Cao, Matthew Cashman, Madhav Kumar, Artem Timoshenko, **Jeremy Yang**<sup>*</sup>, Shuyi Yu, Jerry Zhang, Yuting Zhu, Birger Wernerfelt

**_Marketing Letters (2019)_** [<a href="https://mitsloan.mit.edu/shared/ods/documents/?PublicationDocumentID=5970">paper</a>]<br/> 

<ins>Abstract:</ins> We interview 24 marketing professors to ask how they got the ideas for 64 of their papers. More than three quarters of the papers were inspired by holes in the literature, by a “stylized fact” that the current literature cannot explain, or by an interaction with a manager. The rest fall into several smaller categories that to a large extent can be seen as special cases of the three big ones. We describe how papers from each of the three big categories help move the literature forward. We also illustrate the range of situations contained in each category by way of several examples. Among the authors we interview, most do not use a single source. As these authors become more senior, managerial contacts play an increasing role, while the balance between literature and stylized facts appears to be unchanged.

<!-- #### revise & resubmit:-->

#### selected work in progress:
<ins>Sequential Paywall Design with Reinforcement Learning</ins> <br/>
<ins>Activation: The Change of User Intention on TikTok</ins> <br/>
<ins>Attribution and Targeting without Apple IDFA</ins> <br/>

<!--
<ins>Misinformation on COVID-19</ins>
<ins>The Shape of Humor</ins> <br/>
<ins>Information Revelation and Diffusion</ins> [analysis & writing] <br/>
<ins>Using Bounded Outcome to Improve the Design of Exploration Policy</ins> [analysis & writing] <br/> 
<ins>Creative Decay: Predicting Advertisement Half-Life<br/>
-->
<sup>*</sup>Authors made equal contribution and are listed in an alphabetic order <br/>
<sup>**</sup>Presented by a co-author <br/>

[home](./)
