---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

## ZhiweiXu(许志伟)

I am currently a lecturer at the School of Computer Science and Technology, Wuhan University of Science and Technology, I am currently a lecturer at the School of Computer Science and Technology, Wuhan University of Science and Technology, China. I am a member of the **Institute of Electrical and Electronics Engineers (IEEE)**, **China Computer Federation (CCF)**, **Association for Computing Machinery (ACM)**, **Chinese Association for Artificial Intelligence (CAAI)**, **Chinese Association of Automation (CAA)**, **Chinese Institute of Electronics (CIE)**, **Technical Committee on Intelligent Simulation Optimization and Scheduling, Chinese Association for System Simulation**, **IEEE Systems, Man, and Cybernetics Society (IEEE-SMC)**, **IEEE Computational Intelligence Society (IEEE-CIS)**, and **ACM Special Interest Group on Genetic and Evolutionary Computation (ACM-SIGEVO)**. Recognized as a high-quality content creator and blogging expert in the field of artificial intelligence on CSDN, I have actively contributed to the academic community.

I was awarded the National Scholarship for Master's students in 2019 and the National Scholarship for Doctoral students in 2021 and 2022 by the Ministry of Education of China. Recently, I have achieved significant advancements and breakthroughs in multi-task multi-objective optimization, constrained multi-objective optimization, and high-dimensional multi-objective optimization.

I have participated in two projects funded by the National Natural Science Foundation of China and led a youth project funded by the Provincial Natural Science Foundation. I hold three granted patents. My research findings have been published in top-tier international journals such as **IEEE Transactions on Evolutionary Computation**, **IEEE Transactions on Cybernetics**, **Information Sciences**, **Science China: Information Sciences**, and **Applied Soft Computing**.

I was recognized as an Excellent Graduate Student at the Annual Meeting and Academic Seminar of the Wuhan Computer Software Engineering Society in both 2021 and 2022, and won the First Prize at the 2021 CCF Wuhan Excellent Doctoral Student Academic Showcase Forum.

I serve as a reviewer for leading international journals including **IEEE Transactions on Evolutionary Computation**, **IEEE Transactions on Systems, Man, and Cybernetics: Systems**, **Information Sciences**, **Applied Soft Computing**, **Robotics and Computer-Integrated Manufacturing**, **Neural Computing and Applications**, and **Journal of Membrane Computing**. Additionally, I am a reviewer for international conferences such as the **IEEE Congress on Evolutionary Computation (IEEE CEC)**, **IEEE Symposium Series on Computational Intelligence (SSCI)**, **IEEE Conference on Artificial Intelligence (IEEE CAI)** and the **International Conference on Bio-inspired Computing: Theories and Applications (BIC-TA)**.  Served as a Session Chair at the **19th International Conference on Bio-inspired Computing: Theories and Applications (BIC-TA 2024)**, Program Committee Member for the **2025 Asia Conference on Artificial Intelligence Technology (ACAIT2025)** and **The International Conference on Machine Intelligence and Nature-inspired Computing (MIND 2025)**.  <a href='https://scholar.google.com/citations?user=_Lkioz8AAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=引用"></a>

My research interests include:

- Evolutionary Computation
- Multi-objective Optimization (Many-objective, Constrained, Multi-task, Multimodal, etc.)
- DNA Computing, Encoding, and Self-Assembly
- RNA Structure Prediction
- Multi-objective Path Planning

<span class='anchor' id='-Hl'></span>

## Highlight

