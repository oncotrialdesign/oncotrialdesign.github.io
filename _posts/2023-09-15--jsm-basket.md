---
layout: post
title: IDSWG Oncology JSM 2023 Reflection Part I
subtitle: Statistical Considerations in Basket Trial Design
tags: [JSM] [basket trial] [design]
comments: true
---

[IDSWG Oncology Group](https://oncotrialdesign.github.io/) was established in 2021 with the mission to Develop, Explore, Promote, and Implement innovative Clinical Trial (DEPICT) designs in cancer drug clinical development. The team consists of the subteams covering hot and challenging topics including RWD/RWE, master protocols, seamless development and oncology dosing. JSM is the largest statistical conference within our community, offering a veritable feast of statistical advances. Notably, the IDSWG Oncology Group also contributed to this event with a variety of engagements. I’d like to highlight two featured sessions organized by the team: Statistical Considerations in Basket Trial Design, and Seamless Late-Stage Development in Oncology – the Past Decade in Practice. 

# Statistical Considerations in Basket Trial Design

## Basket Trial Design in Exploratory Setting

<figure>
<img align="left" src="/assets/img/blog/2023_JSM_basket/fig1.png" alt="Figure 1">
</figure>

In recent years, the concept of basket trials (Figure 1) has emerged as a groundbreaking approach for assessing the effectiveness of targeted therapies across diverse tumor types, referred to as "baskets," that share a common molecular alteration or biomarker. This innovative basket trial design represents a fundamental departure from traditional oncology drug development, which typically focuses on the tumor's tissue of origin. Instead, basket trials open up a novel avenue for accelerating the delivery of potent targeted therapies to patients by prioritizing the underlying molecular characteristics over the organ where the tumor originates. This paradigm shift in clinical research offers a valuable opportunity to expedite the availability of effective targeted treatments to a broader spectrum of patients.

The FDA's approval of Pembrolizumab in May 2017 (Figure 2) for the treatment of unresectable/metastatic MSI-H or dMMR solid tumors represented a significant milestone in the pharmaceutical industry. This milestone served as a catalyst, inspiring the statistical community to develop innovative statistical designs capable of streamlining tumor-agnostic drug development efforts. These designs aim to maximize efficiency while also addressing potential heterogeneity that may exist across various tumor origins. 

Given the constraints of limited sample sizes within each tumor type, the adoption of Bayesian borrowing emerges as an attractive strategy to enhance the efficiency of studies. Several innovative approaches have been put forth to address this challenge. These methods include the Bayesian Hierarchical Model (BHM) introduced by Berry et al. (2013), the EXNEX approach by Neuenschwander et al. (2016), BCHM proposed by Chen and Lee (2020), CBHM as presented by Jiang et al. (2021), and the local-MEM method recently introduced by Liu et al. (2022).

Dr. Broglio (Astrazeneca) conducted research (Broglio et al 2022) that revealed how, in certain practical scenarios, the adoption of more complex models may yield only marginal additional benefits when compared to the simpler Bayesian Hierarchical Model (BHM) (Figure 3). Their findings emphasize that factors such as computational efficiency and the ease of interpretation for clinical study teams are pivotal considerations in real-world applications. In line with Broglio's conclusions, Dr. Zhou and colleagues (2023) conducted a comprehensive comparison involving seven different models and essentially concurred with Broglio's observations. Additionally, their research introduced the innovative concept of a local power prior approach. This approach not only delivered results on par with the more intricate models but also offered the advantage of closed-form posterior distributions, eliminating the need for time-consuming Markov Chain Monte Carlo (MCMC) sampling techniques. 
