---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

# 🎓 About Me

I am Zechen Sun (孙泽辰), a Ph.D. student at the School of Computer Science and Technology, Soochow University. I am a member of the [OpenNLG](https://opennlg.cn/#/index) group, advised by Assoc. Prof. [Juntao Li](https://lijuntaopku.github.io/) and Prof. [Wenliang Chen](https://chen-wenliang.github.io/), as part of Prof. [Min Zhang](https://zhangmin-nlp-ai.github.io/)'s team. I received my B.Eng. from Soochow University in 2022 and transferred to the Ph.D. program in 2024.

My research interests include **Long-context Language Models** and **Shortcut Learning in Large Language Models**.

I am currently a Research Intern at Xiaohongshu (小红书), Pevek Team (Applied Algorithm Department / Foundation Model Team), focusing on Post-training techniques including SFT data synthesis, on-policy distillation and model generalization.


# 🔥 News
- *2026.06*: &nbsp;🎉🎉 One survey paper accepted by **TACL**!
- *2026.01*: &nbsp;🎉🎉 One paper (IS-CoT) accepted by **ACL 2026**!
- *2025.12*: &nbsp;🎉🎉 One paper (CGMIS) accepted by **AAAI 2026**!
- *2025.09*: &nbsp; Started Research Internship at **Xiaohongshu (小红书)** Redone Team!
- *2025.05*: &nbsp;🎉🎉 One paper (LOGO) accepted by **ICML 2025**!
- *2025.05*: &nbsp;🎉🎉 One paper accepted by **ACL 2025**!
<!-- - *2025.11*: &nbsp;🎉🎉 One survey paper accepted by **TACL** (Conditional Accept)! -->


# 📝 Publications

## 📄 Long-context Language Models

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACL 2026</div><img src='/images/iscot.png' alt="IS-CoT" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**IS-CoT: Breaking the Long-form Generation Collapse via Interleaved Structural Thinking**

**Zechen Sun**, Yuyang Sun, Zecheng Tang, Juntao Li, Wenpeng Hu, Wenliang Chen, Zhunchen Luo, Guotong Geng, Min Zhang

We are the first to identify the "length collapse" problem in long-form text generation by LLMs, where static planning fails to dynamically guide long-context generation. We propose IS-CoT, a framework that embeds a "plan-write-reflect" cycle into the generation process. The trained IS-Writer-8B outperforms larger models including DeepSeek-V3.2 on long-form benchmarks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026</div><img src='/images/cgmis2.png' alt="CGMIS" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**CGMIS: Concept-Graph Based Multi-Hop Instructions Synthesis for Enhancing Long-Context Reasoning**](https://ojs.aaai.org/index.php/AAAI/article/view/40599)

**Zechen Sun**, Zecheng Tang, Juntao Li, Wenpeng Hu, Wenliang Chen, Zhunchen Luo, Qiaoming Zhu

We propose CGMIS, a concept-graph-based framework for synthesizing verifiable multi-hop instruction data with traceable reasoning paths. Using only 10% of the data volume of existing methods, CGMIS achieves SOTA on 13 long-context reasoning tasks. The framework supports building high-quality instruction datasets from arbitrary corpora.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TACL</div><img src='/images/tacl2.png' alt="Survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Data Foundations of Long-Context Language Models: A Survey**

**Zechen Sun**, Yuyang Sun, Zhaochen Su, Zecheng Tang, Juntao Li, Wenliang Chen, Ao Zhou, Min Zhang

The first systematic survey on training and evaluation data characteristics for long-context LLMs. We identify key data properties, summarize construction methods, analyze the relationship between data and model capabilities, and provide comprehensive guidance for long-context LLM data design.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2025</div><img src='/images/logo.png' alt="LOGO" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**LOGO: Long cOntext aliGnment via efficient preference Optimization**](https://proceedings.mlr.press/v267/tang25j.html)

Zecheng Tang, **Zechen Sun**, Juntao Li, Qiaoming Zhu, Min Zhang

We propose LOGO, an efficient long-context alignment training strategy that significantly improves long-context model performance via preference optimization and positional encoding synthesis, achieving GPT-4-level performance with minimal data and hardware cost.
</div>
</div>

---

## 🔍 Shortcut Learning in LLMs & New Architecture Exploration

- <span class="badge" style="position: relative; display: inline-block; top: 0; left: 0;">COLING 2024</span> [**Exploring and Mitigating Shortcut Learning for Generative Large Language Models**](https://aclanthology.org/2024.lrec-main.602/)

  **Zechen Sun**, Yisheng Xiao, Juntao Li, Yixin Ji, Wenliang Chen, Min Zhang

  We investigate whether LLMs exhibit shortcut learning behavior and its root causes (pre-training vs. instruction fine-tuning). We propose FSLI to effectively suppress LLMs' reliance on shortcut features in ICL settings, improving reasoning capabilities.

- <span class="badge" style="position: relative; display: inline-block; top: 0; left: 0;">软件学报</span> [**基于可控性解释的混合数据增强框架**](https://scholar.hit.edu.cn/en/publications/%E5%9F%BA%E4%BA%8E%E5%8F%AF%E6%8E%A7%E6%80%A7%E8%A7%A3%E9%87%8A%E7%9A%84%E6%B7%B7%E5%90%88%E6%95%B0%E6%8D%AE%E5%A2%9E%E5%BC%BA%E6%A1%86%E6%9E%B6/)

  **孙泽辰**, 肖义胜, 李俊涛, 张民, 周国栋

  We propose a controllable explanation-based hybrid data augmentation framework. With minimal fine-tuning data, the model achieves better generalization and robustness on downstream tasks, mitigating shortcut learning in generative LLMs such as LLaMA and FLAN-T5.

- <span class="badge" style="position: relative; display: inline-block; top: 0; left: 0;">ACL 2025</span> [**An Empirical Study of Iterative Refinements for Non-autoregressive Translation**](https://aclanthology.org/2025.acl-long.1443/)

  Yisheng Xiao♡, Pei Guo♡, **Zechen Sun♡**, Juntao Li, Kai Song, Min Zhang &nbsp;(♡equal contribution)

  We explore factors related to iterative non-autoregressive model capabilities and provide targeted recommendations, surpassing previous best models with less decoding time.

- <span class="badge" style="position: relative; display: inline-block; top: 0; left: 0;">ICLR 2024</span> [**Are BERT Family Good Instruction Followers? A Study on Their Potential and Limitations**](https://iclr.cc/virtual/2024/poster/17466)

  Yisheng Xiao, Juntao Li, **Zechen Sun**, Zechang Li, Qingrong Xia, Xinyu Duan, Zhefeng Wang, Min Zhang

  The first exploration of zero-shot instruction-following capability of BERT-family models, providing new possibilities and insights for generative language model framework design.


# 🎖 Honors and Awards
- *2024&2025* &nbsp; Academic Excellence First-Class Scholarship, Soochow University
- *2024* &nbsp; Huawei "Intelligent Base" Scholarship, Soochow University
- *2023&2024* &nbsp; Outstanding Graduate Student, Soochow University
- *2022* &nbsp; Third Prize (National Level), China Collegiate Software Design Competition
- *2022* &nbsp; Outstanding Youth League Member, Soochow University
- *2022* &nbsp; Outstanding Student Leader, Soochow University


# 📖 Educations
- *2022.09 - 2028.06 (expected)*, Ph.D. in Computer Science, School of Computer Science and Technology, Soochow University, Suzhou, China. (Transferred to Ph.D. program in 2024)
- *2018.09 - 2022.06*, B.Eng. in Computer Science (Artificial Intelligence), School of Computer Science and Technology, Soochow University, Suzhou, China.


# 💻 Internships
- *2025.09 - Present*, Research Intern, Pevek Team (Applied Algorithm Department / Foundation Model Team), **Xiaohongshu (小红书)**, China. Focusing on Post-training techniques including SFT data synthesis, data mixture optimization, on-policy distillation, and model generalization.
- *2022.07 - 2022.09*, Algorithm Intern, CTO Line - Business Platform, **Alibaba Group**, Hangzhou, China. Participated in the Soochow University-Alibaba AIR project. Designed category prediction algorithms on large-scale noisy product data (10M+ samples, 13,000+ categories), improving RoBERTa-based model accuracy by ~5%. The model has been deployed in production.
