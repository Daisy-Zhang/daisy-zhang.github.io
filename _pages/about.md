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

I am currently a fourth year joint Ph.D. student in the [Image and Visual Representation Lab (IVRL)](https://www.epfl.ch/labs/ivrl/), the School of Computer and Communication Sciences at [École Polytechnique Fédérale de Lausanne (EPFL)](https://www.epfl.ch/en/), Lausanne, Switzerland, luckily supervised by [Prof. Sabine Süsstrunk](https://people.epfl.ch/sabine.susstrunk?lang=en) and working with [Dr. Tong Zhang](https://sites.google.com/view/tong-zhang).

Before that, I received my bachelor degree from the Department of Computer Science and Technology, [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China. My bachelor's thesis was supervised by [Prof. Hang Su](https://www.suhangss.me/) and [Prof. Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml). And I feel lucky to further collaborate with [Prof. Hang Su](https://www.suhangss.me/), [Prof. Jianmin Li](https://www.cs.tsinghua.edu.cn/csen/info/1154/3991.htm) and [Prof. Jun Zhu](https://ml.cs.tsinghua.edu.cn/~jun/index.shtml) from Tsinghua University.
I am also enrolled in a Ph.D. program at the University of Chinese Academy of Sciences, [Chinese Academy of Sciences](https://english.cas.cn/), Beijing, China, luckily supervised by [Prof. Shiming Ge](https://imsg.ac.cn/people/geshiming.html) and [Prof. Can Ma](https://people.ucas.ac.cn/~macan).

Currently, my research focuses on Multimodal Media Forensics and AI Safety, including investigating the mechanism of generative models (such as Large Language Models and Diffusion Models) and how to detect generated or manipulated content.
If you are also interested in similar topics or seeking any form of research collaboration, please feel free to reach out to me by email. I always enjoy working with excellent researchers!

<font color="red"> I am actively looking for **full-time positions**. Do not hesitate to contact me if you are interested. </font>

# 🔥 News
- *2024.10*: &nbsp;📄 Present our work in [ECCV 2024](https://eccv.ecva.net/virtual/2024/calendar), Milano, Italy. Welcome to join us during the poster session!
- *2024.07*: &nbsp;🙌 Volunteer in [ICCP 2024](https://iccp-conference.org/iccp2024/), Lausanne, Switzerland. Welcome to join our conference!
- *2024.06*: &nbsp;🎉 One paper Accepted by [ECCV 2024](https://eccv.ecva.net/)! Thanks for all my co-authors!
- *2024.02*: &nbsp;🔈 Supervise two [BS/MS Semester Projects](https://www.epfl.ch/labs/ivrl/available-projects/) on Large Language Models/Diffusion Models Safety during spring semester at EPFL. Feel free to send me an email if you are interested in these topics and working with me.
- *2024.01*: &nbsp;🙋 Invited talk on [the TechDay of International School of Geneve](https://www.ecolint.ch/en) on Deepfake. Happy to share ideas with young students!
- *2023.09*: &nbsp;😃 I am lucky to join the [IVRL](https://www.epfl.ch/labs/ivrl/) group at EPFL for a joint Ph.D. program under the supervision of [Prof.Sabine Süsstrunk](https://people.epfl.ch/sabine.susstrunk?lang=en).

# 📖 Educations
- *2023.09 - now*, Ph.D. Student, Joint Ph.D. program, School of Computer and Communication Sciences, [École Polytechnique Fédérale de Lausanne (EPFL)](https://www.epfl.ch/en/), Lausanne, Switzerland.
- *2021.12 - 2023.09*, Ph.D. Student, Joint Ph.D. program, Department of Computer Science and Technology, [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China. 
- *2020.09 - 2021.12*, Ph.D. Student, University of Chinese Academy of Sciences, [Chinese Academy of Sciences](https://english.cas.cn/), Beijing, China.
- *2016.09 - 2020.06*, Bachelor, Department of Computer Science and Technology, [Tsinghua University](https://www.tsinghua.edu.cn/en/), Beijing, China. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/eccv24.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Natural Consistency Representation for Face Forgery Video Detection](https://arxiv.org/abs/2407.10550)

**Daichi Zhang**, Zihao Xiao, Shikun Li, Fanzhao Lin, Jianmin Li, Shiming Ge.

European Conference on Computer Vision (*ECCV*) 2024.

- Learning the natural consistency representation of real face videos with two designed self-supervised tasks to detect fake ones. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2023</div><img src='images/arxiv23.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Latent Spatiotemporal Adaptation for Generalized Face Forgery Video Detection](https://arxiv.org/abs/2309.04795)

**Daichi Zhang**, Zihao Xiao, Jianmin Li, Shiming Ge.

arXiv preprint arXiv:2309.04795.

- Improve the detector's generalization by adapting the spatiotemporal clues from labeled source domain to unlabeled target domain.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/mm22.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deepfake Video Detection with Spatiotemporal Dropout Transformer](https://dl.acm.org/doi/abs/10.1145/3503161.3547913)

**Daichi Zhang**, Fanzhao Lin, Yingying Hua, Pengju Wang, Dan Zeng, Shiming Ge.

ACM International Conference on Multimedia (*ACM MM*) 2022: 5833-5841. $${\color{red}{(Oral)}}$$

- A Transformer-based detector by mining the local patch-level spatiotemporal inconsistency. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2021</div><img src='images/ijcai21.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Detecting Deepfake Videos with Temporal Dropout 3DCNN](https://www.ijcai.org/proceedings/2021/0178.pdf)

**Daichi Zhang**, Chenyu Li, Fanzhao Lin, Dan Zeng, Shiming Ge.

International Joint Conferences on Artificial Intelligence (*IJCAI*) 2021: 1288-1294.

- A 3DCNN-based detector by exploring the multi-scale spatiotemporal coherence with temporal augmentation. 
</div>
</div>

- [Deepfake Video Detection via Predictive Representation Learning.](https://dl.acm.org/doi/full/10.1145/3536426) Shiming Ge, Fanzhao Lin, Chenyu Li, **Daichi Zhang**, Weiping Wang, Dan Zeng. ACM Transactions on Multimedia Computing, Communications, and Applications (*TOMM*) 2022, 18(2s): 1-21.
- [Interpret the Predictions of Deep Networks via Re-Label Distillation.](https://ieeexplore.ieee.org/abstract/document/9428072/?casa_token=3i1SkWCrJUUAAAAA:fqA8v736ixJJO7oOyr24XTffmCYJLszA4Y5vjac6dk2Q0axzdXVh_AlJfTk94TP8CLR14E1CiDi6) Yingying Hua, Shiming Ge, **Daichi Zhang**. IEEE International Conference on Multimedia and Expo (*ICME*) 2021: 1-6.
- [Interpretable Face Manipulation Detection via Feature Whitening.](https://arxiv.org/abs/2106.10834) Yingying Hua, **Daichi Zhang**, Pengju Wang, Shiming Ge. International Conference on Machine Learning Workshop (*ICML Workshop*) 2021.
- [Look Through Masks: Towards Masked Face Recognition with De-occlusion Distillation.](https://dl.acm.org/doi/abs/10.1145/3394171.3413960?casa_token=-RpotDqKpjEAAAAA:82CNFQArjJS3XHGfVN4plecder5xdOYECThEGX2Qdjf4CQn5XRJPAbn_YX2KcZ5HJTwD7Od3E6lOsR4) Chenyu Li, Shiming Ge, **Daichi Zhang**, Jia Li. ACM International Conference on Multimedia (ACM MM) 2020: 3016-3024.
- [Research Progress in the Interpretability of Deep Learning Models.](https://jcs.iie.ac.cn/xxaqxb/ch/reader/view_abstract.aspx?file_no=20200302&flag=1) Yingying Hua, **Daichi Zhang**, Shiming Ge. Journal of Cyber Security 5.3 (2020): 1-12.

---
- [A Method and Device for Face Forgery Video Detection](http://epub.cnipa.gov.cn/Index). Shiming Ge, **Daichi Zhang**, Chenyu Li, Yingying Hua, Weiping Wang. Chinese Patent 2020. No. ZL202010994947.4.

# 🔨 Projects
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Github</div><img src='images/dfd.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Awesome Deepfake Detection [Github]](https://github.com/Daisy-Zhang/Awesome-Deepfakes-Detection)

- A collection list of Deepfakes Detection related datasets, tools, papers, and code to facilitate the development of related community. 
</div>
</div>

- [Deepfake Detection Challenge (DFDC) 2020](https://www.kaggle.com/c/deepfake-detection-challenge): World rank top 20 with Tsinghua University.
- [ZGC Forum - Artificial Intelligence Security Competition 2022](https://compete.zgc-aisc.com/login): Assist organization with Tsinghua University.
- [The 3rd China Artificial Intelligence Competition on Deepfake Video Detection 2021](https://ai.xm.gov.cn/): B-level prize with Tsinghua University.
- [Huawei Student Developer Competition 2020](https://developer.huawei.com/consumer/cn/programs/hsd): Second prize.

Besides, I also serve as a reviewer for top-tier journals (including TIP, TCSVT) and conferences (including CVPR, ECCV, ICLR, ACM MM).

# 🎖 Awards
- *2021.06*, Merit Student, University of Chinese Academy of Sciences.
- *2019.10*, National Encouragement Scholarship, Philobiblion Scholarship, Tsinghua University.
- *2019.06*, Merit Student, Tsinghua University.

# 💻 Internships
- *2019.10 - 2020.06*, Algorithm Engineer, [Ant Group](https://www.antgroup.com/en), Beijing, China.
- *2019.06 - 2019.09*, Algorithm Engineer, [Tecent](https://www.tencent.com/en-us/about.html), Shenzhen, China.
