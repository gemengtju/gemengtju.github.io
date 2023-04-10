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

I am a PhD candidate student in College of Intelligence and Computing in Tianjin University, supervised by Prof. [Longbiao Wang](http://cic.tju.edu.cn/faculty/wanglongbiao/wang.html) and Prof. [Jianwu Dang](http://www.jaist.ac.jp/~jdang/index-e.htm). My research topic is Speech Separation Based on Deep Learning in Open Complex Environment [[Thesis]](https://note.youdao.com/s/LxdHTMU4) [[Slide]](https://note.youdao.com/s/PYb5Ip4f). During my PhD period, I also worked as a research assistant in NTU and NUS in Singapore from 2019 to 2022, supervised by Prof. [Eng Siong Chng](https://personal.ntu.edu.sg/aseschng/default.html) and Prof. [Haizhou Li](https://colips.org/~eleliha/). Prior to that, I received my Master’s Degree from Tianjin University under the supervision of Prof. [Di Jin](https://scholar.google.com/citations?hl=zh-CN&user=Q8MRRecAAAAJ) and Prof. [Liang Yang](https://yangliang.github.io/) in 2017, and my master's research topic is Socical Network or Community Detection.

My research interest includes speech processing, speech separation and social network analysis. I have published more than 10 papers at the top international AI conferences such as IJCAI, ICASSP, INTERSPEECH.

# 💻 Research Experiences
- *2022.07 - Present*, Research Asistant, Chinese University of Hong Kong (CUHKSZ), Shenzhen, China. [[Project Demo]](https://gemengtju.github.io/demo/AV/index.html)
- *2020.04 - 2022.07*, Research Asistant, National University of Singapore (NUS), Singapore.
- *2019.10 - 2020.04*, Research Asistant, Nanyang Technological University (NTU), Singapore.
- *2018.09 - 2019.06*, Machine Learning Engineer, AI Lab of Didi Chuxing Company (DiDi), Beijing, China.

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div> -->

- *"Time-Domain Speech Separation Networks with Graph Encoding Auxiliary"*, Tingting Wang, Zexu Pan, **Meng Ge<sup>`*`</sup>**, Zhen Yang, Haizhou Li, **SPL** [[PDF]](https://note.youdao.com/s/P2qvfqgz)
- *"VCSE: Time-Domain Visual-Contextual Speaker Extraction Network"*, Junjie Li, **Meng Ge<sup>`*`</sup>**, Zexu Pan, Longbiao Wang, Jianwu Dang, **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/DF6nBHiw)
- *"USEV: Universal Speaker Extraction with Visual Cue"*, Zexu Pan, **Meng Ge`*`**, Haizhou Li, **TASLP 2022** [[PDF]](https://note.youdao.com/s/1SpGwsRf) [[Code]](https://github.com/zexupan/USEV)
- *"Dual-stream Speech Dereverberation Network Using Long-term and Short-term Cues"*, Nan Li, **Meng Ge`*`**, Longbiao Wang, Jianwu Dang,  **IJCNN 2022** [[PDF]](https://note.youdao.com/s/dN2u1EWb)
- *"MIMO-DoAnet: Multi-channel Input and Multiple Outputs DoA Network with Unknown Number of Sound Sources"*, Haoran Yin, **Meng Ge**, Yanjie Fu, Gaoyan Zhang, Longbiao Wang, Lei Zhang, Lin Qiu, Jianwu Dang,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/5NvEDWsS) [[Poster]](https://drive.google.com/file/d/1bTSSorgCL5C4chIGBAmC3Y4nZ6S0-uht/view) [[Code]](https://github.com/TJU-haoran/VCTK-16k-simulated)
- *"Language-specific Characteristic Assistance for Code-switching Speech Recognition"*, Tongtong Song, Qiang Xu, **Meng Ge**, Longbiao Wang, Hao Shi, Yongjie Lv, Yuqin Lin, Jianwu Dang,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/Ej1balFp)
- *"RAW-GNN: RAndom Walk Aggregation based Graph Neural Network"*, Di Jin, Rui Wang, **Meng Ge**, Dongxiao He, Xiang Li, Wei Lin, Weixiong Zhang,  **IJCAI 2022** [[PDF]](https://note.youdao.com/s/S0yzjAhC) [[Video]](https://www.ijcai.org/proceedings/2022/video/293) [[Code]](https://github.com/jindi-tju/RAWGNN)
- *"Iterative Sound Source Localization for Unknown Number of Sources"*, Yanjie Fu, **Meng Ge**, Haoran Yin, Xinyuan Qian, Longbiao Wang, Gaoyan Zhang, Jianwu Dang,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/7W4dnvsz) [[Video]](https://www.bilibili.com/video/BV1kD4y1b75n/) [[Poster]](https://drive.google.com/file/d/1TpxvtH9qwZCaqP2NnKhQ4FAzZqJj83EM/view) [[Code]](https://github.com/FYJNEVERFOLLOWS/ISSL)
- *"Compressing Transformer-Based ASR Model by Task-Driven Loss and Attention-Based Multi-Level Feature Distillation"*, Yongjie Lv, Longbiao Wang, **Meng Ge**, Sheng Li, Chenchen Ding, Lixin Pan, Yuguang Wang, Jianwu Dang, Kiyoshi Honda,  **ICASSP 2022** [[PDF]](https://note.youdao.com/s/JvrvZOCT)
- *"L-SpEx: Localized Target Speaker Extraction"*, **Meng Ge**, Chenglin Xu, Longbiao Wang, Eng Siong Chng, Jianwu Dang, Haizhou Li,  **ICASSP 2022** [[PDF]](https://note.youdao.com/s/2HZePZPa) [[Slide]](https://note.youdao.com/s/IFmvsy7m) [[Poster]](https://note.youdao.com/s/8U7WYBe1) [[Code]](https://github.com/gemengtju/L-SpEx)
- *"A Hybrid Continuity Loss to Reduce Over-Suppression for Time-domain Target Speaker Extraction"*, Zexu Pan, **Meng Ge**, Haizhou Li,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/FS4cCqeJ) [[Code]](https://github.com/zexupan/avse_hybrid_loss)
- *"Global Signal-to-noise Ratio Estimation Based on Multi-subband Processing Using Convolutional Neural Network"*, Nan Li, **Meng Ge**, Longbiao Wang, Masashi Unoki, Sheng Li, Jianwu Dang,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/He8FsxLz)
- *"Self-Distillation Based on High-level Information Supervision for Compressing End-to-End ASR Model"*, Qiang Xu, Tongtong Song, Longbiao Wang, Hao Shi, Yuqin Lin, Yongjie Lv, **Meng Ge**, Qiang Yu, Jianwu Dang,  **INTERSPEECH 2022** [[PDF]](https://note.youdao.com/s/NwZhG4Ze)
- *"Simultaneous Progressive Filtering-Based Monaural Speech Enhancement"*, Haoran Yin, Hao Shi, Longbiao Wang, Luya Qiang, Sheng Li, **Meng Ge**, Gaoyan Zhang, Jianwu Dang,  **ICONIP 2021** [[PDF]](https://note.youdao.com/s/1f13jhRd)
- *"Speech Dereverberation Based on Scale-Aware Mean Square Error Loss"*, Luya Qiang, Hao Shi, **Meng Ge**, Haoran Yin, Nan Li, Longbiao Wang, Sheng Li, Jianwu Dang,  **ICONIP 2021** [[PDF]](https://note.youdao.com/s/K6c9nied)
- *"Robust Voice Activity Detection Using a Masked Auditory Encoder Based Convolutional Neural Network"*, Nan Li, Longbiao Wang, Masashi Unoki, Sheng Li, Rui Wang, **Meng Ge**, Jianwu Dang,  **ICASSP 2021** [[PDF]](https://note.youdao.com/s/Z2D92cOM)
- *"Multi-Stage Speaker Extraction with Utterance and Frame-Level Reference Signals"*, **Meng Ge**, Chenglin Xu, Longbiao Wang, Eng Siong Chng, Jianwu Dang, Haizhou Li,  **ICASSP 2021** [[PDF]](https://note.youdao.com/s/Pe2dMDVn) [[Slide]](https://note.youdao.com/s/4vuxufFG)
- *"Order-aware Pairwise Intoxication Detection"*, **Meng Ge**, Ruixiong Zhang, Wei Zou, Xiangang Li, Cheng Gong, Longbiao Wang, Jianwu Dang,  **ISCSLP 2021** [[PDF]](https://note.youdao.com/s/1HAcQyIb) [[Slide]](https://note.youdao.com/s/Jh9Q8LEt)
- *"Neural Speaker Extraction with Speaker-Speech Cross-Attention Network"*, Wupeng Wang, Chenglin Xu, **Meng Ge**, Haizhou Li,  **INTERSPEECH 2021** [[PDF]](https://note.youdao.com/s/Z3fStirj)
- *"A Pitch-aware Speaker Extraction Serial Network"*, Yu Jiang, **Meng Ge**, Longbiao Wang, Jianwu Dang, Kiyoshi Honda, Sulin Zhang, Bo Yu,  **APASIPA 2021** [[PDF]](https://note.youdao.com/s/RPOysne2)
- *"Spectrograms Fusion with Minimum Difference Masks Estimation for Monaural Speech Dereverberation"*, Hao Shi, Longbiao Wang, **Meng Ge**, Sheng Li, Jianwu Dang,  **ICASSP 2020** [[PDF]](https://note.youdao.com/s/5WwjbDkX)
- *"SpEx+: A Complete Time Domain Speaker Extraction Network"*, **Meng Ge**, Chenglin Xu, Longbiao Wang, Eng Siong Chng, Jianwu Dang, Haizhou Li,  **INTERSPEECH 2020** [[PDF]](https://note.youdao.com/s/3GBVsNyt) [[Slide]](https://note.youdao.com/s/N4kjvwu0) [[Video]](https://youtu.be/ha8RiZFKqhY) [[Code]](https://github.com/gemengtju/SpEx_Plus)
- *"Singing Voice Extraction with Attention-Based Spectrograms Fusion"*, Hao Shi, Longbiao Wang, Sheng Li, Chenchen Ding, **Meng Ge**, Jianwu Dang, Hiroshi Seki, **INTERSPEECH 2020** [[PDF]](https://note.youdao.com/s/YyDRcbZS)
- *"A Fast Convolutional Self-attention Based Speech Dereverberation Method for Robust Speech Recognition"*, Nan Li, **Meng Ge**, Longbiao Wang, Jianwu Dang, **ICONIP 2020** [[PDF]](https://note.youdao.com/s/LkqkbJkS)
- *"Environment-Dependent Attention-Driven Recurrent Convolutional Neural Network for Robust Speech Enhancement"*, **Meng Ge**, Longbiao Wang, Nan Li, Hao Shi, Jianwu Dang, Xiangang Li, **INTERSPEECH 2019** [[PDF]](https://note.youdao.com/s/QXoZ2wMD)
- *"Distant-talking Speech Recognition Based on Multi-objective Learning Using Phase and Magnitude-based Feature"*, Dongbo Li, Longbiao Wang, Jianwu Dang, **Meng Ge**, Haotian Guan, **ISCSLP 2019** [[PDF]](https://note.youdao.com/s/EbKhflJA)
- *"Pitch Synchronized Relative Phase with Peak Error Detection For Noise-robust Speaker Recognition"*, **Meng Ge**, Longbiao Wang, Seiichi Nakagawa, Yuta Kawakami, Jianwu Dang, Xiangang Li, **ISCSLP 2019** [[PDF]](https://note.youdao.com/s/bkYFNJ52)
- *"Integrative Network Embedding via Deep Joint Reconstruction"*, Di Jin, **Meng Ge**, Liang Yang, Dongxiao He, Longbiao Wang, Weixiong Zhang, **IJCAI 2018** [[PDF]](https://note.youdao.com/s/9pAoPK8i)
- *"Using Deep Learning for Community Discovery in Social Networks"*, Di Jin, **Meng Ge**, Zhixuan Li, Wenhuan Lu, Dongxiao He, Francoise Fogelman-Soulie, **ICTAI 2017** [[PDF]](https://note.youdao.com/s/LGVk0ENQ)
- *"Exploring the Roles of Cannot-link Constraint in Community Detection via Multi-variance Mixed Gaussian Generative Model"*, Liang Yang, **Meng Ge**, Di Jin, Dongxiao He, Huazhu Fu, Jing Wang, Xiaochun Cao, **PLOS ONE 2017** [[PDF]](https://note.youdao.com/s/Lq1fLmJD) [[Code]](https://yangliang.github.io/code/MMGG.rar)

# 📖 Educations
- *2017.09 - 2022.10*, Ph.D. in Applied Computer Technology, Tianjin University (TJU), Tianjin, China. 
- *2015.09 - 2017.06*, M.E. in Software Engineering, Tianjin University (TJU), Tianjin, China. 
- *2011.09 - 2015.06*, B.E. in Software Engineering / B.S. in Public Management (double major), Tianjin Polytechnic University (TJPU), Tianjin, China. (GPA: 90.33/100, Ranking: Top3)

# 💻 Work Experiences
- *2015.07 - 2016.07*, Co-Funder, Tianjin Lingyi Technology Co., Ltd, Tianjin, China.
- *2014.03 - 2015.06*, Co-Funder and Senior Software Engineer, Tianjin Chuanhe Technology Co., Ltd, Tianjin, China.
- *2014.01 - 2014.07*, Software Engineer and Team Leader, iSoftStone (Tianjin) Information Technology Group Co, Ltd, Tianjin, China.
- *2013.06 - 2013.07*, Software Engineer & Team Leader, IBM (Tianjin) Experienced Training Program, Tianjin, China.

# 🎖 Certifications and Awards
- Honda Kiyoshi's Advanced Speech Science Award
- ISCA Grant Award of INTERSPEECH 2019
- Oracle Certified Professional (OCP) - Oracle 10g Database Administrator. 
- Oracle Database 10g Administrator Certified Associate (OCA). 
- Outstanding Student Scholarship Award.
- First-Class Scholarship Award
- Outstanding Youth Nomination Award
- Outstanding Graduate Student Award

# 💬 Leadership and Service Experiences
- Reviewers: TASLP, ICASSP 2023
- Conference Volunteer, The National Conference on Man-Machine Speech Communication (NCMMSC'19)
- Volunteer Leader, The 11th International Seminar on Speech Production (ISSP'17)
- Conference Volunteer, The 10th International Symposium on Chinese Spoken Language Processing (ISCSLP'16)
- Foreign-Side Volunteer, The 12th Summer Davos Forum
- Vice Minister, Graduate Student Union, Tianjin University (TJU). 
- Vice Minister, Lenovo Idea Elite Club, Tianjin Polytechnic University (TJPU)
- Captain, Volleyball Team, Tianjin Polytechnic University (TJPU)

