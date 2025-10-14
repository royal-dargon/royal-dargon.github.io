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

Hi! I am currently a PhD student in a joint training program between **Fudan University** and **Shanghai AI Lab**, under the supervision of [Professor Tao Chen](http://www.it.fudan.edu.cn/Data/View/2989), [Associate Professor Nanqing Dong](https://scholar.google.com/citations?user=0DX2YsQAAAAJ&hl=en), and [Professor Wanli Ouyang](https://wlouyang.github.io/). My current research interests are AI4Science and Multimodal. 
I have published papers with total google scholar citations <a href='https://scholar.google.com/citations?user=gShUHBAAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

I received my bachelor's degree in Computer Science and Technology from **Central China Normal University** (Sep. 2020 - Jun. 2024). During my undergraduate years, I was supervised by [Professor Xingpeng Jiang](http://cs.ccnu.edu.cn/info/1097/2097.htm) and [Lecturer Chengji Wang](http://cs.ccnu.edu.cn/info/1097/2753.htm), and my research direction was multi-modal sentiment Analysis (MSA).


# 🔥 News
- *2025.09*: &nbsp;🎉🎉 I have two papers accepted by NeurIPS 2025 (CCF A)
- *2025.05*: &nbsp;🎉🎉 I have one paper accepted by ACL 2025 Main (CCF A)
- *2025.03*: &nbsp;🎉🎉 I have one paper accepted by Briefings in Bioinformatics (SCI Q1, CCF B)
- *2024.12*: &nbsp;🎉🎉 I have one paper accepted by AAAI 2025 (CCF A)
- *2024.06*: &nbsp;🎉🎉 I have one paper accepted by PRCV 2024 (CCF C)
- *2023.12*: &nbsp;🎉🎉 I have one paper accepted by ICASSP 2024 (CCF B)

# 🕙 Preprint

- $^{\dagger}$ represents the corresponding author, $^{\ddagger}$ represents the co-first author

- [Rethinking Multi-Omics LLMs from the Perspective of Omics-Encoding](https://openreview.net/pdf/0c29c5b48dce132666ff2e32a515a58458e66f98.pdf) **<u>Jinzhe Li$^{\ddagger}$</u>**, Zihong Chen$^{\ddagger}$, Jie Ying$^{\ddagger}$, Han Hu$^{\ddagger}$, Zhefan Wang$^{\ddagger}$, haonan he, Wenwei Han, Jiangbin Zheng, Huanjun Kong, Wanli Ouyang, Stan Z. Li, Yuchen Ren$^{\dagger}$, Tao Chen$^{\dagger}$, Nanqing Dong$^{\dagger}$

- [GraphGen: Enhancing Supervised Fine-Tuning for LLMs with Knowledge-Driven Synthetic Data Generation](https://arxiv.org/pdf/2505.20416?) Zihong Chen, Wanli Jiang, **<u>Jinzhe Li</u>**, Zhonghang Yuan, Huanjun Kong, Wanli Ouyang, Nanqing Dong$^{\dagger}$

# 📝 Publications 

- $^{\dagger}$ represents the corresponding author, $^{\ddagger}$ represents the co-first author

- [PRING: Rethinking Protein-Protein Interaction Prediction from Pairs to Graphs](https://arxiv.org/pdf/2507.05101?) Xinzhe Zheng$^{\ddagger}$, Hao Du$^{\ddagger}$, Fanding Xu$^{\ddagger}$, **<u>Jinzhe Li$^{\ddagger}$</u>**, Zhiyuan Liu$^{\dagger}$, Wenkang Wang, Tao Chen, Wanli Ouyang, Stan Z Li, Yan Lu$^{\dagger}$, Nanqing Dong$^{\dagger}$, Yang Zhang$^{\dagger}$ NeurIPS 2025 [CCF A]

- [Alignrag: An adaptable framework for resolving misalignments in retrieval-aware reasoning of rag](https://arxiv.org/pdf/2504.14858) Jiaqi Wei$^{\ddagger}$, Hao Zhou$^{\ddagger}$, Xiang Zhang, Di Zhang, Zijie Qiu, Wei Wei, **<u>Jinzhe Li</u>**, Wanli Ouyang, Siqi Sun$^{\dagger}$ NeurIPS 2025 [CCF A]

- [Many Heads Are Better Than One: Improved Scientific Idea Generation by A LLM-Based Multi-Agent System](https://aclanthology.org/2025.acl-long.1368/) Haoyang Su$^{\ddagger}$, Renqi Chen$^{\ddagger}$, Shixiang Tang$^{\dagger}$, Zhenfei Yin, Xinzhe Zheng, **<u>Jinzhe Li</u>**, Biqing Qi, Qi Wu, Hui Li, Wanli Ouyang, Philip Torr, Bowen Zhou, Nanqing Dong$^{\dagger}$ ACL 2025 Main [CCF A]

- [Deep generative model for protein subcellular localization prediction](https://academic.oup.com/bib/article/26/2/bbaf152/8110879) Guo-Hua Yuan$^{\ddagger}$, **<u>Jinzhe Li$^{\ddagger}$</u>**, Zejun Yang$^{\ddagger}$, Yao-Qi Chen$^{\ddagger}$, Zhonghang Yuan, Tao Chen, Wanli Ouyang, Nanqing Dong$^{\dagger}$, Li Yang$^{\dagger}$ Briefings in Bioinformatics [SCI Q1, CCF B]

- [Towards Efficient and Intelligent Laser Weeding: Method and Dataset for Weed Stem Detection](https://ojs.aaai.org/index.php/AAAI/article/view/35040) Dingning Liu$^{\ddagger}$, **<u>Jinzhe Li$^{\ddagger}$</u>**, Haoyang Su$^{\ddagger}$, Bei Cui$^{\dagger}$, Zhihui Wang, Qingbo Yuan, Wanli Ouyang, Nanqing Dong$^{\dagger}$ AAAI 2025 [CCF A]

- [Uncertainty-aware Gradient Modulation and Feature Masking for Multimodal Sentiment Analysis](https://link.springer.com/chapter/10.1007/978-981-97-8795-1_22) Yuxian Wu, Chengji Wang$^{\dagger}$, **<u>Jinzhe Li</u>**, Wenjing Zhang, and Xingpeng Jiang$^{\dagger}$ PRCV 2024 [CCF C]

- [Modality-Dependent Sentiments Exploring for Multi-Modal Sentiment Classification](https://ieeexplore.ieee.org/abstract/document/10445820) **<u>Jinzhe Li</u>**, Chengji Wang$^{\dagger}$, Zhiming Luo, Yuxian Wu, Xingpeng Jiang$^{\dagger}$ ICASSP 2024 [CCF B]

# 🏆 Awards and Scholarships
- *Jun. 2024*. Award for **Outstanding Graduate Student**.

# 📖 Educations
- *Sep. 2024 - Jun. 2029 (expected)*. Joint PhD at Fudan University-Shanghai AI Lab.
- *Sep. 2020- Jun. 2024*. Bachelor student at Central China Normal University.

# 💻 Internship and Community
- *Oct. 2023 - Now*. Research intern. [ShangHai AI Lab](https://www.shlab.org.cn/)
- *Oct. 2020 - Dec. 2022*. Supervisor and Backend Group Member. [Muxi Studio](https://muxi-tech.xyz/) 

# 🔍 Reviews
- **Conferences**: AAAI, ICLR, ECML, ISBI
- **Journals**: Coming Soon.

<div align="center">
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
</div>



