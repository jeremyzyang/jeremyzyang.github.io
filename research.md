---
layout: default
---

[home](./). [cv](./assets/files/CV.pdf). [research](./research.md). [talks](./talk.md). [teaching](./teaching.md). <br/>
[thoughts](./thought.md). [personal](./hobby.md). [failed projects](./failed.md).

### research 

My dissertation is on learning to design, deliver, and diffuse interventions, in which I study what treatment features make it effective (design), who should be targeted with what (deliver), and how to spread it (diffuse). It leverages machine learning and causal inference to develop data products for advertising, targeting, and pricing decisions.

My recent work focuses on understanding and solving important problems in the creator economy. My projects are organized around the 4Cs: creator, content, community, and commerce. On creator, I study creator inequality and bias. On content, I study what creative elements drive performance and the impact of generative models. On community, I study how creators build and engage a community. On commerce, I study creator monetization. 

<!--
My dissertation is on learning to design, deliver, and diffuse interventions, in which I study what treatment features make it effective (design), who should be targeted with what (deliver), and how to spread it (diffuse). 
I'm fortuante to have my training supervised by [Juanjuan Zhang](https://mitsloan.mit.edu/faculty/directory/juanjuan-zhang), [Sinan Aral](https://mitsloan.mit.edu/faculty/directory/sinan-kayhan-aral) (co-chairs), [Dean Eckles](https://mitsloan.mit.edu/faculty/directory/dean-eckles) at MIT, and [Vishal Singh](http://people.stern.nyu.edu/vsingh/index.html) at NYU. 
#### general interests:
<ins>Topic:</ins> Video Advertising, Targeting Interventions, <br/>
Entertainment Commerce, Incentive Design<br/>
<ins>Method:</ins> Computer Vision, Reinforcement Learning, <br/>
Natural Language Processing, Causal Inference
I'm fortuante to have my training supervised by [Juanjuan Zhang](https://mitsloan.mit.edu/faculty/directory/juanjuan-zhang), [Sinan Aral](https://mitsloan.mit.edu/faculty/directory/sinan-kayhan-aral) (co-chairs), and [Dean Eckles](https://mitsloan.mit.edu/faculty/directory/dean-eckles). Yes, pun intended. Outside of MIT, I'm working with . I'm also affiliated with the [Initiative on the Digital Economy](http://ide.mit.edu), [Social Analytics Lab](https://www.sinanaral.io/research/lab), [Behavioral Research Lab](https://brl.mit.edu), and the [American Statistical Association](https://www.amstat.org/).
-->

#### working papers:

<ins>**Engagement that Sells: <br/>
Influencer Video Advertising on TikTok**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>--> <br/>
Jeremy Yang<sup>*</sup>, Juanjuan Zhang, Yuhan Zhang

