---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<style>
  .pub_button button {
    /* margin: calc(20vw / 100); */
    margin: 0.5em;
    padding-left:  calc(40vw / 100);
    padding-right:  calc(40vw / 100);
    padding-bottom: calc(0vw / 100);
    text-align: center;
    font-size: 12px;
    height: 25px;
    /* padding-left:  calc(40vw / 100);
    padding-right:  calc(40vw / 100);
    padding-bottom: calc(0vw / 100);
    text-align: center;
    font-size: calc(60vw / 100);
    height: calc(120vw / 100); */
    transition: 0.5s;
    background-size: 200% auto;
    color: white;
    border-radius: calc(60vw / 100);
    display: inline;
    /* border: 2px solid black; */
    font-weight: 500;
    box-shadow: 0px 0px 14px -7px #f09819;
    background-image: linear-gradient(45deg, #FF512F 0%, #F09819 51%, #FF512F 100%);
    cursor: pointer;
    user-select: none;
    -webkit-user-select: none;
    touch-action: manipulation;
  }

  .pub_button button:hover {
    background-position: right center;
    /* change the direction of the change here */
    color: #fff;
    text-decoration: none;
  }

  .pub_button button:active {
    transform: scale(0.95);
  }
</style>

![visitors](https://visitor-badge.laobi.icu/badge?page_id=vtu.life)

Hello, I am **Tinghao Xie 谢廷浩**, a second year ECE PhD candidate at [Princeton](https://www.princeton.edu/), advised by Prof. [Prateek Mittal](https://www.princeton.edu/~pmittal/index.html). Previously, I received my Bachelor degree from [Computer Science and Technology](http://www.en.cs.zju.edu.cn) at [Zhejiang University](http://www.zju.edu.cn/english/).

<!-- Earlier, I just finished my one-term visit at the [University of Oxford](https://www.ox.ac.uk/). -->
<!-- * 📋 My **[[CV/resume]](/files/CV_TinghaoXie.pdf) [[Research Summary Slides]](/files/research_summary_full.pdf)** -->

<!-- My current research interest lies around secure, robust and reliable AI. The projects I am now working on and have finished involve neural network verification, certified and adversarial robustness, backdoor attacks and defenses. Building AI that makes human-like decisions attracts me, where robustness and security may be good perspectives to dive in. I have enthusiasm in explainable AI, out-of-distribution generalization, and potential ways to improve current models fundamentally. Yet, I'm always on my way looking for things that intrigue me, and tend to hold an open mind for whatever is coming. I (wish to) have fun doing research. -->

<!-- I found the **robustness of machine learning** being both a “dark cloud” and an attractive perspective to work on. Specifically, my research interest could be described in two aspects: First, I intend to study and solve security concerns involving current non-robust deep learning models; Second, I would like to better understand AI’s behaviors and make their predictions more human-like through explainable and causal methods. In summary, I hope to fully explore the breadth and depth of **secure, robust, and reliable AI**. Yet, I'm always on my way looking for things that intrigue me, and tend to hold an open mind for whatever is coming. I (wish to) have fun doing research. -->

### My Research

I hope to fully explore the breadth and depth of **safe, secure, robust, and reliable AI systems**. Specifically:

- I am currently working around large (language / vision) model safety and security.
  - ✨ Check out our new **LLM safety benchmark**, 🥺[**SORRY-Bench**](https://sorry-bench.github.io/) -- evaluate LLM safety refusal systematically!
  - How easy can current text-to-image systems generate **copyrighted** content (and how to prevent them from such generations)? Check our 🐱[**CopyCat**](https://copycat-eval.github.io/) project.
  - "AI safety" and "AI security" are different! See our position paper 📖 [AI Risk Management Should Incorporate Both Safety and Security](https://arxiv.org/abs/2405.19524).
  - [LLM safety is brittle🫙](https://boyiwei.com/alignment-attribution/) -- removing barely 3% parameter / 2.5% rank will compromise model safety.
  - Do you know 🚨*fine-tuning aligned LLM can compromise safety, even when users do not intend to?* Checkout our work on 🚨**LLM Fine-tuning Risks** [[website]](https://llm-tuning-safety.github.io/) [[paper]](https://arxiv.org/abs/2310.03693) [[code]](https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety), which was exclusively reported on [**📰New York Times**](https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html)!
- I also have extensive research experience on DNN backdoor attacks and defenses for CV models:
  - Check my [**📦backdoor-toolbox**](https://github.com/vtu81/backdoor-toolbox) @ Github, which has helped many backdoor researchers!
<!-- To defense against backdoor attack at inference-time, we introduce a novel backdoor input detection method, by directly extracting the backdoor functionality to a backdoor expert model. Check our work **🛡️BaDExpert: Extracting Backdoor Functionality for Accurate Backdoor Input Detection** [[paper]](https://arxiv.org/abs/2308.12439) (preprint) for details! -->
<!-- We proposes a proactive solution to identify backdoor poison samples in a poisoned training set in our work **🛡️Towards A Proactive ML Approach for Detecting Backdoor Poison Samples** [[paper]](https://www.usenix.org/conference/usenixsecurity23/presentation/qi) [[code]](https://github.com/Unispac/Fight-Poison-With-Poison/tree/master) (USENIX Security'23) . This is realized via a super intersting method named "Confusion Training" where we prevent an ML model from fitting the normal clean samples by deliberate mislabeling -- the resulting model can only fit the backdoor poison samples. -->
<!-- Before that, our another work **🤔Revisiting the Assumption of Latent Separability for Backdoor Defenses** [[paper]](https://openreview.net/forum?id=_wSHsgrVali)[[code]](https://github.com/Unispac/Circumventing-Backdoor-Defenses) (ICLR'23) studies the latent separation assumption made by state-of-the-art backdoor defenses, and designs adaptive attacks against such backdoor defenses. -->
<!-- **😈Subnet Replacement Attack (SRA)**[[paper]](https://arxiv.org/abs/2111.12965)[[code]](https://github.com/Unispac/Subnet-Replacement-Attack) (CVPR'22 Oral) is my earlier work, proposing the first gray-box and physically realizable backdoor weight attack, collaborating with [Xiangyu Qi](https://unispac.github.io) @ Princeton University, advised by Principal Researcher Jifeng Zhu @ Tencent Zhuque Lab and [Prof. Kai Bu](https://list.zju.edu.cn/kaibu/) @ ZJU. -->
<!-- When I was an undergraduate, I was fortunate to work with [Prof. Ting Wang](https://alps-lab.github.io/) on **backdoor certification**[[blog]](/posts/2021/12/Backdoor-Certification/) and **backdoor restoration**[[blog]](/posts/2021/12/Backdoor-Trigger-Restoration/) @ Pennsylvania State University (currently Associate Professor @ Stony Brook University) as an intern, meanwhile co-advised by [Prof. Shouling Ji](https://nesa.zju.edu.cn/webpage/crew/jsl.html) @ ZJU [NESA Lab](https://nesa.zju.edu.cn/index.html). -->
<!-- Even earlier during my undergrad years (my first research experience actually lol), I worked with [Prof. Jianhai Chen](https://person.zju.edu.cn/en/cjhe), designed and implemented **Enchecap**[[code]](https://github.com/vtu81/Enchecap) -- an encrypted (enclave-based) heterogeneous calculation protocol. -->


### News & Facts

* [2024/05] I'm interning at Meta GenAI (Menlo Park, CA) this summer 🏖️. Feel free to reach out if you are nearby!
* [2024/05] Officially a PhD **candidate** now!
* [2023/10] Two papers accepted by ICLR 2024:
  * 📖 **Oral (Top 1.2%)** [Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://openreview.net/forum?id=hTEGyKf0dZ)
  * 📖 [BaDExpert: Extracting Backdoor Functionality for Accurate Backdoor Input Detection](https://openreview.net/forum?id=s56xikpD92)
* [2023/10] Our preprint 🚨[Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://llm-tuning-safety.github.io/) is available. It is exclusively reported by [📰New York Times](https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html) and covered by many other social medias!
* I enjoy: 🧗 Rock Climbing, Skiing, Open Water Diving, Basketball, Swimming, Billiards, Bowling...
<!-- * [2023/06] Our paper 📖 [Towards A Proactive ML Approach for Detecting Backdoor Poison Samples](https://www.usenix.org/conference/usenixsecurity23/presentation/qi) is accepted by USENIX Security 2023! -->
<!-- * [2023/01] Our paper 📖 [Revisiting the Assumption of Latent Separability for Backdoor Defenses](https://openreview.net/forum?id=_wSHsgrVali) is accepted by ICLR 2023! -->
<!-- * [2022/08] 🐯 Now officially a Ph.D. student in Princeton. -->
<!-- * [2022/07] 🎓 Graduated and received B.E. degree from ZJU! -->
<!-- * [2022/06] 🛡️ Successfully defended my undergraduate thesis, ready for graduation~ -->
<!-- * [2022/05] 🏆 Won the championship in Zhejiang University Body Building Competition (70kg level)! -->
<!-- * [2022/03] <s>My 🍫-abs (6 packs) are visible!!! To lose fat, healthy diets are just important as appropriate exercise plans.</s> (Update in 2023: Losing it due to heavy workload, wonderful food in Princeton student dinning halls, and lack of exercise😫) -->
<!-- * [2022/03] Our paper 📖 [Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks](https://arxiv.org/abs/2111.12965) is accepted by CVPR 2022 (oral)! -->
<!-- * Three papers of backdoor attacks and defenses: -->
  <!-- * 📖 [BaDExpert: Extracting Backdoor Functionality for Accurate Backdoor Input Detection](https://arxiv.org/abs/2308.12439) -->
  <!-- * 📖 [Circumventing Backdoor Defenses That Are Based on Latent Separability](https://arxiv.org/abs/2205.13613) -->
  <!-- * 📖 [Fight Poison with Poison: Detecting Backdoor Poison Samples via Decoupling Benign Correlations](https://arxiv.org/abs/2205.13616) -->
<!-- * 💃 Interested in choreography and street dance. I especially enjoy *House* recently. Besides that, I do *Hiphop* a lot, and some *Breaking* too. BTW, I like *Locking* and *Popping* but not so good at them :) -->
<!-- * 🏋 Go gymming regularly. -->
<!-- * 🔬 Currently working as a remote research intern @ [ALPS lab](https://alps-lab.github.io/alps/) (**A**lgorithmic Research on **L**earning, **P**rivacy and **S**ecurity), advised by Professor [Ting Wang](https://alps-lab.github.io/about/) at Penn State University. -->
<!-- * Received 22 Fall offers: ECE Ph.D.@Princeton, CS Ph.D.@GeorgiaTech, CS Ph.D.@NUS, MSML@CMU, MSCS@UCLA, MSCS@UCSD, MSCS@ETHz, MSCS@EPFL (updating). -->
<!-- * 🎓 **Seeking opportunities for a Ph.D. study** -->
<!-- * Our new paper [Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks](https://arxiv.org/abs/2111.12965) (pre-print & under review) now available! -->


### Publications/Manuscripts

<!-- > Click [here](publications) (or the "[Publications/Manuscripts](publications)" button in the nav bar) for more details! -->


📖 [SORRY-Bench: Systematically Evaluating Large Language Model Safety Refusal Behaviors](https://sorry-bench.github.io/)
<br/>
**Tinghao Xie\***, Xiangyu Qi\*, Yi Zeng\*, Yangsibo Huang\*, Udari Madhushani Sehwag, Kaixuan Huang, Luxi He, Boyi Wei, Dacheng Li, Ying Sheng, Ruoxi Jia, Bo Li, Kai Li, Danqi Chen, Peter Henderson, Prateek Mittal
<br/>
*Preprint (Under Review)*
<br/>
<a href="https://sorry-bench.github.io" style="text-decoration:none">
  <button class="pub_button">🏠Website </button>
</a>
<a href="http://arxiv.org/abs/2406.14598" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://huggingface.co/datasets/sorry-bench/sorry-bench-202406" style="text-decoration:none">
  <button class="pub_button">📚Dataset </button>
</a>
<a href="https://github.com/SORRY-Bench/SORRY-Bench" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>
<a href="https://huggingface.co/datasets/sorry-bench/sorry-bench-human-judgment-202406" style="text-decoration:none">
  <button class="pub_button">🧑‍⚖️Human Judgment Dataset </button>
</a>
<a href="https://huggingface.co/sorry-bench/ft-mistral-7b-instruct-v0.2-sorry-bench-202406" style="text-decoration:none">
  <button class="pub_button">🤖Judge LLM </button>
</a>



📖 [Fantastic Copyrighted Beasts and How (Not) to Generate Them](https://copycat-eval.github.io/)
<br/>
Luxi He\*, Yangsibo Huang\*, Weijia Shi\*, **Tinghao Xie**, Haotian Liu, Yue Wang, Luke Zettlemoyer, Chiyuan Zhang, Danqi Chen, Peter Henderson
<br/>
*Preprint (Under Review)*
<br/>
<a href="https://copycat-eval.github.io/" style="text-decoration:none">
  <button class="pub_button">🏠Website </button>
</a>
<a href="https://arxiv.org/pdf/2406.14526" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/princeton-nlp/CopyCat" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>



📖 [AI Risk Management Should Incorporate Both Safety and Security](https://arxiv.org/abs/2405.19524)
<br/>
Xiangyu Qi, Yangsibo Huang, Yi Zeng, Edoardo Debenedetti, Jonas Geiping, Luxi He, Kaixuan Huang, Udari Madhushani, Vikash Sehwag, Weijia Shi, Boyi Wei, **Tinghao Xie**, Danqi Chen, Pin-Yu Chen, Jeffrey Ding, Ruoxi Jia, Jiaqi Ma, Arvind Narayanan, Weijie J Su, Mengdi Wang, Chaowei Xiao, Bo Li, Dawn Song, Peter Henderson, Prateek Mittal
<br/>
*Preprint (Under Review)*
<br/>
<a href="https://arxiv.org/pdf/2405.19524" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>

📖 [Assessing the brittleness of safety alignment via pruning and low-rank modifications](https://arxiv.org/abs/2402.05162)
<br/>
Boyi Wei\*, Kaixuan Huang\*, Yangsibo Huang\*, **Tinghao Xie**, Xiangyu Qi, Mengzhou Xia, Prateek Mittal, Mengdi Wang, Peter Henderson
<br/>
*ICML 2024*
<br/>
<a href="https://boyiwei.com/alignment-attribution/" style="text-decoration:none">
  <button class="pub_button">🏠Website </button>
</a>
<a href="https://arxiv.org/pdf/2402.05162" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/boyiwei/alignment-attribution-code" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>


📖 [Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!](https://llm-tuning-safety.github.io/)
<br/>
Xiangyu Qi\*, Yi Zeng\*, **Tinghao Xie\***, Pin-Yu Chen, Ruoxi Jia, Prateek Mittal$^†$, Peter Henderson$^†$
<br/>
*ICLR 2024 (oral)*
<br/>
📰 This work was <b style="color: red">exclusively reported by <a href="https://www.nytimes.com/2023/10/19/technology/guardrails-artificial-intelligence-open-source.html">New York Times</a></b>, and covered by many other social medias!
<br/>
<a href="https://llm-tuning-safety.github.io/" style="text-decoration:none">
  <button class="pub_button">🏠Website </button>
</a>
<a href="https://arxiv.org/pdf/2310.03693" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://huggingface.co/datasets/LLM-Tuning-Safety/HEx-PHI" style="text-decoration:none">
  <button class="pub_button">📚Dataset </button>
</a>
<a href="https://github.com/LLM-Tuning-Safety/LLMs-Finetuning-Safety" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>


📖 [BaDExpert: Extracting Backdoor Functionality for Accurate Backdoor Input Detection](https://arxiv.org/abs/2308.12439)
<br/>
**Tinghao Xie**, Xiangyu Qi, Ping He, Yiming Li, Jiachen T. Wang, Prateek Mittal
<br/>
*ICLR 2024*
<br/>
<a href="https://arxiv.org/pdf/2308.12439" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/vtu81/backdoor-toolbox" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>


📖 [Towards A Proactive ML Approach for Detecting Backdoor Poison Samples](https://www.usenix.org/conference/usenixsecurity23/presentation/qi)
<br/>
Xiangyu Qi, **Tinghao Xie**, Jiachen T. Wang, Tong Wu, Saeed Mahloujifar, Prateek Mittal
<br/>
*USENIX Security 2023*
<br/>
<a href="https://www.usenix.org/system/files/usenixsecurity23-qi.pdf" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/Unispac/Fight-Poison-With-Poison" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>


📖 [Revisiting the Assumption of Latent Separability for Backdoor Defenses](https://www.usenix.org/conference/usenixsecurity23/presentation/qi)
<br/>
Xiangyu Qi\*, **Tinghao Xie\***, Yiming Li, Saeed Mahloujifar, Prateek Mittal
<br/>
*ICLR 2023*
<br/>
<a href="https://arxiv.org/pdf/2205.13613" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/Unispac/Circumventing-Backdoor-Defenses" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>


📖 [Towards Practical Deployment-Stage Backdoor Attack on Deep Neural Networks](https://arxiv.org/abs/2111.12965)
<br/>
Xiangyu Qi\*, **Tinghao Xie\***, Ruizhe Pan, Jifeng Zhu, Yong Yang, Kai Bu
<br/>
*CVPR 2022 (oral)*
<br/>
<a href="https://arxiv.org/pdf/2111.12965" style="text-decoration:none">
  <button class="pub_button">📑Paper </button>
</a>
<a href="https://github.com/Unispac/Subnet-Replacement-Attack" style="text-decoration:none">
  <button class="pub_button">💻Github </button>
</a>






<br/>
<br/>
<br/>
