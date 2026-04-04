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

I am a Research Assistant at the [EIT-NLP Lab](https://idt.eitech.edu.cn/nlp/), advised by [Prof. Xiaoyu Shen (沈晓宇)](https://chin-gyou.github.io/). My research focuses on efficient multimodal large language models (MLLMs), particularly MLLM compression and streaming LLMs. I plan to pursue a PhD in 2026 through a joint program between Eastern Institute of Technology, Ningbo (宁波东方理工大学) and Shanghai Jiao Tong University (上海交通大学).


My recent work explores compression techniques for MLLMs, including image, video, audio, 3D and Omni LLMs. If you are interested in academic collaboration, please feel free to reach out via email (haowu.ai.research@gmail.com). **We are always looking for motivated interns!**


My research interest includes MLLMs and World Models. Beyond accelerating models through compression, I aim to identify and reuse redundancy in representations, attention patterns, and multimodal interactions to develop efficient architectures that improve both performance and computational efficiency in the long run. I have published 7 papers <a href='https://scholar.google.com/citations?user=Ix9RD18AAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> at top-tier AI conferences and journals (e.g., ICLR, CVPR, ECCV, TMM, TMI, and TGRS), including one Best Paper Finalist.  


<!-- 🔥 📚 👀 🌟 ✨ ✒️ 🎯 📄 🙏 ✉️ 🤗 🌐 🚀 🔔 💡 🔧 ⭐️ 📋 -->


# 🔥 News
- *2026.03*: &nbsp;📰 Our ICLR 2026 paper on mllm compression has received media coverage from [MachineSapiens（机器之心）](https://mp.weixin.qq.com/s/QKGZ7cFi0zJ7XeDlBp4uwQ?scene=1&click_id=5), showcasing its impact on efficient MLLMs.
- *2026.03*: &nbsp;📰 Our CVPR 2026 paper on streaming video reasoning has received media coverage from [QbitAI（量子位）](https://mp.weixin.qq.com/s/czMmpq25L2j1SVP9nrxXvg), showcasing its impact on efficient and real-time video reasoning.
- *2026.03*: &nbsp;📢 We release a systematic survey about Streaming LLMs: "From Static Inference to Dynamic Interaction: Navigating the Landscape of Streaming Large Language Models". [![Preprint](https://img.shields.io/badge/arXiv-2603.04592-b31b1b)](https://arxiv.org/abs/2603.04592) [![GitHub](https://img.shields.io/badge/GitHub-Awesome--Streaming--LLMs-white?logo=github)](https://github.com/EIT-NLP/Awesome-Streaming-LLMs)
- *2026.02*: &nbsp;📢 We release a systematic survey about MLLM compression: "From Data to Model: A Survey of the Compression Lifecycle in MLLMs". [![Preprint](https://img.shields.io/badge/TechRxiv-DOI-b31b1b)](https://www.techrxiv.org/users/1031130/articles/1390890-from-data-to-model-a-survey-of-the-compression-lifecycle-in-mllms) [![GitHub](https://img.shields.io/badge/GitHub-Awesome--MLLM--Compression-white?logo=github)](https://github.com/EIT-NLP/Awesome-MLLM-Compression)
- *2026.02*: &nbsp;🎉 Two papers are accepted by CVPR 2026.
- *2026.02*: &nbsp;🎉 One paper is accepted by TMM 2026.
- *2026.01*: &nbsp;🎉 One paper is accepted by ICLR 2026.
- *2025.06*: &nbsp;🎉 One paper is accepted by TMI 2025.
- *2024.10*: &nbsp;🎉 One paper is accepted by ECCV 2024 and nominated as a 🏆Best Paper Award Candidate.
- *2024.03*: &nbsp;🎉 One paper is accepted by TGRS 2024.



# 📝 Selected Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>
 -->
See full list in [Publications](https://scholar.google.com.hk/citations?user=Ix9RD18AAAAJ).


### MLLM Compression
- ![Preprint](https://img.shields.io/badge/TechRxiv-Survey-b31b1b) [From Data to Model: A Survey of the Compression Lifecycle in MLLMs.](https://www.techrxiv.org/users/1031130/articles/1390890-from-data-to-model-a-survey-of-the-compression-lifecycle-in-mllms) **Hao Wu<sup>\*</sup>**, Junlong Tong<sup>\*</sup>, Xudong Wang, Yang Tan, Changyu Zeng, Anastasia Antsiferova, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/Awesome-MLLM-Compression?logo=github)](https://github.com/EIT-NLP/Awesome-MLLM-Compression)
- ![Preprint](https://img.shields.io/badge/arXiv-2602.07574-b31b1b) [ViCA: Efficient Multimodal LLMs with Vision-Only Cross-Attention](https://arxiv.org/abs/2602.07574). Wenjie Liu<sup>\*</sup>, **Hao Wu<sup>\*</sup>**, Xin Qiu, Yingqi Fan, Yihan Zhang, Anhao Zhao, Yunpu Ma, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/ViCA?logo=github)](https://github.com/EIT-NLP/ViCA)

- ![PDF](https://img.shields.io/badge/CVPR-2026-1f6feb) [UTPTrack: Towards Simple and Unified Token Pruning for Visual Tracking](https://arxiv.org/abs/2602.23734). **Hao Wu<sup>\*</sup>**, Xudong Wang<sup>\*</sup>, Jialiang Zhang, Junlong Tong, Xinghao Chen, Junyan Lin, Yunpu Ma, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/UTPTrack?logo=github)](https://github.com/EIT-NLP/UTPTrack)

- ![PDF](https://img.shields.io/badge/ICLR-2026-1f6feb) [HiDrop: Hierarchical Vision Token Reduction in MLLMs via Late Injection, Concave Pyramid Pruning, and Early Exit](https://arxiv.org/abs/2602.23699). **Hao Wu<sup>\*</sup>**, Yingqi Fan<sup>\*</sup>, Jinyang Dai, Junlong Tong, Yunpu Ma, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/HiDrop?logo=github)](https://github.com/EIT-NLP/HiDrop)

### Streaming LLMs
- ![Preprint](https://img.shields.io/badge/arXiv-Survey-b31b1b) [From Static Inference to Dynamic Interaction: A Survey of Streaming Large Language Models.](https://arxiv.org/abs/2603.04592) Junlong Tong, Zilong Wang, YuJie Ren, Peiran Yin, **Hao Wu**, Wei Zhang, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/Awesome-Streaming-LLMs?logo=github)](https://github.com/EIT-NLP/Awesome-Streaming-LLMs)
- ![Preprint](https://img.shields.io/badge/arXiv-2601.06843-b31b1b) [Speak While Watching: Unleashing TRUE Real-Time Video Understanding Capability of Multimodal Large Language Models](https://arxiv.org/abs/2601.06843). Junyan Lin<sup>\*</sup>, Junlong Tong<sup>\*</sup>, **Hao Wu**<sup>\*</sup>, Jialiang Zhang<sup>\*</sup>, Jinming Liu, Xin Jin, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/Speak-While-Watching?logo=github)](https://github.com/EIT-NLP/Speak-While-Watching)

- ![PDF](https://img.shields.io/badge/CVPR-2026-1f6feb) [Think-as-You-See: Streaming Chain-of-Thought Reasoning for Large Vision-Language Models](https://arxiv.org/abs/2603.02872). Jialiang Zhang<sup>\*</sup>, Junlong Tong<sup>\*</sup>, Junyan Lin<sup>\*</sup>, **Hao Wu**, Yirong Sun, Yunpu Ma, Xiaoyu Shen<sup>†</sup>. [![GitHub stars](https://img.shields.io/github/stars/EIT-NLP/StreamingLLM?logo=github)](https://github.com/EIT-NLP/StreamingLLM/tree/main/TaYS)

### Pathology MLLMs
- ![PDF](https://img.shields.io/badge/TMI-2025-1f6feb) [PathBench: Advancing the Benchmark of Large Multimodal Models for Pathology Image Understanding at Patch and Whole Slide Level](https://ieeexplore.ieee.org/abstract/document/11062674/). Yuxuan Sun, **Hao Wu**, Chenglu Zhu, et al, Tao Lin<sup>†</sup>, Lin Yang<sup>†</sup>.

- ![PDF](https://img.shields.io/badge/ECCV-2024-1f6feb) <span style="color:#e74c3c">(Best Paper Award Candidate)</span> [PathMMU: A Massive Multimodal Expert-Level Benchmark for Understanding and Reasoning in Pathology](https://arxiv.org/abs/2401.16355). Yuxuan Sun, **Hao Wu**, Chenglu Zhu, et al, Tao Lin<sup>†</sup>, Lin Yang<sup>†</sup>. 


### Others
- ![PDF](https://img.shields.io/badge/TMM-2026-1f6feb) [A Transformer-Based Tracker Integrating Motion and Representation Information](https://ieeexplore.ieee.org/abstract/document/11395545/). Yuanhui Wang, Ben Ye, Zhanchuan Cai<sup>†</sup>, **Hao Wu**. 

- ![PDF](https://img.shields.io/badge/TGRS-2024-1f6feb) [Crater-DETR: A novel transformer network for crater detection based on dense supervision and multiscale fusion](https://ieeexplore.ieee.org/abstract/document/10466735/). Yue Guo, **Hao Wu**, Shuojin Yang, Zhanchuan Cai<sup>†</sup>. 

# 🏆 Honors and Awards
- *2024.10* ECCV 2024 Best Paper Candidate (Top 0.2%).

<!-- # 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  --> 

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2022.05 - 2022.08*, Yunqi Academy of Engineering, Hangzhou. -->

# 🌐 Academic Services
- Invited Reviewer for IEEE TMM.
<!-- Invited Reviewer for NeurIPS. -->