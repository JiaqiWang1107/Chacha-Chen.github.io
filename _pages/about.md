---
permalink: /
excerpt: "About me"
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

About me
======



Hi, it's Chacha. I am a first year PhD student in IST at Penn State University. I am fortunate to be advised by  [Prof. **Kenneth Ting-hao Huang**](https://crowd.ist.psu.edu/index.html).  Before joining Penn State, I received my bachelor's degree from Shanghai Jiao Tong University. I spent a wonderful year working with [Prof. **Zhenhui Jessie Li**](https://faculty.ist.psu.edu/jessieli) in Hangzhou CityBrain Lab.


<!--Computer Science, **Shanghai Jiao Tong University**. 
-->
I'm interested in the general field of **Data Mining** and **Machine Learning**. Particularly, I aspire to solve real-world problems using Machine Learning techniques. Big Data itself cannot be utilized and well-understood. I want to be a data scientist who is able to turn data into knowledge which, in the long run, make impacts and improve the living standard of human society.

<!--Currently, I am working as a research intern of the City Brain project on **intelligent traffic signal control**, advised by [Prof. **Zhenhui Jessie Li**](https://faculty.ist.psu.edu/jessieli).-->

- My [<span style="color:orange">**Curriculum Vitae** </span>](/files/Chacha_CV.pdf).



<!--We are doing very exciting and impactful things in Hangzhou. Here is some news about us!-->

<!--[<span style="color:purple">**@XINHUANET新华网** </span>AI-driven technology reshaping city traffic in China](http://www.xinhuanet.com/english/2018-03/10/c_137029827.htm)

[<span style="color:purple">**@WIRED** </span>  In China, Alibaba’s data-hungry AI is controlling (and watching) cities](https://www.wired.co.uk/article/alibaba-city-brain-artificial-intelligence-china-kuala-lumpur)-->

<!--[<span style="color:purple">**@Technode** </span> Hangzhou is becoming a pioneer in urban digitization](https://technode.com/2018/09/19/hangzhou-digitization-pioneer/)

[<span style="color:purple">**@Alwihda Info** </span>Hangzhou growing ‘smarter’ thanks to AI technology](https://www.alwihdainfo.com/Hangzhou-growing-smarter-thanks-to-AI-technology_a58657.html)-->


## Education
- Shanghai Jiao Tong University Shanghai **(SJTU)**, China
	- B.E. in Computer Science, Sep.2015 -- Jun.2019 (Expected)
	<!--- GPA: 3.68/4.0 (87.1/100) -->
	- Advisor:  Prof. [**Weinan Zhang**](http://wnzhang.net/) and Prof. [**Zhenhui (Jessie) Li**](https://faculty.ist.psu.edu/jessieli/Site/index.html)

## Publication
- Hua Wei, **Chacha Chen**, Chang Liu, Guanjie Zheng, Zhenhui Li. Learning to Simulate on Sparse Data. In Proceedings of European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (**ECML-PKDD 2020**), Ghent, Belgium, Sep 2020. (To appear)
- **Chacha Chen**, Hua Wei, Nan Xu, Guanjie Zheng, Ming Yang, Yuanhao Xiong, Kai Xu and Zhenhui Li. Toward A Thousand Lights: Decentralized Deep Reinforcement Learning for Large-Scale Traffic Signal Control. In Proceedings of the Thirty-Fourth AAAI Conference on Artificial Intelligence (**AAAI'20**). (Acceptance rate: ~20.6\%) [[**Paper**](/files/chacha-AAAI2020.pdf)]
- Hua Wei*, Nan Xu*, Huichu Zhang, Guanjie Zheng, Xinshi Zang, **Chacha Chen**, Weinan Zhang, Yanmin Zhu, Kai Xu, and Zhenhui Li, [CoLight: Learning Network-level Cooperation for Traffic Signal Control](https://arxiv.org/pdf/1905.05717.pdf). In Proceedings of the 28th ACM International Conference on Information and Knowledge Management (**CIKM 2019**), Beijing, China, Nov 2019. (Acceptance rate: ~200/1030=19.4%)[[**Paper**](http://personal.psu.edu/hzw77/publications/colight-cikm19.pdf)]
- Hua Wei, **Chacha Chen**, Guanjie Zheng, Kan Wu, Vikash V. Gayah, Kai Xu and Zhenhui Li, [PressLight: Learning Max Pressure Control to Coordinate Traffic Signals in Arterial Network](https://dl.acm.org/citation.cfm?id=3330949). In Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (**KDD 2019**), Anchorage, AK, USA, Aug 2019. (Acceptance rate: ~170/1200=14.2%)[[**Paper**](http://personal.psu.edu/hzw77/publications/presslight-kdd19.pdf)]





## Research Experience

### Deep Reinforcement Learning for Traffic Signal Control 
_Research Intern, Advisor: Prof. Zhenhui (Jessie) Li Jul.2018 - Present_  

- Designed and implemented a reinforcement learning (RL) approach with justification on state and reward design for multi-intersection traffic signal control along arterials
- Draw a connection between RL method and classical transportation theory for the first time
- Justified our RL model in comparison to the closed form solution under the same simplified experiment settings
- Achieved state-of-the-art performance in simulation on both synthetic and real-world traffic data
- Started conducting field experiments in Hangzhou China

<span style="color:purple">**Here's a demo video showing how our intelligent traffic light learn the greenwave!** </span> 
<iframe width="560" height="315" src="https://www.youtube.com/embed/0zeHDpv361Q" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!--<span style="color:purple">**Hangzhou Intelligent Signal Control System Demo** </span> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Oj2rRASpPGQ" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>-->

<span style="color:purple">**Toward a Thousand Lights--Manhattan Experiment Demo** </span> 

<iframe width="560" height="315" src="https://www.youtube.com/embed/-UulnApXbjM" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

### Mining Homeownership Patterns 
_Research Assistant, Advisor: Prof. Tingting Lu (Social Science) and Prof. Weinan Zhang Mar.2018 - Present_

- Formulated the task into a multi-class classification problem in machine learning based on the data collected from a national scale survey
- Implemented logistic regression and tree model to predict the homeownership
- Interpreted the machine learning models with feature ranking and visualization which further reveals the
mechanism and pattern of homeownership

### SVM Toolbox for Both Indefinite and Semi-definite Kernel Learning 
_Research Assistant, Advisor: Prof. Xiaolin Huang Sep.2017 - Mar.2018_

- Coauthored a software package which accommodates Support Vector Machine (SVM) classification algorithms with indefinite kernels and semi-definite kernels
- Incorporated Sequential Minimal Optimization (SMO) in the traditional SVM algorithm
- Provided various kernel functions, including TAHN, TL1, Gaussian, polynomial and linear kernels
- Implemented various vector machine algorithms, including KVM, LSSVM, kPCA

## Contact
- Email: cjc6647@psu.edu
<!--- Tel: (+1)8146992243-->
<!--- Skype: chachachen1997-->
<!--- Address: 800 Dongchuan Rd, Minhang Campus, Shanghai Jiaotong University, Shanghai-->


<!--## Miscellaneous
- Volunteer: Organized a bazaar selling study notes to help people with kidney disease
- Programming: C/C++, Python, C#, Java, JavaScript, SQL
- Interests: badminton, swimming, photography-->

<!--Other places to find me: facebook, weibo (in Chinese)-->
