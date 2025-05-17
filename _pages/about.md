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

Peiyan Hu (胡佩炎 in Chinese) is currently a third year Ph.D. student at [Academy of Mathematics and Systems Science (AMSS), Chinese Academy of Sciences (CAS)](http://www.amss.ac.cn/), advised by Prof. [Zhiming Ma](https://en.wikipedia.org/wiki/Zhi-Ming_Ma) ([EN](https://en.wikipedia.org/wiki/Zhi-Ming_Ma), [CN](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html#home)). She completed her undergraduate studies at [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/) in 2022, majoring in Mathematics with a minor in Computer Science. 

She currently is a visiting student of [AI for Scientific Simulation and Discovery Lab](https://ai4s.lab.westlake.edu.cn/) at [Westlake University](https://en.westlake.edu.cn/), mentored by [Tailin Wu](https://tailin.org/). She was an intern of [Microsoft Research Asia](https://www.msra.cn/) and [Microsoft Research AI4Science](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/), mentored by [Yue Wang](https://www.microsoft.com/en-us/research/people/yuwang5/) and [Qi Meng](https://scholar.google.co.jp/citations?user=t-z3K34AAAAJ&hl=en). She is also a member of [AI4Science Research Project](https://ai4sci-research.github.io). 

Her researches focus on AI for PDE/physical system simulation and control, generative models.

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><img src='images/guidance.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

On the Guidance of Flow Matching \\
[Ruiqi Feng](https://weenming.github.io/), [Tailin Wu](https://tailin.org/), Chenglei Yu, [Wenhao Deng](https://w3nhao.github.io/), **Peiyan Hu** \\
ICML 2025 (<span style="color: red;">spotlight</span>) \\
[[code]](https://github.com/AI4Science-WestlakeU/flow_guidance) [[paper]](https://openreview.net/forum?id=pKaNgFzJBy) [[arXiv]](https://arxiv.org/abs/2502.02150)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/safe.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

From Uncertain to Safe: Conformal Fine-Tuning of Diffusion Models for Safe PDE Control \\
**Peiyan Hu**\*, [Xiaowei Qian](https://xweiq.github.io/)\*, [Wenhao Deng](https://w3nhao.github.io/), [Rui Wang](https://openreview.net/profile?id=~Rui_Wang56), [Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en), [Ruiqi Feng](https://weenming.github.io/), [Tao Zhang](https://zhangtao167.github.io/), [Long Wei](https://longweizju.github.io/), [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Zhi-Ming Ma](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html), [Tailin Wu](https://tailin.org/) \\
ICML 2025 \\
[[code]](https://github.com/AI4Science-WestlakeU/safediffcon) [[paper]](https://openreview.net/forum?id=XGJ33p4qwt) [[arXiv]](https://arxiv.org/abs/2502.02205)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class='paper-box'><div class='paper-box-image'><div style="text-align: center;"><img src='images/mbcc.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Model-Based Closed-Loop Control Algorithm for Stochastic Partial Differential Equation Control \\
**Peiyan Hu**, [Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en), [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Zhiming Ma](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html) \\
IJCAI 2025 \\
[[arXiv]](https://arxiv.org/abs/2505.05521)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/wdno.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Wavelet Diffusion Neural Operator \\
**Peiyan Hu**\*, [Rui Wang](https://openreview.net/profile?id=~Rui_Wang56)\*, [Xiang Zheng](https://xiangzheng2002.github.io/), [Tao Zhang](https://zhangtao167.github.io/), [Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en), [Ruiqi Feng](https://weenming.github.io/), [Long Wei](https://longweizju.github.io/), [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Zhi-Ming Ma](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html), [Tailin Wu](https://tailin.org/) \\
ICLR 2025 \\
[[code]](https://github.com/AI4Science-WestlakeU/wdno) [[paper]](https://openreview.net/forum?id=FQhDIGuaJ4) [[arXiv]](https://arxiv.org/abs/2412.04833)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/CL-DiffPhyCon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

CL-DiffPhyCon: Closed-loop Diffusion Control of Complex Physical Systems \\
[Long Wei](https://longweizju.github.io/)\*, [Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en)\*, [Yuchen Yang](https://openreview.net/profile?id=~Yuchen_Yang11), [Ruiqi Feng](https://weenming.github.io/), **Peiyan Hu**, [Xiang Zheng](https://xiangzheng2002.github.io/), [Tao Zhang](https://zhangtao167.github.io/), [Dixia Fan](https://en.westlake.edu.cn/faculty/dixia-fan.html), [Tailin Wu](https://tailin.org/) \\
ICLR 2025 \\
[[code]](https://github.com/AI4Science-WestlakeU/CL_DiffPhyCon) [[paper]](https://openreview.net/forum?id=PiHGrTTnvb) [[arXiv]](https://arxiv.org/abs/2408.03124)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/Multimodal.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multimodal Policies with Physics-informed Representations \\
[Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en), **Peiyan Hu**, [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Dixia Fan](https://en.westlake.edu.cn/faculty/dixia-fan.html) \\
Preprint \\
[[arXiv]](https://arxiv.org/abs/2410.15250)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/survey.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Recent Advances on Machine Learning for Computational Fluid Dynamics: A Survey \\
Haixin Wang, Yadi Cao, Zijie Huang, Yuxuan Liu, **Peiyan Hu**, Xiao Luo, Zezheng Song, Wanjia Zhao, Jilin Liu, Jinan Sun, Shikun Zhang, Long Wei, Yue Wang, Tailin Wu, Zhi-Ming Ma, Yizhou Sun \\
Preprint \\
[[arXiv]](https://arxiv.org/abs/2408.12171)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/DiffPhyCon.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DiffPhyCon: A Generative Approach to Control Complex Physical Systems \\
[Long Wei](https://longweizju.github.io/)\*, **Peiyan Hu**\*, [Ruiqi Feng](https://weenming.github.io/)\*, [Haodong Feng](https://scholar.google.com/citations?user=0GOKl_gAAAAJ&hl=en), Yixuan Du, [Tao Zhang](https://zhangtao167.github.io/), [Rui Wang](https://openreview.net/profile?id=~Rui_Wang56), [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Zhi-Ming Ma](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html), [Tailin Wu](https://tailin.org/) \\
NeurIPS 2024; ICLR 2024 AI4PDE workshop (<span style="color: red;">oral</span>) \\
[[project page]](https://ai4s.lab.westlake.edu.cn/projects/diffphycon/) [[code]](https://github.com/AI4Science-WestlakeU/diffphycon) [[paper]](https://openreview.net/forum?id=MbZuh8L0Xg) [[arXiv]](https://arxiv.org/abs/2407.06494)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/mesh.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Better Neural PDE Solvers Through Data-Free Mesh Movers \\
**Peiyan Hu**, [Yue Wang](https://scholar.google.com/citations?hl=zh-CN&user=fGv5irIAAAAJ), [Zhi-Ming Ma](http://homepage.amss.ac.cn/research/homePage/8eb59241e2e74d828fb84eec0efadba5/myHomePage.html) \\
ICLR 2024 \\
[[code]](https://github.com/Peiyannn/MM-PDE) [[paper]](https://openreview.net/pdf?id=hj9ZuNimRl) [[arXiv]](https://arxiv.org/abs/2312.05583)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/dlr.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Deep Latent Regularity Network for Modeling Stochastic Partial Differential Equations \\
Shiqi Gong, **Peiyan Hu**, Qi Meng, Yue Wang, Rongchan Zhu, Bingguang Chen, Zhiming Ma, Hao Ni, Tie-Yan Liu \\
AAAI 2023 \\
[[code]](https://github.com/sdogsq/DLR-Net) [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/25938)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/drvn.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

DRVN (Deep Random Vortex Network): A New Physics-Informed Machine Learning Method for Simulating and Inferring Incompressible Fluid Flows \\
Rui Zhang, **Peiyan Hu**, Qi Meng, Yue Wang, Rongchan Zhu, Bingguang Chen, Zhi-Ming Ma, Tie-Yan Liu \\
Physics of Fluids 2022 \\
[[code]](https://github.com/optray/Deep_Random_Vortex_Networks_DRVN) [[paper]](https://pubs.aip.org/aip/pof/article-abstract/34/10/107112/2847899/DRVN-deep-random-vortex-network-A-new-physics?redirectedFrom=fulltext) [[arXiv]](https://arxiv.org/abs/2206.09571)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><img src='images/nors.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Neural Operator with Regularity Structure for Modeling Dynamics Driven by SPDEs \\
**Peiyan Hu**, Qi Meng, Bingguang Chen, Shiqi Gong, Yue Wang, Wei Chen, Rongchan Zhu, Zhi-Ming Ma, Tie-Yan Liu \\
ICLR 2022 workshop \\
[[code]](https://github.com/Peiyannn/Neural-Operator-with-Regularity-Structure) [[arXiv]](https://arxiv.org/abs/2204.06255)

</div>
</div>


# 🎖 Honors and Awards
- National Scholarship (Ph.D.)
- Star of Tomorrow (MSRA)
- Outstanding Graduation Student of Beijing
- Outstanding Graduation Thesis of UCAS
- National Scholarship (Bachelor)
- First-Class Academic Scholarship

# 📑 Academic Service
- Reviewer: NeurIPS, ICLR, IJCAI, Physics of Fluids

# 📖 Educations
- *2022.09 - Now*, Ph.D., Academy of Mathematics and Systems Science (AMSS), Chinese Academy of Sciences (CAS).
- *2018.09 - 2022.06*, Bachelor of Mathematics and Applied Mathematics (major) & Computer Science (minor), University of Chinese Academy of Sciences (UCAS).

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2023.02 - 2023.08*, Research intern with [Yue Wang](https://www.microsoft.com/en-us/research/people/yuwang5/), [AI4Science, Microsoft Research](https://www.microsoft.com/en-us/research/lab/microsoft-research-ai4science/).
- *2021.11 - 2022.07*, Research intern with [Qi Meng](https://scholar.google.co.jp/citations?user=t-z3K34AAAAJ&hl=en) and [Yue Wang](https://www.microsoft.com/en-us/research/people/yuwang5/), [Machine Learning Group, Microsoft Research Asia](https://www.microsoft.com/en-us/research/lab/microsoft-research-asia/).
