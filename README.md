# Fog/Edge management: A survey of source codes

This page reviews the source codes found, during my research works, of Fog/Edge management solutions published in the literature.
It also reports some Fog-Edge Computing simulators/frameworks, often-used data traces, Fog/Edge topologies, IoT applications, and Fog/Edge Computing Projects.

## Preface

**This repo aims to:**
  - Simplify access to references for users and facilitate the comparison of their proposals with the existing approaches.

  - Serve as a guideline for future research.
  
  - Help researchers learn and build Awesome Fog management strategies.
  
Do not hesitate to contribute to this page by providing source codes that I have not reported and thus enriching this repo. Any idea, you can create an issue or PR here.

I classify the identified source codes according to the addressed Fog-Edge Computing issue, i.e., Resource allocation, Service placement, and Computation Offloading; the type of the resolution approach; and the programming languages.

<!-- ## Table of contents
__TOC__ 


```


```
-->



## A. Fog management issues 
---

### A.1. Resource allocation

>#### + Mathematical Programming/Constraint Programming
  - [Python] [Santos, J., Wauters, T., Volckaert, B., & De Turck, F. (2021). **"Towards end-to-end resource provisioning in Fog Computing over Low Power Wide Area Networks"**. Journal of Network and Computer Applications, 175, 102915.](https://www.sciencedirect.com/science/article/pii/S108480452030374X?casa_token=2FYO7SqZA8sAAAAA:yKx48A2x0iUnWZEX2Gf4B3UDLl85a9dadX1wh_EqfaL7-msHDKsPNbiWBv-FmFApB07-l8nbXxI) [[**Source code**]](https://github.com/jpedro1992/gym-fog)
  
  >#### + Deep Reinforcement Learning
  - [Python] [Santos, J., Wauters, T., Volckaert, B., & De Turck, F. (2021). **"Resource provisioning in fog computing through deep reinforcement learning."**](http://dl.ifip.org/db/conf/im/im2021mini/210942.pdf) [[**Source Code**]](https://github.com/jpedro1992/gym-fog)
  - [Python] [Towers, M (2020). **"Reinforcement learning agents for online flexible resource allocation in mobile Edge Computing"**.](https://github.com/pseudo-rnd-thoughts/Online-Flexible-Resource-Allocation/blob/master/final_report/final_report.pdf) [[**Source Code**]](https://github.com/pseudo-rnd-thoughts/Online-Flexible-Resource-Allocation)

  >#### + PSO (Particle Swarm Optimization)
  - [Java] [Fakhfakh, F., Neji, A., Cheikhrouhou, S., & Kallel, S. (2019). **"Optimizing the performance of timed-constrained business processes in cloud-fog environment"**. In International Conference on Model and Data Engineering (pp. 78-90). Springer, Cham.](https://link.springer.com/chapter/10.1007/978-3-030-32213-7_6) [[**Source Code**]](https://github.com/fairouz1/PSO4CFS)
   
  >#### + Heuristics
  - [Go] [Agrawal, N., Rellermeyer, J., & Ding, A. Y. (2019). **"IoT resource-aware orchestration framework for edge computing"**. In Proceedings of the 15th International Conference on emerging Networking EXperiments and Technologies (pp. 62-64).](https://dl.acm.org/doi/pdf/10.1145/3360468.3368179?casa_token=mER71yHQzV8AAAAA:ONmXtsyzZQUuzokUgOOE7S78p49ex1E7TibCvY-i9MrspvVdQpf5udMptmALjRxNutOLNuV8CCZQbA) [[**Source Code**]](https://github.com/niketagrawal/EDIRO)
  - [Java] [Li, C., Zhuang, H., Wang, Q., & Zhou, X. (2018). **"SSLB: Self-Similarity-Based Load Balancing for Large-Scale Fog Computing"**. Arabian Journal for Science & Engineering (Springer Science & Business Media BV), 43(12).](https://link.springer.com/article/10.1007/s13369-018-3169-3) [[**Source Code**]](https://github.com/liclong/IoTSim)
  - [Java] [Vieira, J. C. R (2019).  **"Fog and Cloud Computing Optimization in Mobile IoT Environments"**.](https://fenix.tecnico.ulisboa.pt/downloadFile/563345090418720/Thesis.pdf) [[**Source Code**]](https://github.com/JoseCVieira/FogComputingSim)
  - [Java] [Sharma, S., & Saini, H. (2019). **"A novel four-tier architecture for delay aware scheduling and load balancing in fog environment"**. Sustainable Computing: Informatics and Systems, 24, 100355.](https://www.sciencedirect.com/science/article/pii/S2210537919300885?casa_token=53Ff2g11paYAAAAA:Sa1adkFNMwdGoUVf-VJ3UAX5TWUoXxTZYCCsIAfpXKaMwL25PV8_DUvnd1UgBuhjxGvp1JXepaw) [[**Source Code**]](https://github.com/ManikandanRJSM/ifogsim_loadbalance)

  
### A.2. Service placement

>#### + Mathematical Programming/Constraint Programming
 - [Java] [Aït-Salaht, F., Desprez, F., & Lebre, A. (2020). **"An overview of service placement problem in fog and edge computing"**. ACM Computing Surveys (CSUR), 53(3), 1-35.](https://hal.inria.fr/hal-02313711/document) [[**Source code**]](https://github.com/ASFarah/SPP)
 - 
>#### + Partition-based optimization
- [Python] [Lera, I., Guerrero, C., & Juiz, C. (2018). **"Availability-aware service placement policy in fog computing based on graph partitions"**. IEEE Internet of Things Journal, 6(2), 3641-3651.](https://ieeexplore.ieee.org/iel7/6488907/6702522/08588297.pdf?casa_token=4kcKkjISfRsAAAAA:Nxm6TU3pfsk9VqE2dvHoeZa7kBvqoxqBbyRqYzvjygRDgMWjLdTmHfz_oP2jvGl_Z9mEbAyGY4I) [[**Source code**]](https://github.com/acsicuib/FogServicePlacement-ILPvsCN)

>#### + Genetic-based Algorrithms
- [Python] [Guerrero, C., Lera, I., & Juiz, C. (2019). **"Evaluation and efficiency comparison of evolutionary algorithms for service placement optimization in fog architectures"**. Future Generation Computer Systems, 97, 131-144.](https://www.sciencedirect.com/science/article/pii/S0167739X18325147) [[**Source code**]](https://github.com/acsicuib/GA4FogPlacement)
 - [Matlab] [Hoseiny, F., Azizi, S., Shojafar, M., Ahmadiazar, F., & Tafazolli, R. (2021, May). **"PGA: a priority-aware genetic algorithm for task scheduling in heterogeneous fog-cloud computing"**. In IEEE INFOCOM 2021-IEEE Conference on Computer Communications Workshops (INFOCOM WKSHPS) (pp. 1-6). IEEE.](https://ieeexplore.ieee.org/iel7/9484327/9484428/09484436.pdf?casa_token=9pQu1j06ZrIAAAAA:nuKLSIfbbqfaIr3_7oRbqD0vQ-dZnT3IR4WP7D6529kZJ9scpb50GiKQ3pSrrkFoZKDxiKvONrw) [[**Source Code**]](https://github.com/mshojafar/sourcecodes/blob/master/Azizi2021-INFOCOM-PGA_Sourcecode.zip)

>#### + Honey Bee Algorithm
- [Java] [Faragardi, H. R., et al. (2018). **"A time-predictable fog-integrated cloud framework: One step forward in the deployment of a smart factory"**. In  IEEE RTEST. pp. 54-62.](http://www.es.mdh.se/pdf_publications/5019.pdf) [[**Source code**]](https://github.com/HamidFaragardi/fog-integrated_industrial_iot)

>#### + Heuristics
- [Java] [Sarkar, S., Chatterjee, S., & Misra, S. (2015). **"Assessment of the Suitability of Fog Computing in the Context of Internet of Things"**. IEEE Transactions on Cloud Computing, 6(1), 46-59.](https://ieeexplore.ieee.org/abstract/document/7286781/?casa_token=X4JrECCDGdYAAAAA:OMsMVEhzKIFA4ZZv5wHQbzDkpkSXYzebWmQm0tAdadto0vAVnWe8GYv_hzQbFFlKGoSxCzYQBjQ) [[**Source code**]](https://github.com/SravaniSegireddy/Fog_Cloud)
 - [Java] [Cardellini, V., Grassi, V., Lo Presti, F., & Nardelli, M. (2016, June). **"Optimal operator placement for distributed stream processing applications"**. In ACM International Conference on Distributed and Event-based Systems (pp. 69-80).](https://dl.acm.org/doi/pdf/10.1145/2933267.2933312?casa_token=MBxNigAFgkMAAAAA:eCIBmpmZeSFxM8VMpP3w8NRMIrN28bqksU-idlDpeUbMxQEGYMdLjtMyZkda4p7nNcCeBJl_kJP77Q) [[**Source code**]](https://github.com/gmarciani/opmap)
 - [Java] [Guerrero, C., Lera, I., & Juiz, C. (2019). **"A lightweight decentralized service placement policy for performance optimization in fog computing"**. Journal of Ambient Intelligence and Humanized Computing, 10(6), 2435-2452.](https://link.springer.com/article/10.1007/s12652-018-0914-0) [[**Source Code**]](https://github.com/carlosguerrero/iFogSimPopularityPlacement)
 - [Python] [Brogi, A., Forti, S., Guerrero, C., & Lera, I. (2020, October). **"Towards declarative decentralised application management in the fog"**. In 2020 IEEE International Symposium on Software Reliability Engineering Workshops (ISSREW) (pp. 223-230). IEEE.](https://ieeexplore.ieee.org/iel7/9307608/9307628/09307726.pdf?casa_token=pOqUq3sMlloAAAAA:frp7zyZfUk76FU7XZpiJSQfDRSjsKJDtEGH4ualMdk7nsONvxP2eeM641snhbjt8qBB60_IWH1U) [[**Source code**]](https://github.com/acsicuib/MARIO/tree/gauss2020)
 - [Java] [Yousefpour, A. et al. (2019). **"FOGPLAN: A lightweight QoS-aware dynamic fog service provisioning framework"**. IEEE Internet of Things Journal, 6(3), 5080-5096.](https://ieeexplore.ieee.org/iel7/6488907/6702522/08629987.pdf?casa_token=5EkHKT418NgAAAAA:QiCB4UMBeIvP2G0-Y7oyZa34zFcg1jIIF1ZCP0KM35_JQVpMaXmTVdKLYQY_I4xkYBzgBxucQrI) [[**Source code**]](https://github.com/ashkan-software/FogPlan-simulator)
 - [Java] [Naas, M. I., Parvedy, P. R., Boukhobza, J., & Lemarchand, L. (2017). **"iFogStor: an IoT data placement strategy for fog infrastructure"**. In IEEE ICFEC. pp. 97-104.](https://ieeexplore.ieee.org/abstract/document/8014365/?casa_token=2EzLsjY5oPgAAAAA:uSdqIXtMMhfpPZX5lMjrBBnQ_bbeJJUyxXjdl5M0wqJWdX9VIBCS8BTFREvcehR1AnOspgkSDHk) [[**Source code**]](https://github.com/medislam/iFogSimWithDataPlacement)
 - [Python] [Avasalcai, C., Tsigkanos, C., & Dustdar, S. (2021). **"Resource Management for Latency-Sensitive IoT Applications with Satisfiability"**. IEEE Transactions on Services Computing.](https://ieeexplore.ieee.org/iel7/4629386/4629387/09409738.pdf?casa_token=fLR0Nsk7WBIAAAAA:LnSHOOFe5dI1XMBXkkWh70tSNxcvxz3ERypN1R3ydPMpoPHIIDvO9HfBwLNBNiAZaQzBWc0G2_E) [[**Source Code**]](https://github.com/cavasalcai/Decentralized-Resource-Management)
 - [Java] [Abdullaha, M., Khana, S. A., Alenezib, M., Almustafab, K., & Iqbala, W. (2020). **"Application Centric Virtual Machine Placements to Minimize Bandwidth Utilization in Datacenters"**. Intell. Autom. Soft Comput., 26(1), 13-25.](https://www.researchgate.net/profile/Waheed-Iqbal/publication/326704195_Application_Centric_Virtual_Machine_Placements_to_Minimize_Bandwidth_Utilization_in_Datacenters/links/5baf662ca6fdccd3cb7c1230/Application-Centric-Virtual-Machine-Placements-to-Minimize-Bandwidth-Utilization-in-Datacenters.pdf) [[**Source code**]](https://github.com/abdullahsunny/VM-Placement-for-Application-centric-Data-centers-Simulation)
 - [Matlab] [Cong, R., Zhao, Z., Min, G., Feng, C., & Jiang, Y. (2021). **"EdgeGO: A Mobile Resource-sharing Framework for 6G Edge Computing in Massive IoT Systems"**. IEEE Internet of Things Journal.](https://ieeexplore.ieee.org/abstract/document/9375469/?casa_token=QG_yQjMPQC8AAAAA:EKfKzpEizqpgmmZiR58Zv6ObtT4Qjzbl_hT6m7dDMFsFR0WO5_gje0rLskk0ycgo0MKQwtYmPkc) [[**Source code**]](https://github.com/mobinets/6G-Edge-Computing-Simulation-Deployment)
 - [Matlab] [Shu, C., Zhao, Z., Han, Y., Min, G., & Duan, H. (2019). **"Multi-user offloading for edge computing networks: A dependency-aware and latency-optimal approach"**. IEEE Internet of Things Journal, 7(3), 1678-1689.](https://ieeexplore.ieee.org/abstract/document/8847369/?casa_token=F95Uk3so1CoAAAAA:v-0Jxzz1n4o3_s3Rxhzh8lnGc2Lt_alKYBCcMY4dbEYI37tP3wsD7xLnTzDJ1KWXaxef4p0hOwM) [[**Source code**]](https://github.com/mobinets/task-offloading-edge-computing)


### A.3. Computation offloading
>#### + Reinforcement Learning
 - [Python] [Wu, D., Ullah, R., Harvey, P., Kilpatrick, P., Spence, I., & Varghese, B. (2021). **"Fedadapt: Adaptive offloading for iot devices in federated learning"**. arXiv preprint arXiv:2107.04271.](https://arxiv.org/pdf/2107.04271)[[**Source code**]](https://github.com/qub-blesson/FedAdapt)

>#### + Deep Reinforcement Learning
  - [Python] [Huang, L., Bi, S., & Zhang, Y. J. A. (2019). **"Deep reinforcement learning for online computation offloading in wireless powered mobile-edge computing networks"**. IEEE Transactions on Mobile Computing, 19(11), 2581-2593.](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8771176&casa_token=ZhYRKqP1KfgAAAAA:wVHyWs1iRPHRZvM1Bmk6aqRdbJL51xefIdkBg6JyEUdsFtTFfbl_sOB2J5cMjQUMej5z4mh2qlQ&tag=1) [[**Source code**]](https://github.com/revenol/DROO)
  - [Python] [Wang, Yunpeng, et al. **"Computation offloading optimization for UAV-assisted mobile edge computing: a deep deterministic policy gradient approach."** Wireless Networks 27.4 (2021): 2991-3006.](https://link.springer.com/article/10.1007/s11276-021-02632-z) [[**Source code**]](https://github.com/fangvv/UAV-DDPG)
  - [Python] [Bi, Suzhi, et al. **"Lyapunov-guided deep reinforcement learning for stable online computation offloading in mobile-edge computing networks."** IEEE Transactions on Wireless Communications (2021).](https://arxiv.org/pdf/2010.01370) [[**Source code**]](https://github.com/revenol/LyDROO)
  - [Python] [Huang, L., Feng, X., Feng, A., Huang, Y., & Qian, L. P. (2018). **"Distributed deep learning-based offloading for mobile edge computing networks"**. Mobile networks and applications, 1-8.](https://www.researchgate.net/profile/Liang-Huang-33/publication/329279256_Distributed_Deep_Learning-based_Offloading_for_Mobile_Edge_Computing_Networks/links/5c076f3b458515ae5447b313/Distributed-Deep-Learning-based-Offloading-for-Mobile-Edge-Computing-Networks.pdf) [[**Source Code**]](https://github.com/revenol/DDLO)
  -  [Python] [Huang, L., Bi, S., & Zhang, Y. J. A. (2019). **"Deep reinforcement learning for online computation offloading in wireless powered mobile-edge computing networks"**. IEEE Transactions on Mobile Computing, 19(11), 2581-2593.](https://ieeexplore.ieee.org/iel7/7755/4358975/08771176.pdf?casa_token=pnru4Uqy0gUAAAAA:P8_EKTbPbrfdJ_RELgRV9Kjo_Qt9T9tz4Ppf_HIc_LaoT-Lu3mj5aC07y7IHy1XBgmbbMuV0Mto) [[**Source Code**]](https://github.com/jordan8409212/RL-for-binary-computation-offloading-in-wireless-powered-MEC-networks)

>#### + Fuzzy Logic
- [Java] [Basic, F., Aral, A., & Brandic, I. (2019, June). **"Fuzzy handoff control in edge offloading"**. In 2019 IEEE International Conference on Fog Computing (ICFC) (pp. 87-96). IEEE.](https://www.researchgate.net/profile/Atakan-Aral/publication/335580866_Fuzzy_Handoff_Control_in_Edge_Offloading/links/5fd6a10b92851c13fe84cb27/Fuzzy-Handoff-Control-in-Edge-Offloading.pdf) [[**Source Code**]](https://github.com/BasFa/FHC-simulator/)

 >#### + Heuristics
 - [Matlab] [Tran, T. X., & Pompili, D. (2018). **"Joint task offloading and resource allocation for multi-server mobile-edge computing networks"**. IEEE Transactions on Vehicular Technology, 68(1), 856-868.](https://ieeexplore.ieee.org/iel7/25/4356907/08533343.pdf?casa_token=GY5U7f-2vQMAAAAA:N6ApF1_q6JJH2PXSjGOdOAqdgGdVKBigc6bqQi5VE1L2jPCrs1r-lEYvKA0B1C1JpO_rEN0mVJk) [[**Source Code**]](https://github.com/Cyclotron2333/Task-Offloading-and-Resource-Allocation-for-Multi-Server-Mobile-Edge-Computing-Networks)
 - [Python] [Yan, Jia, Suzhi Bi, and Ying-Jun Angela Zhang (2018). **"Optimal offloading and resource allocation in mobile-edge computing with inter-user task dependency."** IEEE GLOBECOM.](https://arxiv.org/pdf/1810.11199.pdf) [[**Source Code**]](https://github.com/czgdp1807/MECOptimalOffloading)
- [Java] [De Maio, V., & Brandic, I. (2018, May). **"First hop mobile offloading of dag computations"**. In 2018 18th IEEE/ACM International Symposium on Cluster, Cloud and Grid Computing (CCGRID) (pp. 83-92). IEEE.](https://www.ec.tuwien.ac.at/~ivona/papers/CCGrid2018.pdf) [[**Source code 1**]](https://github.com/vindem/sleipnir) [[**Source code 2**]](https://bitbucket.org/vindem/fogtorchpi-extended)
 - [Python] [Mitsis, Giorgos, et al. **"Intelligent dynamic data offloading in a competitive mobile edge computing market."** Future Internet 11.5 (2019): 118.](https://www.mdpi.com/1999-5903/11/5/118/pdf) [[**Source Code**]](https://github.com/vinPopulaire/MEC_offloading)
- [Python] [Chen, Y. T., & Liao, W. (2019, May). **"Mobility-aware service function chaining in 5G wireless networks with mobile edge computing"**. In ICC. pp. 1-6.](https://ieeexplore.ieee.org/iel7/8753818/8761046/08761306.pdf?casa_token=d5ChthskjiMAAAAA:5TdoQ1KYRB-sY3Vn0wVq_wj647R6HXdRxHa8cyt5MzTLg85qRGrz2RGEZHuEySXP4m0186z1hW8) [[**Source code**]](https://github.com/yantingchn/MVNFP)


## B. Fog-Edge Computing simulators/frameworks
---
- `VirtFogSim`. [Matlab] [Scarpiniti, M., Baccarelli, E., & Momenzadeh, A. (2019). **"VirtFogSim: A parallel toolbox for dynamic energy-delay performance testing and optimization of 5G mobile-fog-cloud virtualized platforms"**. Applied Sciences, 9(6), 1160.](https://www.mdpi.com/2076-3417/9/6/1160/htm) [[**Source code**]](https://github.com/mscarpiniti/VirtFogSim)

- `FogNetSim++`. [C] [Qayyum, T., Malik, A. W., Khattak, M. A. K., Khalid, O., & Khan, S. U. (2018). **"FogNetSim++: A toolkit for modeling and simulation of distributed fog environment"**. IEEE Access, 6, 63570-63583.](https://ieeexplore.ieee.org/iel7/6287639/6514899/08502760.pdf) [[**Source code**]](https://github.com/rtqayyum/fognetsimpp)

- `iFogSim`.  [Java] [Gupta, H., Vahid Dastjerdi, A., Ghosh, S. K., & Buyya, R. (2017). **"iFogSim: A toolkit for modeling and simulation of resource management techniques in the Internet of Things, Edge and Fog computing environments"**. Software: Practice and Experience, 47(9), 1275-1296.](https://arxiv.org/pdf/1606.02007.pdf) [[**Source code**]](https://github.com/Cloudslab/iFogSim)

- `Dynamic ifogsim`. [Python] [Seo, D., Shahhosseini, S., Mehrabadi, M. A., Donyanavard, B., Lim, S. S., Rahmani, A. M., & Dutt, N. (2020). **"Dynamic ifogsim: A framework for full-stack simulation of dynamic resource management in iot systems"**. In COINS. pp. 1-6.](https://ieeexplore.ieee.org/iel7/9186550/9191368/09191663.pdf?casa_token=kGGnUJTfL-IAAAAA:TYHHk44nDFXk0E2NEOVbFWGR2SJHKgDB7jk8rrSyjl4F-miKMIR4JuETbWABIBOTh94YjwA06VQ) [[**Source Code**]](https://github.com/HealthSciTech/Dynamic_iFogSim)
   

- `Edgecloudsim`. [Java] [Sonmez, C., Ozgovde, A., & Ersoy, C. (2018). **"Edgecloudsim: An environment for performance evaluation of edge computing systems"**. Transactions on Emerging Telecommunications Technologies, 29(11), e3493.](https://scholar.archive.org/work/uiolxyzaarhbzni272nvnidwee/access/wayback/https://www.researchgate.net/profile/Atay_Ozgovde/publication/317067647_EdgeCloudSim_An_Environment_for_Performance_Evaluation_of_Edge_Computing_Systems/links/5925e39b458515e3d4537990/EdgeCloudSim-An-Environment-for-Performance-Evaluation-of-Edge-Computing-Systems.pdf) [[**Source code**]](https://github.com/CagataySonmez/EdgeCloudSim)

 - `YAFS`. [Python] [Lera, I., Guerrero, C., & Juiz, C. (2019). **"YAFS: A simulator for IoT scenarios in fog computing"**. IEEE Access, 7, 91745-91758.](https://ieeexplore.ieee.org/iel7/6287639/6514899/08758823.pdf) [[**Source code**]](https://github.com/acsicuib/YAFS/)

- `FogTorch`. [Java] [Brogi, A., & Forti, S. (2017). **"QoS-aware deployment of IoT applications through the fog"**. IEEE Internet of Things Journal, 4(5), 1185-1192.](https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/iel7/6488907/6702522/07919155.pdf%3Fcasa_token%3D9hJjBV8ha2cAAAAA:C_xpM2lIxcgpWRFMsxKu5rojcPPQYxlOBya6VISnEuPFoqS5y9K9H97L5pwWgkms3Y6sR9XIa-o&hl=fr&sa=T&oi=gsb-gga&ct=res&cd=0&d=10311237671799238044&ei=1V23Yb7DG8ySy9YP1Li_8Ak&scisig=AAGBfm3I9lWenfTCO-T5InIn7P_L7INRoA) [[**Source code**]](https://github.com/di-unipi-socc/FogTorch)

- `FogTorchPI`. [Java] [Brogi, A., Forti, S., & Ibrahim, A. (2019). **"Predictive analysis to support fog application deployment"**. Fog and edge computing: principles and paradigms, 191-222.](http://pages.di.unipi.it/forti/pdf/chapters/2018/C09_Predictive%20Analysis%20to%20Support%20Fog%20Application%20Deployment_PP.pdf) [[**Source code**]](https://github.com/di-unipi-socc/FogTorchPI)


- `MobFogSim`. [Java] [Puliafito, C., Gonçalves, D. M., Lopes, M. M., Martins, L. L., Madeira, E., Mingozzi, E., ... & Bittencourt, L. F. (2020). **"MobFogSim: Simulation of mobility and migration for fog computing"**. Simulation Modelling Practice and Theory, 101, 102062.](https://www.sciencedirect.com/science/article/pii/S1569190X19301935?casa_token=oz5u1dhMK_sAAAAA:-COv4G7LjuTN1gCdGTtayPgyGYm_l6lwG1ox_zx2L6IdcgC4iCiLjhdSC8heFbhubGt5LAj0JvE) [[**Source code**]](https://github.com/diogomg/MobFogSim)

- `Emufog`. [Kotlin] [Mayer, R., Graser, L., Gupta, H., Saurez, E., & Ramachandran, U. (2017, October). **"Emufog: Extensible and scalable emulation of large-scale fog computing infrastructures"**. In IEEE FWC. pp. 1-6.](https://ieeexplore.ieee.org/iel7/8364427/8368514/08368525.pdf?casa_token=ei8AH_Jl450AAAAA:LepNJSrHBz1WK_helYtKyZRMF2syZN6ojC9HrnUOEkZFzA9evHbxXSLNF8cj1HMGvJ6xCQ-kmY4) [[**Source code**]](https://github.com/emufog/emufog)

- `FogDirMime`. [Python] [Forti, S., Ibrahim, A., & Brogi, A. (2019). **"Mimicking FogDirector application management"**. SICS Software-Intensive Cyber-Physical Systems, 34(2), 151-161.](http://pages.di.unipi.it/forti/pdf/journals/2018/csrd18.pdf) [[**Source Code**]](https://github.com/di-unipi-socc/FogDirMime/)

- `FogDirSim`. [Python] [Forti, S., Pagiaro, A., & Brogi, A. (2020). Simulating fogdirector application management. Simulation Modelling Practice and Theory, 101, 102021.](https://www.sciencedirect.com/science/article/pii/S1569190X19301522?casa_token=F_mcBRxln1UAAAAA:nQ_lDOgB9k5cj9wd1V7jFn0nBdBbcgVL0hXJv5JwkLth4h6NEMA1Hvl-KUXPlUvktSceHE3-HLs) [[**Source code**]](https://github.com/di-unipi-socc/FogDirSim)

- `LocPrivFogSim`. [Java] [**LocPrivFogSim: A simulator to analyze threats of computation offloading strategies to location privacy in fog computing with real-world trajectory data.**](https://github.com/LocPrivFogSim/LocPrivFogSim)

- `FogAtlas`. [Go] [**FogAtlas – A platform for operating Fog Computing infrastructures.**](https://fogatlas.fbk.eu/)

- `KubeEdge`. [Go] [**Kubernetes Native Edge Computing Framework**.](https://kubeedge.io/en/)

- `Fogbed`. [Python] [**Fog emulation platform**.](https://github.com/fogbed/fogbed)

- `ENORM`. [Python] [Wang, N., Varghese, B., Matthaiou, M., & Nikolopoulos, D. S. (2017). **"ENORM: A framework for edge node resource management. IEEE transactions on services computing"**.](https://ieeexplore.ieee.org/iel7/4629386/4629387/08039523.pdf?casa_token=S7tAvKq0ZJoAAAAA:jf61gOckd4haKuYFDpOlW2JUgQUu3SNmgfg_5vjtVtz-6srgcRYZSoagUzUMqkC32TNObSlcnPg) [[**Source code**]](https://github.com/qub-blesson/ENORM)

- `FogFlow`. [Go] [FogFlow: an IoT Edge Computing framework.](https://github.com/smartfog/fogflow) 

<!-- 
### - Other interesting simulators
- `SniperSim`. [Python] [Multi-core simulator.](https://snipersim.org//w/The_Sniper_Multi-Core_Simulator) 
-->

## C. Data traces
---
 * [Microscopic vehicular mobility trace of Europarc roundabout, Creteil, France](http://vehicular-mobility-trace.github.io)
 * [mobility patterns of SUMO - Simulation of Uban MObility](https://www.eclipse.org/sumo/)
 * [Industrial Internet of Things Data](https://www.kaggle.com/pitasr/industrialiot)
 * [Mobile HEALTH datasets](https://archive.ics.uci.edu/ml/datasets/MHEALTH+Dataset)
 * [Machine Learning Repository](https://archive-beta.ics.uci.edu)
 * [Alibaba Cluster Trace Program](https://github.com/alibaba/clusterdata)
 * [Fog-Computing-Data-set](https://github.com/AdnanAkhunzada/Fog-Computing-Data-set)
 * [Iot-compute-dataset](https://github.com/saifulislamPhD/IoT-Compute-Dataset) 
 <!-- Refrenced in: [Paper_1](https://www.sciencedirect.com/science/article/abs/pii/S108480452030148X#bbib25)-->
 * [CRAWDAD: Community Resource for Archiving Wireless Data At Dartmouth](https://crawdad.org/index.html)
 * [Wide mawi working group traffic archive](http://mawi.wide.ad.jp)
 * [AutoML – training high-quality custom machine learning models with minimum effort and machine learning expertise.](https://cloud.google.com/automl/)

## D. Fog/Edge topologies
---
 * The [BRITE](https://www.nsnam.org/doxygen/group__brite.html) network generator. <!-- Refs: [Mayer et al.](https://ieeexplore.ieee.org/iel7/8364427/8368514/08368525.pdf?casa_token=ei8AH_Jl450AAAAA:LepNJSrHBz1WK_helYtKyZRMF2syZN6ojC9HrnUOEkZFzA9evHbxXSLNF8cj1HMGvJ6xCQ-kmY4)-->
 * Real world topologies from [Caida](https://www.caida.org/) <!-- Referenced in: [Mayer et al.](https://ieeexplore.ieee.org/iel7/8364427/8368514/08368525.pdf?casa_token=ei8AH_Jl450AAAAA:LepNJSrHBz1WK_helYtKyZRMF2syZN6ojC9HrnUOEkZFzA9evHbxXSLNF8cj1HMGvJ6xCQ-kmY4)-->
 * [The Internet Topology Zoo](http://www.topology-zoo.org)
  
## E. IoT applications
---
 * Refer to [this page](https://asfarah.github.io/IoT_Benchmark/) that reviews the main identified IoT applications in Fog-Edge Computing investigated in the literature.

## F. Fog Computing Projects
---
 - [Beyond the Clouds, The Discovery Initiative](https://beyondtheclouds.github.io/)
 - [projet FogGuru](http://www.fogguru.eu/)
 - [Fog Computing Project](https://nmsl.cs.nthu.edu.tw/fog-computing-project/)
 - [Internet of Things (IoT) and Fog computing](https://mc.cs.ut.ee/research/internet-of-things/)