<span class='anchor' id='-lwzl'></span>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TITS 2025</div><img src='images/MMOEA-CDP.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Zhiwei Xu(许志伟)` \*, Kai Zhang, Javier Del Ser, Miqing Li, Xin Xu, Juanjuan He, Ni Wu.Multi-Objective Optimization for Multimodal Multi-Objective Multi-Point Shortest Path Problem Considering Unforeseeable Road Eventualities. *IEEE Transactions on Intelligent Transportation Systems* , pp. 1–19, 2025 (JCR: Q1; IF: 7.9)  
- In this paper, multi-objective multi-point shortest path planning problem is modeled as a multimodal multi-objective optimization problem with necessary points constrains. A multimodal multi-objective evolutionary algorithm using constraint dominance principle-based path comparison strategy and path similarity-based multimodal solutions selection strategy is proposed to address this problem.  
[[Link]](https://ieeexplore.ieee.org/document/10959009/) [[Download]](/PDF/MMOEA-CDP.pdf) [[Code]](https://github.com/JaywayXu/MMOEA-CDP)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCYB 2021</div><img src='images/MaOES.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Kai Zhang, `Zhiwei Xu(许志伟)`, Shengli Xie, and Gary G. Yen\*. Evolution Strategy-Based Many-Objective Evolutionary Algorithm Through Vector Equilibrium. *IEEE Transactions on Cybernetics* , vol. 51, no. 11, pp. 5455–5467, Nov. 2021. (JCR:Q1; IF:11.8)
- In this paper, we propose a novel evolution strategy for solving many-objective optimization problems, named MaOES.
- The proposed algorithm uses mutation and selection for individual self-adaptation. The Precision Controllable Mutation operator is designed for individuals to explore and exploit the decision space efficiently. The Maximum Extension Distance strategy is tailored to guide the individuals to keep uniform distance among particles in the population and to facilitate the extension to approximate the entire Pareto front automatically.  
[[Link]](https://ieeexplore.ieee.org/document/8955947/) [[Download]](/PDF/MaOES.pdf)[[Code]](https://github.com/MaOEA/MaOES)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TEVC 2024</div><img src='images/CMOES.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- Kai Zhang, `Zhiwei Xu(许志伟)`, Gary G. Yen\*, Ling Zhang. Two-Stage Multi-Objective Evolution Strategy for Constrained Multi-Objective Optimization. *IEEE Transactions on Evolutionary Computation* , vol. 28, no. 1, pp. 17–31, Feb. 2024 (JCR:Q1; IF:14.3)
- In this paper, a novel parameter-less constraint handling technique is proposed, which divides the whole population into three mutually exclusive subsets dynamically, including FNDS, the subset dominated by FNDS, and the subset not dominated by FNDS. According to the proposed division of labor, it is not necessary to balance the convergence and constrained satisfaction in each subset.
- Secondly, to avoid been trapped into local optima, the proposed algorithm adopts a two-stage strategy to solve CMOPs.
- In the first stage, the proposed algorithm focuses solely on converging toward the unconstrained PF without considering the constrained satisfaction.
- In the second stage, the FNDS constraint handling technique is adopted to guide the population converging towards PF effectively.  
[[Link]](https://ieeexplore.ieee.org/document/9869698) [[Download]](/PDF/CMOES.pdf)[[Code]](https://github.com/MaOEA/CMOES)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS 2022</div><img src='images/CT-EMT-MOES.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Zhiwei Xu (许志伟)`, Xiaoming Liu, Kai Zhang\*, and Juanjuan He. Cultural transmission based multi-objective evolution strategy for evolutionary multitasking. *Information Sciences* , vol. 582, pp. 215–242, Jan. 2022. (JCR:Q1; IF：8.1)

- In this paper, a novel multi-objective evolution strategy was proposed for solving multitask optimization problems. Inspired by modern cultural evolution theory, elite-guided variation strategy, and horizontal cultural transmission strategy, two evolutionary operators were proposed.
- To make full use of the two transfer strategies, an adaptive information transfer strategy is proposed to adjust the probability of the information transfer adaptively according to the dominant relationship between the offspring and its parent to reasonably allocate the evolutionary resources.  
[[Link]](https://www.sciencedirect.com/science/article/pii/S0020025521009282) [[Download]](/PDF/CT_EMT_MOES.pdf)[[Code]](https://github.com/Asurada2015/CT-EMT-MOES)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">INS 2022</div><img src='images/EMT-MOMIEA.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Zhiwei Xu (许志伟)`, Kai Zhang, Juanjuan He\*, and Xiaoming Liu. A novel membrane-inspired evolutionary framework for multi-objective multi-task optimization problems. *Information Sciences* , vol. 596, pp. 236–263, Jun. 2022. (JCR:Q1; IF：8.1)  

- In this paper, a multi-objective multi-task evolutionary framework based on membrane system (EMT-MOMIEA) is proposed to solve the multi-objective multi-task optimization (MOMTO) problems. 
- Inspired by the binding process of information molecules and receptors during information exchange between cells, the information molecule concentration vector (IMCV) concept is proposed. The IMCV can dynamically adjust the information transfer probability and reduce negative information transfer.  
[[Link]](https://www.sciencedirect.com/science/article/pii/S002002552200216X) [[Download]](/PDF/EMT-MOMIEA.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASOC 2021</div><img src='images/MOMFIA.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Zhiwei Xu (许志伟)` and Kai Zhang\*. Multiobjective multifactorial immune algorithm for multiobjective multitask optimization problems. *Applied Soft Computing* , vol. 107, p. 107399, Aug. 2021. (JCR:Q1; IF：8.7)

- In this paper, a novel multiobjective multifactorial immune algorithm (MOMFIA) is proposed to solve MOMTO and MOMaTO problems. The proposed MOMFIA applied a novel multipopulation framework and a novel information transfer method based on the dimensional information of solutions (DIS). The proposed multi-population framework can evenly distribute individuals to different subpopulations, each of which maintains an independent task module, can evolve independently, but is also equipped to transfer their knowledge when necessary.  
[[Link]](https://www.sciencedirect.com/science/article/pii/S1568494621003227) [[Download]](/PDF/MOMFIA.pdf)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ASOC 2024</div><img src='images/HMOMFMA.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

- `Zhiwei Xu (许志伟)`\*, Jia feng Xu, Kai Zhang, Xin Xu, Juanjuan He, Ni Wu, Decision Variable Classification based Multi-objective Multifactorial Memetic Algorithm for Multi-objective Multi-task Optimization Problem. *Applied Soft Computing* , vol. 152, p. 111232, Feb. 2024. (JCR:Q1; IF：8.7)

- In this paper, a novel hybrid multi-objective multifactorial memetic algorithm is proposed to solve MOMTO problems. The proposed variable classification method will classify decision variables into convergence-related and diversity-related decision variables. Only the same type of decision variables in the source and target tasks can transfer information to avoid negative transfer. 
- Different evolutionary operators are adopted according to the characteristics of decision variables during individual recombination. 
- In addition, the proposed algorithm hybridizes the immune algorithm as the global evolutionary operator and the evolutionary gradient search algorithm as the local search operator into the multifactorial framework to enhance the searching ability.  
[[Link]](https://www.sciencedirect.com/science/article/pii/S1568494624000061) [[Download]](/PDF/HMOMFMA.pdf)
</div>
</div>

## Publication

<span class='anchor' id='-Pub'></span>

---
- `Zhiwei Xu(许志伟)` \*, Kai Zhang, Javier Del Ser, Miqing Li, Xin Xu, Juanjuan He, Ni Wu.Multi-Objective Optimization for Multimodal Multi-Objective Multi-Point Shortest Path Problem Considering Unforeseeable Road Eventualities. *IEEE Transactions on Intelligent Transportation Systems* , pp. 1–19, 2025 (JCR: Q1; IF: 7.9)  
[[Link]](https://ieeexplore.ieee.org/document/10959009/) [[Download]](https://jaywayxu.github.io/PDF/MMOEA-CDP.pdf) [[Code]](https://github.com/JaywayXu/MMOEA-CDP)

- `Zhiwei Xu (许志伟)`, Xiaoming Liu, Kai Zhang\*, and Juanjuan He. Cultural transmission based multi-objective evolution strategy for evolutionary multitasking. *Information Sciences* , vol. 582, pp. 215–242, Jan. 2022. (JCR:Q1; IF：8.1)  
[[Link]](https://www.sciencedirect.com/science/article/pii/S0020025521009282) [[Download]](/PDF/CT_EMT_MOES.pdf)
- `Zhiwei Xu (许志伟)`, Kai Zhang, Juanjuan He\*, and Xiaoming Liu. A novel membrane-inspired evolutionary framework for multi-objective multi-task optimization problems. *Information Sciences* , vol. 596, pp. 236–263, Jun. 2022. (JCR:Q1; IF：8.1)  
[[Link]](https://www.sciencedirect.com/science/article/pii/S002002552200216X) [[Download]](/PDF/EMT-MOMIEA.pdf)
- `Zhiwei Xu (许志伟)`\*, Jia feng Xu, Kai Zhang, Xin Xu, Juanjuan He, Ni Wu, Decision Variable Classification based Multi-objective Multifactorial Memetic Algorithm for Multi-objective Multi-task Optimization Problem. *Applied Soft Computing* , vol. 152, p. 111232, Feb. 2024. (JCR:Q1; IF：8.7)  
[[Link]](https://www.sciencedirect.com/science/article/pii/S1568494624000061) [[Download]](/PDF/HMOMFMA.pdf)
- `Zhiwei Xu (许志伟)` and Kai Zhang\*. Multiobjective multifactorial immune algorithm for multiobjective multitask optimization problems. *Applied Soft Computing* , vol. 107, p. 107399, Aug. 2021. (JCR:Q1; IF：8.7)  
[[Link]](https://www.sciencedirect.com/science/article/pii/S1568494621003227) [[Download]](/PDF/MOMFIA.pdf)
- Kai Zhang, `Zhiwei Xu(许志伟)`, Shengli Xie, and Gary G. Yen\*. Evolution Strategy-Based Many-Objective Evolutionary Algorithm Through Vector Equilibrium. *IEEE Transactions on Cybernetics* , vol. 51, no. 11, pp. 5455–5467, Nov. 2021. (JCR:Q1; IF:11.8)  
[[Link]](https://ieeexplore.ieee.org/document/8955947/) [[Download]](/PDF/MaOES.pdf)[[Code]](https://github.com/MaOEA/MaOES)
- Kai Zhang, `Zhiwei Xu(许志伟)`, Gary G. Yen\*, Ling Zhang. Two-Stage Multi-Objective Evolution Strategy for Constrained Multi-Objective Optimization. *IEEE Transactions on Evolutionary Computation* , vol. 28, no. 1, pp. 17–31, Feb. 2024 (JCR:Q1; IF:14.3)  
[[Link]](https://ieeexplore.ieee.org/document/9869698) [[Download]](/PDF/CMOES.pdf)[[Code]](https://github.com/MaOEA/CMOES)
- JuanJuan He, Qian Yang, `Zhiwei Xu`, Kai Zhang, Xingyi Zhang, Mingfeng Ge\*. Two-stage multimodal multi-objective evolutionary algorithm based on global density updating strategy. *SCIENTIA SINICA Informationis* , 2024. (CCF-A)  
[[Link]](https://www.sciengine.com/SSI/doi/10.1360/SSI-2022-0294) [[Download]](/PDF/SSI2024.pdf)
- Kai Zhang, Chaonan Shen, Gary G. Yen\*, `Zhiwei Xu(许志伟)` , and Juanjuan He. Two-Stage Double Niched Evolution Strategy for Multimodal Multiobjective Optimization. *IEEE Transactions on Evolutionary Computation* , vol. 25, no. 4, pp. 754–768, Aug. 2021. (JCR:Q1; IF:14.3)  
[[Link]](https://ieeexplore.ieee.org/document/9372341) [[Download]](/PDF/DN-MMOES.pdf)[[Code]](https://github.com/MaOEA/DN-MMOES)
- Kai Zhang, Bin Chen, `Zhiwei Xu(许志伟)`\*. A Multiobjective Evolution Strategy Algorithm for DNA Sequence Design. *Journal of Electronics & Information Technology* , 2020, 42(6): 1365-1373.  
[[Link]](https://jeit.ac.cn/cn/article/doi/10.11999/JEIT190869) [[Download]](/PDF/MOES_DNA.pdf)
- `Zhiwei Xu(许志伟)`, Kai Zhang\*, Xin Xu, and Juanjuan He. A Fireworks Algorithm Based on Transfer Spark for Evolutionary Multitasking. *Frontiers in Neurorobotics* , vol. 13, p. 109, Jan. 2020.  
[[Link]](https://www.frontiersin.org/articles/10.3389/fnbot.2019.00109) [[Download]](/PDF/MTO-FWA.pdf)
- `Zhiwei Xu(许志伟)`, Xiaoming Liu, and Kai Zhang\*. Mechanical Properties Prediction for Hot Rolled Alloy Steel Using Convolutional Neural Network. *IEEE Access* , vol. 7, pp. 47068–47078, 2019.  
[[Link]](https://ieeexplore.ieee.org/document/8682144) [[Download]](/PDF/ACCESS.pdf)
- Haozhi Zhao, `Zhiwei Xu(许志伟)`\*, and K Zhang\*. Reference Point Based Multi-objective Evolutionary Algorithm for DNA Sequence Design. *International Conference on Bio-Inspired Computing: Theories and Applications*, 2019, pp. 178–188.  
[[Link]](http://link.springer.com/10.1007/978-981-15-3415-7_14) [[Download]](/PDF/BICTA_DNA.pdf)
- Hao Xu, `Zhiwei Xu(许志伟)`\*, and Kai Zhang\*. Mechanical Properties Prediction for Hot Roll Steel Using Convolutional Neural Network. *International Conference on Bio-Inspired Computing: Theories and Applications*, 2019, pp. 565–575.  
[[Link]](http://link.springer.com/10.1007/978-981-15-3415-7_47) [[Download]](/PDF/BICTA_CNN.pdf)
- Kai Zhang\*, Fang Liu, Chaonan Shen, and `Zhiwei Xu(许志伟)`. Multi-population Evolutionary Algorithm for Multimodal Multobjective Optimization. *International Conference on Intelligent Autonomous Systems*, 2021, pp. 199–204.  
[[Link]](https://ieeexplore.ieee.org/document/9527712) [[Download]](/PDF/ICoIAS.pdf)
- Fan Li, Kai Zhang\*, Chaonan Shen, `Zhiwei Xu(许志伟)`. Solving Multimodal Multi-Objective Problems with Local Pareto Front using a Population Clustering Mechanism. *International Conference on Machine Learning and Soft Computing*, 2023, pp. 34-39.  
[[Link]](https://dl.acm.org/doi/10.1145/3583788.3583793) [[Download]](/PDF/ICMLSC.pdf)

## Cooperation specialist

<span class='anchor' id='-Co'></span>

- [Gary G. Yen](https://scholar.google.com/citations?user=6LR55aMAAAAJ), *IET Fellow*, *IEEE Fellow*, Regents Professor in the School of Electrical and Computer Engineering at Oklahoma State University (OSU).
- [Linqiang Pan](https://scholar.google.com/citations?user=jZRwWG8AAAAJ), Professor with School of Artificial Intelligence and Automation, Huazhong University of Science and Technology, Wuhan, China.
- [Xingyi Zhang](https://scholar.google.com/citations?user=7lmPe2kAAAAJ), *IEEE Fellow*, Professor with the School of Computer Science and Technology, Anhui University, Hefei, China.
- [Javier Del Ser](https://scholar.google.com/citations?user=p_wY0zUAAAAJ), *IEEE Senior Member*, Research Professor in data analytics and optimization with TECNALIA, Spain, and an Adjunct Professor at the University of the Basque Country (UPV/EHU). 
- [Miqing Li](https://sites.google.com/view/miqing-li), *IEEE Senior Member*, Assistant Professor with the University of Birmingham, Birmingham, U.K. 
- [Xin Xu](https://scholar.google.com/citations?hl=en&user=DtuoAWIAAAAJ), *IEEE Senior Member*, Full Professor with the School of Computer Science and Technology, Wuhan University of Science and Technology, China.

<span class='anchor' id='-team'></span>

## Team specialist

<span class='anchor' id='-Prof'></span>
<style>
.prof-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.prof {
  display: flex;
  align-items: flex-start;
  margin: 20px 0;
  text-align: left;
}
.prof img {
  width: 150px;
  height: auto;
  border-radius: 50%;
  margin-right: 20px;
}
.prof .name {
  text-align: center; /* 名字居中显示 */
  width: 150px; /* 与图片宽度一致 */
  margin-top: 10px; /* 图片和名字之间的间距 */
}
.prof .description-container {
  display: flex;
  flex-direction: column;
}
.prof .description {
  font-size: 14px;
  margin-top: 0;
  max-width: 800px; /* 限制描述文字的最大宽度 */
}
</style>

<div class="prof-gallery">
  <div class="prof">
    <div>
      <img src="images/ZK.jpg" alt="Kai Zhang">
      <p class="name"><a href="https://www.researchgate.net/profile/Kai-Zhang-185" target="_blank">Kai Zhang</a></p>
    </div>
    <div class="description-container">
      <p class="description">Professor Kai Zhang is the Dean of the School of Computer Science and Technology at Wuhan University of Science and Technology and the leader of his research team. He studied under Professor Jin Xu at Peking University. As a doctoral supervisor and professor, he has been recognized as an Excellent Postdoctoral Fellow in Hubei Province and an Outstanding Young Scientific and Technological Worker in Wuhan City. He is an Outstanding Reviewer for IEEE Transactions on Cybernetics (IEEE TCYB) and a member of CCF, CAAI, IEEE, and ACM. He serves on the technical committee of IEEE SMC and is an executive director of the Biological Computing and Bioinformatics Processing Professional Committee of the Chinese Institute of Electronics.Professor Zhang has long been engaged in research in evolutionary computation and multi-objective optimization. He has published over 30 papers in influential academic journals such as IEEE Transactions on Evolutionary Computation (IEEE TEVC), IEEE Transactions on Cybernetics (IEEE TCYB), ACM Transactions on Intelligent Systems and Technology (ACM TIST), Information Sciences, and the Chinese Journal of Computers. He holds six authorized national invention patents.He has led three projects funded by the National Natural Science Foundation of China and one project funded by the Hubei Provincial Natural Science Foundation. He has received two Third Prizes of the Hubei Provincial Scientific and Technological Progress Award and two Second Prizes of the Hubei Provincial Teaching Achievement Award. Additionally, he has published two academic monographs. Professor Zhang teaches undergraduate and graduate courses such as "Data Structures," "Software Design Patterns," "Information Content Security," and "Evolutionary Computation and Multi-objective Optimization." He has supervised nine cohorts of master's students and one cohort of doctoral students.</p>
    </div>
  </div>

  <div class="prof">
    <div>
      <img src="images/HJJ.jpg" alt="Juanjuan He">
      <p class="name"><a href="https://www.researchgate.net/profile/Juanjuan-He" target="_blank">Juanjuan He</a></p>
    </div>
    <div class="description-container">
      <p class="description">Professor Juanjuan He studied under Professor Linqiang Pan at Huazhong University of Science and Technology. She has led one General Project and one Youth Project funded by the National Natural Science Foundation of China, one project funded by the Natural Science Foundation of Hubei Province, and one project under the Scientific Research Plan of the Hubei Provincial Department of Education. She has participated in four projects funded by the National Natural Science Foundation of China and has led or participated in multiple industry collaboration projects. She was awarded the Youth Morning Light Plan by the Hubei Provincial Association for Science and Technology and was recognized as a "Chutian Scholar" in Hubei Province. She was approved for a postdoctoral program funded by the China Scholarship Council to conduct a two-year visiting study at the University of Western Ontario in Canada. Professor He has published over 40 academic papers in important domestic and international journals and conferences such as IEEE Transactions on Evolutionary Computation, IEEE Transactions on Cybernetics, Information Sciences, Applied Soft Computing, and the Journal of Electronics & Information Technology. She holds 2 authorized patents.</p>
    </div>
  </div>

  <div class="prof">
    <div>
      <img src="images/QQD.jpg" alt="QiQi Duan">
      <p class="name"><a href="https://evolutionary-intelligence.github.io/About/" target="_blank">Qiqi Duan</a></p>
    </div>
    <div class="description-container">
      <p class="description">Qiqi Duan is now studying Swarm Intelligence (particularly Swarming of Foundation Models) and Distributed Evolutionary Computation (especially Meta-Evolution) for scalable optimization of Complex Systems at SUSTech, Shenzhen, China. He is one of core developers of the Open-Source software PyPop7 for population-based black-box optimization, published in one top-tier Machine Learning journal JMLR (CCF-A) and also published distributed meta-evolution strategies on one top-tier distributed system journal TPDS (CCF-A), extending his PPSN (CCF-B) conference paper which obtained the Best Paper nomination. Till now, his open-source pure-Python library PyPop7 has been used and cited by one Nature paper and others.</p>
    </div>
  </div>
</div>

## Master's degree student

### 2024

<style>
.student-gallery {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}
.student {
  margin: 10px;
  text-align: center;
}
.student img {
  width: 150px;
  height: auto;
  border-radius: 50%;
}
</style>

<div class="student-gallery">
  <div class="student">
    <img src="images/WPS.jpg" alt="Student 1">
    <p><a href="https://github.com/JaywayXu/PingShanWu" target="_blank">Pingshan Wu</a></p>
  </div>
  <div class="student">
    <img src="images/HNP.jpg" alt="Student 2">
    <p><a href="https://github.com/JaywayXu/NuopiaoHe" target="_blank">Nuopiao He</a></p>
  </div>
  <!-- 根据需要添加更多学生 -->
</div>
