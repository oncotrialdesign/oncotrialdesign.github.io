---
layout: post
title: IDSWG Oncology JSM 2023 Reflection Part II
subtitle: Seamless Late-Stage Development in Oncology – the Past Decade in Practice
author: Philip He
tags: [JSM, seamless, design]
comments: true
---

[IDSWG Oncology Group](https://oncotrialdesign.github.io/) was established in 2021 with the mission to Develop, Explore, Promote, and Implement innovative Clinical Trial (DEPICT) designs in cancer drug clinical development. The team consists of the subteams covering hot and challenging topics including RWD/RWE, master protocols, seamless development and oncology dosing. Joint Statistical Meeting (JSM) is the largest statistical conference within our community, offering a veritable feast of statistical advances. Notably, the IDSWG Oncology subteam also contributed to this event with a variety of engagements. I’d like to highlight two featured sessions organized by the team: **Statistical Considerations in Basket Trial Design**, and **Seamless Late-Stage Development in Oncology – the Past Decade in Practice**. 

# Seamless Late-Stage Development in Oncology – the Past Decade in Practice

Seamless designs are a type of study design that enables a smooth transition from one phase of a clinical trial to another within a single clinical protocol, eliminating the need for multiple protocol developments and pauses. Typically, a confirmatory seamless design includes two distinct phases: the exploratory phase and the confirmatory phase. Within this framework, various adaptive design types can be incorporated to enhance the study's efficiency and flexibility. Over the past two decades, numerous seamless designs have been proposed to accommodate a wide range of adaptive features. These include considerations such as population selection, as discussed in works by Chen et al. (2013), Li et al. (2013), Posch et al. (2016), and Li et al. (2019); regimen/dose optimization by Jin et al. (2012) and Jin and Zhang (2022); and endpoint selection, as highlighted in studies by Xu et al. (2023) and Sinha et al. (2022). These innovative seamless design approaches aim to enhance the efficiency and robustness of clinical trials while maintaining methodological rigor.

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_seamless/fig1.png" alt="Figure 1">
<figcaption>Figure 1 - Use of Seamless Study Designs for registrational purpose
<br/>Source: Dr. Dong’s Presentation
</figcaption>
</figurecenter>

## Use of seamless study designs 

During this session, Dr. Dong delivered a presentation titled "Use of Seamless Study Designs for Regulatory Approval in Oncology Clinical Development" (Figure 1). The practical utilization of these designs was summarized based on therapeutic areas, regulatory feedback received, and whether Stage 1 data were used in Stage 2, distinguishing between inferential and operational approaches (Figure 2). The data used in this analysis were collected through a questionnaire distributed to the ASA biopharmaceutical section and IDSWG email list between August and September 2022. Dr. Broglio's presentation, titled "Adaptive Seamless Design in Late-Phase Oncology Development – A Systemic Meta-Analysis of Real Clinical Cases," reinforced the findings by summarizing available confirmatory seamless phase 2/3 designs based on publicly available sources. The analysis identified a total of 68 trials, revealing that the most common feature of these designs was gating on safety or efficacy, while the least common features included population selection and arm/dose selection. Interestingly, no examples of endpoint selection were identified (Figure 2).

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_seamless/fig2.png" alt="Figure 2">
<figcaption>Figure 2 - Practical use and regulatory feedbacks
<br/>Source: Dr. Dong’s Presentation (Top) and Dr. Broglio’s Presentation (Bottom)
</figcaption>

</figurecenter>

Furthermore, the data indicated a rising trend in the adoption of seamless development over time. This increase in usage could be attributed to the FDA's guidance on adaptive design, which was initially issued in draft form in 2010 and finalized in 2019. Notably, recent examples of seamless designs in oncology included applications in dose selection under the FDA's Project Optimus initiative. Additionally, the growing prevalence of targeted therapies among investigational cancer drugs suggests a potential uptake in the application of enrichment designs in the future. These insights highlight the evolving landscape of adaptive seamless designs in oncology clinical development and their growing importance in the regulatory approval process.

## 2-IN-1 Design

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_seamless/fig3.png" alt="Figure 3">
<figcaption>Figure 3 - 2-IN-1 Design and Considerations of Sequential P2/3, Adaptive P2/3 and Straight P3</figcaption>
</figurecenter>

A significant recent advancement in the field of seamless phase 2/3 designs is the introduction of the 2-IN-1 design (Figure 9). This innovative approach allows for the seamless expansion of a phase 2 study into a phase 3 study if it meets predefined efficacy criteria. Importantly, it also provides the opportunity to claim efficacy based on the unexpanded phase 2 data. In addition, Notably, this design permits flexibility in using different endpoints for interim decision (X), the phase 2 part (Y), and the phase 3 part (Z), as long as they meet the condition ρ(θ_X,θ_Y)≥ρ(θ_X,θ_Z). Multiple studies have implemented this innovative design, for example INDUCE-3 study (Hansen et al 2020).

Dr. Liu's presentation included two informative case studies illustrating the evaluation of the operating characteristics and considerations when employing the 2-IN-1 design. These case studies provided insights into the practical applications of this design for both regular approval and accelerated approval (AA) scenarios. Furthermore, Dr. Liu emphasized the importance of assessing suitable scenarios for the use of the 2-IN-1 design within the context of phase 2/3 development. This assessment should take into account factors such as commercial value and scientific merit to make informed decisions about the appropriateness of implementing this innovative design approach. 

## Multi-Arm Multi-Stage (MAMS) Designs in Project Optimus

<figureleft>
<img class="center" src="/assets/img/blog/2023_JSM_seamless/fig4.png" alt="Figure 4">
<figcaption>Figure 4 - A typical P2/3 design diagram in Project Optimus
<br/>Source: Dr. Kumar’s Presentation
</figcaption>
</figureleft>

One approach to optimizing oncology dose selection involves conducting a seamless phase 2/3 study with the dose selection phase integrated into phase 2, typically within the first stage (Figure 4). During the session, Dr. Kumar presented a talk titled “Multi-Arm Multi-Stage (MAMS) Designs: Challenges and Solutions” that can be used for optimal dose selection while not slowing down drug development, addressed the statistical challenges associated with implementing this approach and presented potential solutions based on recent experiences and research findings. Dr. Kumar's insights included considerations for trial design, statistical methodologies, and decision-making process. 
Dr. Kumar's presentation (Figure 10) included a discussion of two approaches for combining p-values of the two stages of a Phase 2/3 seamless MAMS design to control type I error. The two methods discussed were the events-based method and the subjects-based method. Simulation results were shared to show which methods control Type I error control better when a binary end-point is used for treatment/dose selection and time to event end-point is used for confirmatory decision. Dr. Kumar's presentation also discussed the potential reduction in statistical power when different endpoints are used for treatment selection in Phase 2 and confirmatory Phase 3. He showed that the extent of this power reduction depends on the level of concordance between the two endpoints. These insights are invaluable, as they offer practical guidance for researchers and trial designers when implementing the Phase 2/3 design in dose optimization trials.

<figurecenter>
<img class="center" src="/assets/img/blog/2023_JSM_seamless/fig5.jpg" alt="Figure 5">
<figcaption>Figure 5 - Key session contributors for Seamless Late-Stage Development in Oncology – the Past Decade in Practice</figcaption>
</figurecenter>

Dr. Thomas Gwise summarized the presentations and highlighted design points that were often called out by regulatory authorities. He emphasized the need for good communication when communicating complex statistical concepts to cross-disciplinary audiences.
The session was organized by Dr. Philip He (Daiichi Sankyo Inc.), chaired by Dr. Feifang Hu (George Washington University), and joined by discussant Dr. Thomas Gwise (Gwise Consulting LLC). 
Despite its placement in the last half day of the conference, the session managed to attract a significant audience in the room. The session featured presentations and contributions from several key individuals, including A. Kumar, F. Liu, Y. Dong, K. Broglio, P. He, F. Cooner, T. Gwise, and F. Hu, as shown in Figure 11.


Disclaimer: Please note the views and opinions expressed in this presentation are those of the author and are not intended to reflect the views and/or opinions of Daiichi Sankyo.

## References
1.	Chen YH, Chappell R (2012). Adaptive designs for clinical trials with biomarkers. Journal of Biopharmaceutical Statistics. DOI: 10.1080/10543406.2012.644869
2.	Li Y, Liu L, Lee JJ, et al. (2013). Adaptive population enrichment designs in clinical trials. Journal of Biopharmaceutical Statistics. DOI: 10.1080/10543406.2013.813201
3.	Posch M, Koenig F (2016). Adaptive designs for confirmatory clinical trials with subgroup selection. Pharmaceutical Statistics. DOI: 10.1002/pst.1791
4.	Li M, Lawrence J, Rosenberger WF (2019). Adaptive population enrichment designs: A review. Journal of Biopharmaceutical Statistics. DOI: 10.1080/10543406.2019.1619316
5.	Jin Y, Yin G (2012). Adaptive designs for dropping treatment arms in clinical trials: A review. Contemporary Clinical Trials. DOI: 10.1016/j.cct.2011.08.007
6.	Jin, M and Zhang P (2022). A Seamless Adaptive 2-in-1 Design Expanding a Phase 2 Trial for Treatment or Dose Selection Into a Phase 3 Trial. Statistics in Biopharmaceutical Research. DOI: 10.1080/19466315.2021.1914717
7.	Jin Y, Yin G (2012). Adaptive designs for dropping treatment arms in clinical trials: A review. Contemporary Clinical Trials. DOI: 10.1016/j.cct.2011.08.007
8.	Jin, M and Zhang P (2022). A Seamless Adaptive 2-in-1 Design Expanding a Phase 2 Trial for Treatment or Dose Selection Into a Phase 3 Trial. Statistics in Biopharmaceutical Research. DOI: 10.1080/19466315.2021.1914717
9.	Hansen AR et al (2020). INDUCE-3: A randomized, double-blind study of GSK3359609 (GSK609), an inducible T-cell co-stimulatory (ICOS) agonist antibody, plus pembrolizumab (PE) versus placebo (PL) plus PE for first-line treatment of PD-L1-positive recurrent/metastatic head and neck squamous cell carcinoma (R/M HNSCC). DOI: 10.1200/JCO.2020.38.15_suppl.TPS6591 Journal of Clinical Oncology 38, no. 15_suppl. Published online May 25, 2020.


