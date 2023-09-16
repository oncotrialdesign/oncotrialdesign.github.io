---
layout: post
title: IDSWG Oncology JSM 2023 Reflection Part I
subtitle: Statistical Considerations in Basket Trial Design
author: Philip He
tags: [JSM, basket trial, design]
comments: true
---

[IDSWG Oncology Group](https://oncotrialdesign.github.io/) was established in 2021 with the mission to Develop, Explore, Promote, and Implement innovative Clinical Trial (DEPICT) designs in cancer drug clinical development. The team consists of the subteams covering hot and challenging topics including RWD/RWE, master protocols, seamless development and oncology dosing. Joint Statistical Meeting (JSM) is the largest statistical conference within our community, offering a veritable feast of statistical advances. Notably, the IDSWG Oncology subteam also contributed to this event with a variety of engagements. I’d like to highlight two featured sessions organized by the team: **Statistical Considerations in Basket Trial Design**, and **Seamless Late-Stage Development in Oncology – the Past Decade in Practice**. 

# Statistical Considerations in Basket Trial Design

## Basket Trial Design in Exploratory Setting

<figureleft>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig1.png" alt="Figure 1">
<figcaption>Figure 1 - Basket Trial Concept
<br/>Source: HealthScientific.net
</figcaption>
</figureleft>

In recent years, the concept of basket trials (Figure 1) has emerged as a groundbreaking approach for assessing the effectiveness of targeted therapies across diverse tumor types, referred to as "baskets," that share a common molecular alteration or biomarker. This innovative basket trial design represents a fundamental departure from traditional oncology drug development, which typically focuses on the tumor's tissue of origin. Instead, basket trials open up a novel avenue for accelerating the delivery of potent targeted therapies to patients by prioritizing the underlying molecular characteristics over the organ where the tumor originates. This paradigm shift in clinical research offers a valuable opportunity to expedite the availability of effective targeted treatments to a broader spectrum of patients.

The FDA's approval of Pembrolizumab in May 2017 (Figure 2) for the treatment of unresectable/metastatic MSI-H or dMMR solid tumors represented a significant milestone in the pharmaceutical industry. This milestone served as a catalyst, inspiring the statistical community to develop innovative statistical designs capable of streamlining tumor-agnostic drug development efforts. These designs aim to maximize efficiency while also addressing potential heterogeneity that may exist across various tumor origins. 

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig2.png" alt="Figure 2">
<figcaption>Figure 2 - FDA Approved Tissue-Agnostic Therapies Since 2017</figcaption>
</figurecenter>

Given the constraints of limited sample sizes within each tumor type, the adoption of Bayesian borrowing emerges as an attractive strategy to enhance the efficiency of studies. Several innovative approaches have been put forth to address this challenge. These methods include the Bayesian Hierarchical Model (BHM) introduced by Berry et al. (2013), the EXNEX approach by Neuenschwander et al. (2016), BCHM proposed by Chen and Lee (2020), CBHM as presented by Jiang et al. (2021), and the local-MEM method recently introduced by Liu et al. (2022).

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig3.png" alt="Figure 3">
<figcaption>Figure 3 - A Comparison of Different Approaches to Bayesian Hierarchical Models for Basket Trials 
<br/>Source: Dr. Broglio’s Presentation</figcaption>
</figurecenter>

Dr. Broglio (Astrazeneca) conducted research (Broglio et al 2022) that revealed how, in certain practical scenarios, the adoption of more complex models may yield only marginal additional benefits when compared to the simpler Bayesian Hierarchical Model (BHM) (Figure 3). Their findings emphasize that factors such as computational efficiency and the ease of interpretation for clinical study teams are pivotal considerations in real-world applications. In line with Broglio's conclusions, Dr. Zhou and colleagues (2023) conducted a comprehensive comparison involving seven different models and essentially concurred with Broglio's observations. Additionally, their research introduced the innovative concept of a local power prior approach. This approach not only delivered results on par with the more intricate models but also offered the advantage of closed-form posterior distributions, eliminating the need for time-consuming Markov Chain Monte Carlo (MCMC) sampling techniques. 

## ROAR Case Study

<figureleft>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig4.png" alt="Figure 4">
<figcaption>Figure 4 - ROAR Study Considers BRAF-V600E Mutation in 9 Rare Tumors
<br/>Source: Dr. Redhu’s Presentation
</figcaption>
</figureleft>

Dr. Redhu (Novartis) presented the innovative ROAR (Rare Oncology Agnostic Research) study design (Figure 4). The ROAR was an open-label, non-randomized phase 2 study, with plans to enroll a total of 225 subjects. Within this study, a maximum of 25 subjects were permitted to be enrolled in each of the nine rare cancer groups characterized by the presence of the BRAF V600E mutation. The primary endpoint of the study was the Overall Response Rate (ORR) and the secondary endpoints include Duration of Response (DOR), Progression-Free Survival (PFS), Overall Survival (OS), and safety (Wen et al 2022 and Subbiah et al 2022).

This study led to tumor agnostic (solid tumors) indication approval of the combination therapy of dabrafenib and trametinib in June 2022. The study's design relied on a Bayesian hierarchical model, which facilitated the dynamic borrowing of information between groups. This borrowing was contingent on the degree of consistency observed among these groups; more borrowing occurred when they exhibited similarity, while less borrowing when differences were evident. The model's structure involved two key stages: the utilization of a data-driven borrowing approach via the Dirichlet Process Mixture (DPM) model, followed by the implementation of Hierarchical Models with Clustering.

Furthermore, the study design offered the flexibility of stopping the study early due to efficacy, based upon the posterior distribution indicating substantial evidence of treatment efficacy. This adaptive approach is particularly well-suited for rare tumor studies characterized by limited resources. ROAR study represents a significant advancement in clinical research, showcasing how innovative study designs and Bayesian methodologies can lead to important advancements in oncology treatment.

## Basket Trial Design in Confirmatory Setting

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig5.png" alt="Figure 5">
<figcaption>Figure 5 - Generalized Randomized Confirmatory Basket Trials: Efficiency, Type I Error Control, and a Simulated Application
<br/>Source: Dr. Beckman’s Presentation
</figcaption>
</figurecenter>

Basket trials predominantly take the form of phase 2 exploratory studies, with their primary aim being the identification of promising tumor types for further development in subsequent phases. Approvals from basket trials have been single arm studies of exceptional drugs in terminal disease settings, using short term endpoints (Beckman et al, 2016). However, if basket trial designs are to be generalized to the majority of drugs, to earlier lines of therapy, and to time to event endpoints that measure clinical benefit, they will need to be randomized, as discussed by the French Health Technology Assessment Group (Lengline et al 2021). A generalized approach to Phase 3 development using randomized basket trials could have a dramatic effect on the efficiency of drug development given the large amount of resources expended in Phase 3, as highlighted by the research in Chen et al. (2016), Li et al. (2017), and Beckman et al. (2016). A search conducted by Dr. He on July 29, 2023, using clinicaltrials.gov and focusing on trials with "basket" in their official study title, revealed a total of 67 oncology drug interventional trials. Among these trials, 4 were labeled as phase 1, 13 as phase 1 / 2, 49 as phase 2, and only 1 trial (DETERMINE) was identified as phase 2 / 3, suggesting its deployment in a confirmatory setting. 

During the session, Dr. Beckman from Georgetown University discussed the considerations and challenges associated with randomized confirmatory basket trial designs (Figure 5), particularly emphasizing the importance of controlling type I errors and the fact that several definitions of “type I error control” are possible within the basket trial setting. He presented a simulated application in three auto-immune diseases in which the development efficiency was nearly doubled and the type I error was controlled at the level that would have resulted from three parallel trials. He further showed how the simulation inputs for rare diseases could be refined using real world evidence of off-label use from the Georgetown/MEDSTAR healthcare system. Dr. He from Daiichi Sankyo, the discussant, further contributed insights on the considerations surrounding type I errors in clinical trials, highlighting potential sources of type I error (Figure 6). 

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_basket/fig6.png" alt="Figure 6">
<figcaption>Figure 6 - Confirmatory Basket Trial – What is the type I error?
<br/>Source: Dr. He’s Presentation
</figcaption>
</figurecenter>

This collaborative discussion, organized by Dr. Freda Cooner (Eli Lilly) and chaired by Dr. Hiya Banerjee (Eli Lilly), attracted significant interest from the audience and made substantial contributions to the broader scientific community's understanding of basket trials in both exploratory and confirmatory settings.

Disclaimer: Please note the views and opinions expressed in this presentation are those of the author and are not intended to reflect the views and/or opinions of Daiichi Sankyo.

## References
1.	Berry, S. M., Broglio, K. R., Groshen, S., & Berry, D. A. (2013). Bayesian hierarchical modeling of patient subpopulations: efficient designs of phase II oncology clinical trials. Clinical Trials, 10(5), 720-734.
2.	Neuenschwander, B., Wandel, S., Roychoudhury, S., & Bailey, S. (2016). Robust exchangeability designs for early phase clinical trials with multiple strata. Pharmaceutical statistics, 15(2), 123-134.
3.	Chen, N., & Lee, J. J. (2020). Bayesian cluster hierarchical model for subgroup borrowing in the design and analysis of basket trials with binary endpoints. Statistical Methods in Medical Research, 29(9), 2717-2732..
4.	Jiang, L., Li, R., Yan, F., Yap, T. A., & Yuan, Y. (2021). Shotgun: A Bayesian seamless phase I-II design to accelerate the development of targeted therapies and immunotherapy. Contemporary clinical trials, 104, 106338.
5.	Liu, Y., Kane, M., Esserman, D., Blaha, O., Zelterman, D., & Wei, W. (2022). Bayesian local exchangeability design for phase II basket trials. Statistics in medicine, 41(22), 4367-4384.
6.	Broglio, K. R., Zhang, F., Yu, B., Marshall, J., Wang, F., Bennett, M., & Viele, K. (2022). A Comparison of Different Approaches to Bayesian Hierarchical Models in a Basket Trial to Evaluate the Benefits of Increasing Complexity. Statistics in Biopharmaceutical Research, 14(3), 324-333.
7.	Wen PY et al. Dabrafenib plus trametinib in patients with BRAFV600E-mutant low-grade and high-grade glioma (ROAR): a multicentre, open-label, single-arm, phase 2, basket trial. Lancet Oncol. 2022 Jan;23(1):53-64. doi: 10.1016/S1470-2045(21)00578-7. Epub 2021 Nov 24. PMID: 34838156.
8.	Subbiah V et al. Dabrafenib plus trametinib in patients with BRAF V600E-mutant anaplastic thyroid cancer: updated analysis from the phase II ROAR basket study. Ann Oncol. 2022 Apr;33(4):406-415. doi: 10.1016/j.annonc.2021.12.014. Epub 2022 Jan 10. PMID: 35026411; PMCID: PMC9338780.
9.	Chen, C., Li, X., Yuan, S., Antonijevic, Z., Kalamegham, R., & Beckman, R. A. (2016). Statistical design and considerations of a phase 3 basket trial for simultaneous investigation of multiple tumor types in one study. Statistics in Biopharmaceutical Research, 8, 248–257.
10.	Li, W., Chen, C., Li, X., & Beckman, R. A. (2017). Estimation of treatment effect in two-stage confirmatory oncology trials of personalized medicines. Statistics in Medicine, 36, 1843–1861.
11.	Beckman, R., Antonijevic, Z., Kalamegham, R., & Chen, C. (2016). Adaptive design for a confirmatory basket trial inmultiple tumor types based on a putative predictive biomarker. Clinical Pharmacology & Therapeutics, 100, 617–625.
12.	Lengliné E et al. Basket clinical trial design for targeted therapies for cancer: a French National Authority for Health Statement for health technology assessment. Lancet Oncol. 2021; 22: e430-34.
13.	DETERMINE (Determining Extended Therapeutic Indications for Existing Drugs in Rare Molecularly Defined Indications Using a National Evaluation Platform Trial) - Master Screening Protocol (DETERMINE). ClinicalTrials.gov Identifier: NCT05722886 https://classic.clinicaltrials.gov/ct2/show/NCT05722886

