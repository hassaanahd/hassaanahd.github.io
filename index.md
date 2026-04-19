---
layout: home
---

I’ll skip the “deep” philosophical debate over my existence—it might be interesting, but probably not what anyone wants to read here. Still, I should share a few things about myself, even if their full relevance isn’t obvious.

One late night, while struggling to understand the Quantum Fourier Transform, I found myself wondering: Why did I take on this challenge? The answer was simple enough, but the realization had a profound impact. I challenge myself because I know I am capable of more. With the semester ending and my master’s degree close to completion, I just can’t stop now.

It made sense to continue because my mind was not driven by distractions, but by ambition. I sought the support of my mentors and finally took the plunge.

My current research is in Earth system physics, focusing on learning models from data—models that could help guide better climate policies and decision-making. Step by step, I hope these efforts will contribute to meaningful change. In today’s age of accessible information, change can feel slow or hard to notice—but it’s always necessary. Real impact starts with personal growth, and only then can one influence the wider world.

This journey is more about reinventing myself.

---

**Ongoing Voyages**
Regions dependent on groundwater for domestic supply and irrigation are experiencing increasing stress due to prolonged extraction and declining recharge. This, combined with the lack of viable alternative sources, makes quantitative assessment of long-term sustainability essential. Such assessment must account not only for the physical dynamics of the aquifer but also for the behavioral heterogeneity of communities that drive extraction patterns.  
In this work, each Sub-Watershed Region (HUC12) of the United States’ High Plains Aquifer is modeled as a community-level agent within an affine parametric socio-ecological system [1]. We emphasize that this formulation assumes a fixed interaction structure and aggregates complex local dynamics into community-level representations, which may introduce modeling bias due to spatial and behavioral heterogeneity. The conditions required for the validity of the within-community homogeneity assumption are discussed in [1].  
To estimate the unknown parameters of this system, we employ Dynamic Mode Decomposition with Control (DMDc) [2], which provides a reduced-order representation while preserving the affine structure of the underlying dynamics. DMDc identifies a best-fit linear operator from spatio-temporal snapshot data, enabling system identification in a data-driven manner.  
The dataset consists of monthly groundwater withdrawal aggregates [3] and groundwater level measurements from monitoring wells across the High Plains Aquifer [4]. Groundwater levels are used as a proxy for aquifer storage, under the assumption of approximate proportionality between observed head changes and storage variations.
Preliminary results demonstrate that the proposed framework can recover interpretable community-scale interaction patterns and dominant consumption modes from aggregate data.
However, limitations remain in terms of identifiability under sparse observations and sensitivity to aggregation assumptions. These results provide a data-driven basis for future development of groundwater sustainability and policy analysis frameworks.  

References:  
[1] T. Manzoor, E. Rovenskaya, A. Muhammad, IFAC-PapersOnLine 50, 7675 (2017).
[2] J. L. Proctor, S. L. Brunton, J. N. Kutz, SIAM J. Appl. Dyn. Syst. 15, 142 (2016).
[3] U.S. Geological Survey, Water Resources Mission Area, Water Use in the United States (2023), accessed 2025-08-15.
[4] U.S. Geological Survey, National Ground-Water Monitoring Network Data Portal (2025), accessed 2025-08-15.
[5] H. Ahmed, A. Muhammad, Inferring Community-Level Interaction Structures in Groundwater Consumption Using Dynamic Mode Decomposition with Control (DMDc), accepted (to appear) in IFAC World Congress 2026
