---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I am a master student from [Laboratory of Large-Scale Bioinformatics, the University of Tokyo](https://sites.google.com/site/frithbioinfo) where I am fortunate to be advised by [Prof.Frith](https://scholar.google.com/citations?user=-44WlcwAAAAJ&hl=zh-CN).

I am also extremely grateful to [Dr.Wahib](https://scholar.google.com/citations?user=C3fmEegAAAAJ&hl=en) who introduced me to the world of HPC and computer vision. He is my mentor of research intern in [R-CCS RIKEN](https://www.r-ccs.riken.jp/en/).

My research interests are mainly about **sequence algorithms** and **efficient computer vision**. Please check my publications or [CV(PDF)](files/Resume CHEN YE.pdf) for more information. I am open to other topics as well. If you are interested at sharing ideas and chatting with me, please feel free to send me a message!

Recent News
======
* *Sept, 2025.* Got my **<font color="blue">master degree</font>** at **<font color="blue">the University of Tokyo</font>**!
* *Sept, 2025.* Gave an oral presentation and poster display at **<font color="blue">IIBMP 2025</font>**([link](https://www.jsbi.org/iibmp2025/%e5%8f%a3%e9%a0%ad%e7%99%ba%e8%a1%a8%e3%83%8f%e3%82%a4%e3%83%a9%e3%82%a4%e3%83%88%e3%83%88%e3%83%a9%e3%83%83%e3%82%af/)). 
* *Sept, 2025.* Received **<font color="blue">HPC</font>** and **<font color="blue">parallel computing</font>** training in summer school of R-CCS RIKEN([link](http://www.eccse.kobe-u.ac.jp/simulation_school/kobe-hpc-summer-basic-2025/index.html)) and earned a certificate. 
* *May, 2025.* Got **<font color="blue">research intern</font>** offer from High Performance Artificial Intelligence Systems Research Team, **<font color="blue">RIKEN</font>**!
* *Dec, 2024.* Got **<font color="blue">AI engineer intern</font>** offer from camera algorithm team, 2012 Laboratory, **<font color="blue">Huawei Japan</font>**!
* *Dec, 2024.* [The Statistics of Parametrized Syncmers in a Simple Mutation Process Without Spurious Matches](https://pubmed.ncbi.nlm.nih.gov/39530391/) accepted by journal **<font color="blue">Journal of Computational Biology</font>**!
* *Jun, 2024.* [A Light-Weight Universal Medical Segmentation Network for Laptops Based on Knowledge Distillation](https://link.springer.com/chapter/10.1007/978-3-031-81854-7_6) accepted by conference **<font color="blue">CVPR 2024 workshop: Segment Anything in Medical Images on Laptop</font>**([link](https://www.codabench.org/competitions/1847/)) and won [Meritorious Winner Award(PDF)](files/CVPR2024-Workshop-Awards.pdf)! 

Education
======
<style>
  .edu-entry {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1.5em;
    font-size: 1em; /* Inherit from site-wide font size */
    line-height: 1.5;
  }

  .edu-text {
    max-width: 85%;
  }

  .edu-text strong {
    font-size: 1.1em;
  }

  .edu-logo img {
    height: 4em;
    object-fit: contain;
    vertical-align: middle;
  }

  @media screen and (max-width: 600px) {
    .edu-entry {
      flex-direction: column;
      align-items: flex-start;
    }

    .edu-logo {
      margin-top: 0.5em;
    }
  }
</style>

<div class="edu-entry">
  <div class="edu-text">
    <strong>The University of Tokyo</strong>, Japan<br>
    Master of Science in Sequence Algorithms - Oct. 2022 to Sep. 2025
  </div>
  <div class="edu-logo">
    <img src="{{ '/images/UTokyo.jpg' | relative_url }}" alt="The University of Tokyo logo">
  </div>
</div>

<div class="edu-entry">
  <div class="edu-text">
    <strong>Waseda University</strong>, Japan<br>
    Master of Engineering in Data Mining - Oct. 2020 to Sep. 2022
  </div>
  <div class="edu-logo">
    <img src="{{ '/images/Waseda.jpg' | relative_url }}" alt="Waseda University logo">
  </div>
</div>

<div class="edu-entry">
  <div class="edu-text">
    <strong>Beijing Institute of Technology</strong>, China<br>
    Bachelor of Science in Electric Engineering - Sep. 2017 to Jun. 2021
  </div>
  <div class="edu-logo">
    <img src="{{ '/images/BIT.jpg' | relative_url }}" alt="Beijing Institute of Technology logo">
  </div>
</div>

Internship
======
<!-- <style>
  .exp-entry {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1.5em;
    font-size: 1em;
    line-height: 1.5;
  }

  .exp-text {
    max-width: 85%;
  }

  .exp-text strong {
    font-size: 1.1em;
  }

  .exp-logo img {
    height: 4em;
    object-fit: contain;
    vertical-align: middle;
  }

  @media screen and (max-width: 600px) {
    .exp-entry {
      flex-direction: column;
      align-items: flex-start;
    }

    .exp-logo {
      margin-top: 0.5em;
    }
  }
</style> -->

<style>
  .exp-entry {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 1.5em;
    font-size: 1em;
    line-height: 1.5;
  }

  .exp-text {
    max-width: 85%;
  }

  .exp-text strong {
    font-size: 1.1em;
  }

  /* 【核心改动 1】给 logo 一个统一的“视觉容器” */
  .exp-logo {
    width: 6em;              /* 统一右侧视觉宽度 */
    text-align: right;       /* logo 靠右，更像 CV */
    flex-shrink: 0;          /* 防止被压缩 */
  }

  /* 【核心改动 2】控制 logo 在容器内的最大视觉尺寸 */
  .exp-logo img {
    max-height: 3.5em;       /* 统一视觉高度 */
    max-width: 100%;         /* 不超过容器宽度 */
    object-fit: contain;
    vertical-align: middle;
  }

  @media screen and (max-width: 600px) {
    .exp-entry {
      flex-direction: column;
      align-items: flex-start;
    }

    .exp-logo {
      margin-top: 0.5em;
      width: auto;           /* 手机端放开宽度限制 */
      text-align: left;
    }
  }
</style>

<div class="exp-entry">
  <div class="exp-text">
    <strong>Huawei</strong>, Japan<br>
    Tokyo Research Center, Camera Algorithms Lab<br>
    AI Engineer, Computer Version / Image Processing - Dec. 2024 to Nov. 2025
  </div>
  <div class="exp-logo">
    <img src="{{ '/images/Huawei-1.jpg' | relative_url }}" alt="Huawei logo">
  </div>
</div>

<div class="exp-entry">
  <div class="exp-text">
    <strong>RIKEN</strong>, Japan<br>
    High Performance Artificial Intelligence Systems Research Team<br>
    Research Intern, CV Model Acceleration - May. 2025 to Sep. 2025
  </div>
  <div class="exp-logo">
    <img src="{{ '/images/RIKEN-1.jpg' | relative_url }}" alt="RIKEN logo">
  </div>
</div>

<div class="exp-entry">
  <div class="exp-text">
    <strong>OPPO</strong>, Japan<br>
    Japan Research Center, MLSys Team<br>
    AI Engineer, Model Compression - Feb. 20254 to May. 2024
  </div>
  <div class="exp-logo">
    <img src="{{ '/images/OPPO.jpg' | relative_url }}" alt="OPPO logo">
  </div>
</div>

<div class="exp-entry">
  <div class="exp-text">
    <strong>Baidu</strong>, China<br>
    Search Engine Department<br>
    Algorithm Engineer Intern, Machine Learning - Apr. 2023 to Aug. 2023
  </div>
  <div class="exp-logo">
    <img src="{{ '/images/Baidu.jpg' | relative_url }}" alt="Baidu logo">
  </div>
</div>
