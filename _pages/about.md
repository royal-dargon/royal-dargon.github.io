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

I am currently a PhD student in a joint training program between Fudan University and Shanghai AI Lab, under the supervision of [Professor Tao Chen](http://www.it.fudan.edu.cn/Data/View/2989) , [Professor Ouyang Wanli](https://wlouyang.github.io/) and [Researcher Nanqing Dong](https://scholar.google.com/citations?user=0DX2YsQAAAAJ&hl=en). My current research interests are AI4Science and Generative Model. And I work really closely with [HuanJun Kong](https://github.com/tpoisonooo). 

I received my bachelor's degree in Computer Science and Technology from **Central China Normal University** (Sep. 2020 - Jun. 2024). During my undergraduate years, I was supervised by [Professor Xingpeng Jiang](http://cs.ccnu.edu.cn/info/1097/2097.htm) and [Lecturer Chengji Wang](http://cs.ccnu.edu.cn/info/1097/2753.htm), and my research direction was multi-modal sentiment Analysis (MSA).


# 🔥 News
- *2024.12*: &nbsp;🎉🎉 I have one paper accepted by 2025 AAAI Conference on Artificial Intelligence (AAAI, CCF A)
- *2024.06*: &nbsp;🎉🎉 I have one paper accepted by 2024 Chinese Conference on Pattern Recognition and Computer Vision (PRCV, CCF C)
- *2023.12*: &nbsp;🎉🎉 I have one paper accepted by 2024 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF B)

# 🕙 Preprint

- $^{\dagger}$ represents the corresponding author, $^{\ddagger}$ represents the co-first author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/DeepGPS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep generative model for protein subcellular localization prediction ](https://www.biorxiv.org/content/10.1101/2024.10.29.620765v2)

Guo-Hua Yuan$^{\ddagger}$, **<u>Jinzhe Li$^{\ddagger}$</u>**, Zejun Yang$^{\ddagger}$, Yao-Qi Chen$^{\ddagger}$, Zhonghang Yuan, Tao Chen, Wanli Ouyang, Nanqing Dong$^{\dagger}$, Li Yang$^{\dagger}$
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">under review</div><img src='images/agent.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Two Heads Are Better Than One: A Multi-Agent System Has the Potential to Improve Scientific Idea Generation](https://arxiv.org/abs/2410.09403)

Haoyang Su$^{\ddagger}$, Renqi Chen$^{\ddagger}$, Shixiang Tang$^{\dagger}$, Xinzhe Zheng, **<u>Jinzhe Li</u>**, Zhenfei Yin, Wanli Ouyang, Nanqing Dong$^{\dagger}$
</div>
</div>


# 📝 Publications 

- $^{\dagger}$ represents the corresponding author, $^{\ddagger}$ represents the co-first author

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">PRCV 2024</div><img src='images/UGF.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
[Uncertainty-aware Gradient Modulation and Feature Masking for Multimodal Sentiment Analysis](https://link.springer.com/chapter/10.1007/978-981-97-8795-1_22)

Yuxian Wu, Chengji Wang$^{\dagger}$, **<u>Jinzhe Li</u>**, Wenjing Zhang, and Xingpeng Jiang$^{\dagger}$

- We propose a novel modality uncertainty estimation method for regression problem, it utilizes the normalized absolute distance between predictions and labels to estimates the modality uncertainties.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICASSP 2024</div><img src='images/MDSE.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Modality-Dependent Sentiments Exploring for Multi-Modal Sentiment Classification](https://ieeexplore.ieee.org/abstract/document/10445820)

**<u>Jinzhe Li</u>**, Chengji Wang$^{\dagger}$, Zhiming Luo, Yuxian Wu, Xingpeng Jiang$^{\dagger}$

- We propose a Modality-Dependent Sentiment Exploring framework(MDSE).
</div>
</div>

# 🏆 Awards and Scholarships
- *Jun. 2024*. Award for **Outstanding Graduate Student**.

# 📖 Educations
- *Sep. 2024 - Jun. 2029 (expected)*. Joint PhD at Fudan University-Shanghai AI Lab.
- *Sep. 2020- Jun. 2024*. Bachelor student at Central China Normal University.

# 💻 Internship and Community
- *Oct. 2023 - Now*. Research intern. [ShangHai AI Lab](https://www.shlab.org.cn/)
- *Oct. 2020 - Dec. 2022*. Supervisor and Backend Group Member. [Muxi Studio](https://muxi-tech.xyz/) 

# 🔍 Reviews
- **Conferences**: ECML, ISBI
- **Journals**: Coming Soon.

<!-- <div align="center">
<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
This homepage is visited <font color="purple" size="5"><span id="busuanzi_value_site_pv"></span></font> times
</div>

<div>

<script>
async function fetchLastCommitTime() {
    const owner = 'royal-dargon';
    const repo = 'royal-dargon.github.io';
    const url = `https://api.github.com/repos/${owner}/${repo}/commits`;
    try {
        const response = await fetch(url);
        if (!response.ok) {
            throw new Error(`Failed to fetch data from GitHub: ${response.statusText}`);
        }
        const data = await response.json();
        const lastCommitDate = new Date(data[0].commit.committer.date);
        document.getElementById('lastCommitTime').textContent = `Last Updated in ${lastCommitDate.toLocaleDateString()}`;
    } catch (error) {
        console.error('Error fetching commit time:', error);
        // document.getElementById('lastCommitTime').textContent = 'Failed to fetch commit time.';
    }
}
fetchLastCommitTime();
</script>
</div> -->

<a href="https://info.flagcounter.com/wSJA"><img src="https://s01.flagcounter.com/count2/wSJA/bg_FFFFFF/txt_000000/border_CCCCCC/columns_5/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>