[<a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3815124">paper</a>] [<a href="https://www.dropbox.com/s/5358t0sdrv0uqay/first_law_of_motion_short.key?dl=0">slides</a>] [<a href="https://www.dropbox.com/s/385d8dnx9ooa08m/miw.mp4?dl=0">talk</a>] [<a href="https://twitter.com/jeremyzyang/status/1380897217423216643?s=20">tweet</a>] [<a href="https://medium.com/mit-initiative-on-the-digital-economy/what-makes-tiktok-video-ads-tick-9486ed94724c">media</a>]

Under 3rd Round Review at _Marketing Science_<br/>

\- _JMS China Annual Conference Best Paper Award (2021/11)_<br/>
\- _MSI Alden G. Clayton Doctoral Dissertation Award (2021/5)_<br/> 
\- _MIT Sloan Doctoral Research Forum Thesis Prize (2021/4)_<br/> 

<!-- \- _Job Market Paper_<br/> -->

<ins>Abstract:</ins> Many ads are engaging yet ineffective. This problem is exacerbated in influencer advertising when the incentives of influencers and advertisers are not perfectly aligned. This paper develops an algorithm to predict the effect of influencer video advertising on product sales. We propose the concept of product engagement score, or pe-score, to capture how engaging the product is as presented in an influencer video ad. We locate product placement with an object detection algorithm, and estimate pixel-level engagement as a saliency map by training a deep 3D convolutional neural network on
video-level engagement data. Pe-score is computed as the pixel-level, engagement-weighted product placement in a video. We construct and evaluate the algorithm with influencer video ads on TikTok, a leading short-form video platform. We leverage variation in video posting time to identify the causal effect of video ads on product sales. Videos with higher pe-scores indeed lift more sales. This effect is robust and more pronounced among impulsive, hedonic, or inexpensive products. We discuss how various stakeholders in influencer advertising can use pe-score in a scalable way to develop content, align incentives, and improve efficiency.

<!--
Abstract: TikTok is the most popular short video platform in the world with over 500M active users. We show three sets of early results using a unique dataset with detailed information on influencer created advertising videos, user engagement with the video (e.g., like, comment and share) and product page visits and sales on Douyin (the Chinese version of TikTok) : (1) by exploiting the differential timing of video posting, we use a difference in difference approach to estimate the causal effect of influencer advertising on product page visits and sales and calculate influencer ROI, (2) we use methods in computer vision to extract feature embeddings from the videos and show that video content and influencer fixed effect explains about the same amount of variation in sales, (3) somewhat surprisingly, user engagement with the video is not predictive of sales, it suggests that it might not be a good idea for brands to choose influencers based on past engagement if they want to generate short-term sales.
\- ISMS Marketing Science Conference, University of Roma Tre (2019/6)<sup>**</sup><br/>
\- Quantitative Marketing and Economics, Stanford & UCLA (2020/10)<sup>**</sup><br/>
-->

<!--
<ins>**Identification and Bias-Amplification: Latent Space Approach to Social Contagion on Observational Networks**</ins><br/> 
Jeremy Yang <br/>
<!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/>

<ins>Abstract:</ins> In social networks, ego behavior is usually a function of the behaviors of her alters'. However, such social contagion or peer effect is hard to identify empirically using observational networks due to endogeneity in tie formation. The latent space models have been proposed under the assumption of assortative mixing as a method of modeling the underlying tie generating process, and it also has been used to adjust for unobserved homophily. At the meantime, Pearl (2009, 2010) suggested that adjusting for one common cause of treatment and outcome might actually increase the net bias by amplifying the bias introduced by an unadjusted confounder. The first part of the paper is on identification: I fit a latent space model to a classic dataset on the diffusion of medical innovation (Coleman et al., 1957,1966) to identify social contagion. The second part is on bias-amplification: I extend Pearl's framework to a nonlinear system and then use simulation to demonstrate that latent space adjustment can sometimes amplify the net bias, thus it should be used with caution.

<ins>**Uncertainty and Information Diffusion**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/> <br/>
T. Tony Ke, Jeremy Yang<sup>*</sup> 

<ins>Abstract:</ins> We investigate how uncertainty affects information diffusion. We analyze a dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015 where rumors are verified to be true or false at different time. We exploit the difference in the timing of verification to estimate the causal effect of uncertainty reduction on diffusion via difference-in-differences. We find that in some events the verification _decreases_ diffusion even for rumors that are true. This motivates a microfounded social learning model on the network that highlights the mechanism through which uncertainty shapes individual's incentive to share and thereby changing the pattern of diffusion. The model also offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even for information with similar content. 

presentations:<br/>
\- Marketing Seminar, MIT (2017/11)<br/>
-->

<!--
Abstract: We investigate how uncertainty affects information sharing behavior. Using data on the spread of scientific news regarding the discovery of Higgs boson on Twitter in July 2012 we find that: (1) the main effect of uncertainty reduction on sharing probability is positive, (2) there's positive peer effect (crowding in) in the pre announcement or rumor phase that is characterized by piecemeal release of signals that are informative but noisy (high to medium uncertainty), (3) peer effect becomes negative (crowding out) in the post-announcement phase when the discovery is officially confirmed (low uncertainty) and (4) because of the negative interaction between information uncertainty and peer effect, when the number of sharing peers exceed some threshold, individuals are more likely to share when uncertainty is higher. This result suggests that the crowding in effect in rumor phase tends to amplify diffusion while the crowding out effect after confirmation tends to suppress diffusion. This motivates a simple learning model that highlights the mechanism through which uncertainty interacts with peer effects to drive the pattern of diffusion and offers a potential explanation to why rumors tend to diffuse wider and faster than verified news, even when the content of information is holding fixed. We further corroborate the result by analyzing a broader dataset that contains over 2400 rumors about 5 breaking news on Twitter from 2014-2015.

<ins>**Award No Longer Motivates Once You Are Awarded:<br/> 
A Field Experiment in Online Learning**</ins> <!--[<a href="">paper</a>][<a href=" ">slides</a>]<br/> 
Fan Bi, Qiang Feng, Jeremy Yang<sup>*</sup> 
<ins>Abstract:</ins> This paper studies the effect of social recognition and symbolic award on students’ effort and performance in an online English course in China. Students are randomly assigned to classes, study the materials and take quizzes on a daily basis. We conduct a two stage randomized experiment in which we first randomly assign classes to two treatment groups (pre-announced private or public award given out every week) and a control group, then within each treated class we randomly assign some students to actually receive the award conditional on their performance in the past week. We find that students who received the award exert _less_ effort in the future compared to students with similar past performance but did not receive the award due to randomization. They also do not exert more effort in the future than students with similar past performance in the control group. Students who did not receive the award due to randomization exert more effort and score higher in the future compared to students with similar past performance in the control group. There’s no difference between public and private recognition. Taken together, our results suggest that it is the possibility of being awarded (ex ante) that increases future effort and performance, receiving the award (ex post) actually lowers future effort. In other words, symbolic awards don't have a continuing motivating effect after you are awarded.
presentations:<br/>
\- Organizational Economics Lunch, MIT (2020/10)<br/> 
-->

#### publications:
<ins>**Targeting for Long-Term Outcomes**</ins><br/> 
Jeremy Yang, Dean Eckles, Paramveer Dhillon, Sinan Aral <br/> 

[<a href="https://pubsonline.informs.org/doi/abs/10.1287/mnsc.2023.4881">paper</a>] [[slides](./assets/files/targeting.pdf)] [<a href="https://www.dropbox.com/s/0dq0vgwgjund7qb/targeting_informs.mov?dl=0">talk</a>] [<a href="https://twitter.com/deaneckles/status/1323396125601210372?s=20">tweet</a>] [<a href="http://ide.mit.edu/news-blog/blog/new-methods-improve-customer-targeting-business-outcomes">media</a>] 

_Management Science (2023)_<br/>

\- _American Statistical Association Dissertation Award (2021/1)_<br/> 
\- _INFORMS Annual Meeting Best Paper Award (2020/11)_<br/>
\- _Accepted for Presentation at the NeurIPS Conference (2019/12)_<br/> 

<ins>Abstract:</ins> Decision makers often want to target interventions so as to maximize an outcome that is observed only in the long-term. This typically requires delaying decisions until the outcome is observed or relying on simple short-term proxies for the long-term outcome. Here we build on the statistical surrogacy and policy learning literatures to impute the missing long-term outcomes and then approximate the optimal targeting policy on the imputed outcomes via a doubly-robust approach. We first show that conditions for the validity of average treatment effect estimation with imputed outcomes are also sufficient for valid policy evaluation and optimization; furthermore, these conditions can be somewhat relaxed for policy optimization. We apply our approach in two large-scale proactive churn management experiments at The Boston Globe by targeting optimal discounts to its digital subscribers with the aim of maximizing long-term revenue.  Using the first experiment, we evaluate this approach empirically by comparing the policy learned using imputed outcomes with a policy learned on the ground-truth, long-term outcomes. The performance of these two policies is statistically indistinguishable, and we rule out large losses from relying on surrogates. Our approach also outperforms a policy learned on short-term proxies for the long-term outcome. In a second field experiment, we implement the optimal targeting policy with additional randomized exploration, which allows us to update the optimal policy for future subscribers. Over three years, our approach had a net-positive revenue impact in the range of $4-5 million compared to the status quo.

<ins>**Interdependence and the Cost of Uncoordinated Responses <br/>
to COVID-19**</ins> <br/>
David Holtz, Michael Zhao, Seth G. Benzell, Cathy Y. Cao, M. Amin Rahimiana, Jeremy Yang, Jennifer Allen, Avinash Collis, Alex Moehring, Tara Sowrirajan, Dipayan Ghosha, Yunhao Zhang, Paramveer S. Dhillon, Christos Nicolaides, Dean Eckles, Sinan Aral

_Proceedings of the National Academy of Sciences (2020)_ [<a href="https://ide.mit.edu/wp-content/uploads/2020/05/Interdependence_COVID_522.pdf">paper</a>]<br/>

<ins>Abstract:</ins> Social distancing is the core policy response to COVID-19. But as federal, state and local governments begin opening businesses and relaxing shelter-in-place orders worldwide, we lack quantitative evidence on how policies in one region affect mobility and social distancing in other regions and the consequences of uncoordinated regional policies adopted in the presence of such spillovers. We therefore combined daily, county-level data on shelter-in-place and business closure policies with movement data from over 27 million mobile devices, social network connections among over 220 million of Facebook users, daily temperature and precipitation data from 62,000 weather stations and county-level census data on population demographics to estimate the geographic and social network spillovers created by regional policies across the United States. Our analysis showed the contact patterns of people in a given region are significantly influenced by the policies and behaviors of people in other, sometimes distant, regions. When just one third of a state’s social and geographic peer states adopt shelter in place policies, it creates a reduction in mobility equal to the state’s own policy decisions. These spillovers are mediated by peer travel and distancing behaviors in those states. A simple analytical model calibrated with our empirical estimates demonstrated that the “loss from anarchy” in uncoordinated state policies is increasing in the number of non-cooperating states and the size of social and geographic spillovers. These results suggest a substantial cost of uncoordinated government responses to COVID-19 when people, ideas, and media move across borders.

<ins>**How Do Successful Scholars Get their Best Research Ideas? <br/>
An Exploration**</ins> <br/>
Cathy Cao, Xinyu Cao, Matthew Cashman, Madhav Kumar, Artem Timoshenko, Jeremy Yang<sup>*</sup>, Shuyi Yu, Jerry Zhang, Yuting Zhu, Birger Wernerfelt

_Marketing Letters (2019)_ [<a href="https://mitsloan.mit.edu/shared/ods/documents/?PublicationDocumentID=5970">paper</a>]<br/> 

<ins>Abstract:</ins> We interview 24 marketing professors to ask how they got the ideas for 64 of their papers. More than three quarters of the papers were inspired by holes in the literature, by a “stylized fact” that the current literature cannot explain, or by an interaction with a manager. The rest fall into several smaller categories that to a large extent can be seen as special cases of the three big ones. We describe how papers from each of the three big categories help move the literature forward. We also illustrate the range of situations contained in each category by way of several examples. Among the authors we interview, most do not use a single source. As these authors become more senior, managerial contacts play an increasing role, while the balance between literature and stylized facts appears to be unchanged.

<!-- #### revise & resubmit:-->
<!--
#### selected work in progress:
<ins>Sequential Paywall Design with Reinforcement Learning</ins> <br/>
<ins>Activation: The Change of User Intention on TikTok</ins> <br/>
<ins>Attribution and Targeting without Apple IDFA</ins> <br/>
<ins>Misinformation on COVID-19</ins>
<ins>The Shape of Humor</ins> <br/>
<ins>Information Revelation and Diffusion</ins> [analysis & writing] <br/>
<ins>Using Bounded Outcome to Improve the Design of Exploration Policy</ins> [analysis & writing] <br/> 
<ins>Creative Decay: Predicting Advertisement Half-Life<br/>
<sup>**</sup>Presented by a co-author <br/>
-->

<sup>*</sup>Authors are listed in an alphabetic order <br/>

[home](./)
