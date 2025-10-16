---
permalink: /
title: "Biography"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


<!-- Biography
------ -->
I am a PhD candidate in the [Electrical Engineering program](https://engineering.uci.edu/dept/eecs) at the University of California, Irvine, advised by Prof. [Athina Markopoulou](https://athinagroup.eng.uci.edu/athina/). I received my B.E. degree in Electrical Engineering from Northeastern University (China) in 2019, my M.Sc. degree in Electrical Engineering from University of Southern California in 2021. I was a visiting student at City University of Hong Kong in 2018, supervised by Prof. [Linqi Song](https://sites.google.com/site/aisquaredlab/about-us/linqi?authuser=0).

My research interests are in the areas of agentic AI, privacy-preserving machine learning, federated learning, data valuation and model efficiency.

<!-- Education
======

* **University of California, Irvine, 09/2021 - Present**
  * Degree: PhD
  * Major: Electrical Engineering
  * GPA: 4.0/4.0

* **University of Southern California, 08/2019 - 05/2021**
  * Degree: Master
  * Major: Electrical Engineering
  * GPA: 3.71/4.0

* **Northeastern University (China), 09/2015 - 06/2019**
  * Degree: Bachelor
  * Major: Electronic Information Engineering
  * GPA: 93/100 -->

<!-- Research Experience
======

* PriPrune: Quantifying and Preserving Privacy in Pruned FL, 2022.11 – 2023.8.
  * Advisor: Prof. Athina Markopoulou (University of California Irvine).
  * Performed the first investigation of privacy guarantees for model pruning in FL. We also derived information-
theoretic upper bounds on the amount of information leaked by pruned FL models.
  * Introduced PriPrune – a privacy-aware algorithm for local model pruning, which uses a personalized per-
client defense mask and adapts the defense pruning rate so as to jointly optimize privacy and model perfor-
mance.

* Information Leakage In Personalized Federated Learning, 2022.4 – 2022.6.
  * Advisor: Prof. Athina Markopoulou (University of California Irvine).
  * Launched the gradient leakage attack (DLG attack) in personalized federated learning and articulated how personalized FL can influence the DLG attack with regard to different level of personalization. We showed that with low-level personalization, the DLG attack could easily reconstruct clients’ training data but with high-level personalization, the overall performance of DLG attack deteriorated a lot.
  * Proposed the PerFed-LDP, the per-example level differential privacy for personalized federated learning. We analyzed the privacy-utility tradeoff of PerFed-LDP and demonstrated the results of DLG attack in differentially private personalized FL.

* Privacy by Projection: Federated Population Density Estimation by Projecting on Random Features, 2021.12 – 2022.07.
  * Advisor: Prof. Athina Markopoulou (University of California Irvine).
  * Proposed a federated KDE framework for estimating the user population density,which not only kept users’ data local, but also protected against a malicious server that tries to infer users’ locations.
  * Our proposed federated Random Fourier feature (RFF) KDE leveraged a random feature representation of the KDE solution, in which each user’s information was irreversibly projected onto a small number of spatially delocalized basis functions.

* Location Leakage in Federated Signal Maps, 2021.11 – 2022.04.
  * Advisor: Prof. Athina Markopoulou (University of California Irvine).
  * launched the gradients leakage attack (DLG attack) on signal map prediction tasks and successfully recon- structed the average location of users’ private spatiotemporal dataset during the federated training process.
  * Proposed a defense approach that selects local batches so that the inferred location is far from the true average location, thus misleading the DLG attacker. Explored the tradeoff between utility in federated
signal map task and privacy in protecting clients’ data.

* SaferQ: Obfuscating Search Queries via Generative Adversarial Privacy, 2020.03 – 2020.05.
  * Advisor: Prof. Keith Chugg (University of Southern California).
  * Our proposed SaferQ extended the existing Generative Adversarial Privacy framework for sequence gen- eration problems. Deployed between browser and query log databases. Query logs will be obfuscated by SaferQ based on our desired privacy and utility tradeoff ratio.

* Secure Federated XGBoost Framework, 2018.09 – 2019.08.
  * Advisor: Prof. Linqi Song (City University of Hong Kong).
  * Our proposed secure federated XGBoost algorithm incorporated data aggregation and sparse federated up-
date processes to balance the tradeoff between privacy and learning performance.
  * Based on the characteristics of split finding in XGBoost, we introduced the anonymous virtual data cluster
in the data aggregation process and thus hided a specific user’s gradients under the anonymous cluster.


Work Experience
======

* 07/2022 - 09/2022: Engineering Intern
  * Syntiant Corp.
  * Research on keyword spotting with student-teacher framework.
  
* 06/2020 - 01/2021: Data Science Internship
  * Ericsson Inc.
  * Research on secure federated learning with XGBoost. -->

<!-- Preprints
====== -->

<!-- Publications
============

Chu, Tianyue\*, **Yang, Mengwei**\*, and Laoutaris, Nikolaos, and Markopoulou, Athina. “[PriPrune: Quantifying and Preserving Privacy in Pruned Federated Learning](https://arxiv.org/pdf/2310.19958.pdf)”, arXiv preprint arXiv:2310.19958 (2023), under review.

Bakopoulou, Evita\*, **Yang, Mengwei**\*, and Zhang, Jiang and Psounis, Konstantinos and Markopoulou, Athina, "[Location leakage in federated signal maps](https://arxiv.org/pdf/2112.03452.pdf).", accepted in IEEE Transactions on Mobile Computing, Oct. 2023

Zong, Zixiao and **Yang, Mengwei** and Ley, Justin and Butts, Carter T and Markopoulou, Athina, "[Privacy by projection: Federated population density estimation by projecting on random features](https://petsymposium.org/popets/2023/popets-2023-0019.pdf).", in Proceedings of Privacy Enhancing Technologies (PoPETs), 2023(1), Lausanne, Switzerland, July 2023.

**Yang, Mengwei** and Song, Linqi and Xu, Jie and Li, Congduan and Tan, Guozhen, "[The Tradeoff Between Privacy and Accuracy in Anomaly Detection Using Federated XGBoost](https://arxiv.org/pdf/1907.07157.pdf)", accepted and to appear in IJCAI Workshop: 1st International Workshop on Federated Machine Learning for User Privacy and Data Confidentiality (IJCAI-FL 2019).

(* means equal contributions) -->

<!-- Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->


Experience
======

**Work Experience**
---------------------

* **Syntiant Corp.** — Engineering Intern (2022.7 – 2022.9)
  * Developed a confidence-aware, multi-teacher knowledge distillation framework for keyword spotting tasks, leveraging the student-teacher architecture.
  * Used pre-trained transformer models to enhance student model performance effectively.
  * Location: Irvine, California
  
* **Ericsson Inc.** — Data Science Intern (2020.6 – 2021.1)
  * Built a secure federated XGBoost framework with an innovative secure quantile sketch and practical secure aggregation.
  * Implemented pairwise masking of model parameters to protect against gradient leakage attacks during aggregation, strengthening client data privacy.
  * Location: Santa Clara, California

* **UC Irvine EECS Department** — Teaching Assistant (Winter and Spring 2024; Winter and Spring 2025)
  * Taught the lab sessions of EECS 31L: Introduction to Digital Logic Lab, guiding students through Verilog module design and debugging.
  * Location: Irvine, California

**Research Experience**
---------------------

* **ReTalk Agent: Multilingual Video Dubbing**, 2025.8 – 2025.10.
  * Developed an AI agent pipeline that transforms input videos into multilingual versions by leveraging LLM-based language processing while preserving the speaker’s unique voice identity.
  * Implemented lip-synchronization and voice cloning techniques to ensure natural alignment of facial movements with translated speech, producing high-quality, culturally adaptive video outputs.

* **LLM-Powered Voice Assistant with Voice Cloning**, 2025.6 – 2025.8.
  * Designed and implemented an interactive voice assistant leveraging large language models (LLMs) as the core reasoning engine, enabling natural, context-aware conversations with users.
  * Integrated voice cloning technology to generate a personalized synthetic voice, allowing seamless spoken interaction and enhancing user engagement in real-time dialogue.

* **Valuing Solo and Synergy in Federated Learning**, 2024.10 – 2025.7.
  * Proposed DuoShapley, an efficient Shapley value approximation that adaptively balances individual (Solo) and collaborative (Leave-One-Out) user contributions to improve valuation efficiency across heterogeneous federated learning settings.
  * Demonstrated that DuoShapley achieves over 200× speedup and higher robustness with noisy users, enabling scalable and reliable client selection for large-scale federated learning.

* **Maverick-Aware Shapley Valuation for Client Selection in FL**, 2023.10 – 2024.9.
  * Designed a Maverick-aware Shapley valuation framework to quantify client contributions under data heterogeneity, addressing undervaluation of clients with rare or underrepresented classes.
  * Developed FedMS, a Shapley-guided client selection mechanism that adaptively prioritizes high-value clients, improving global performance and robustness against adversaries and free-riders.

* **PriPrune: Quantifying and Preserving Privacy in Pruned FL**, 2022.11 - 2023.8.
  * Conducted research on privacy guarantees for model pruning in FL, deriving information-theoretic upper bounds on information leakage in pruned models.
  * Developed PriPrune – a privacy-aware pruning algorithm with personalized, per-client defense masks and adaptive pruning rates, balancing privacy and model performance.

* **Information Leakage in Personalized Federated Learning**, 2022.4 – 2022.6.
  * Executed the gradient leakage attack (DLG) in personalized FL, demonstrating how personalization levels impact vulnerability.
  * Proposed PerFed-LDP, a per-example differential privacy method for personalized FL, analyzing privacy-utility tradeoff under DP settings.

* **Privacy by Projection: Federated Population Density Estimation**, 2021.12 – 2022.7.
  * Designed a federated kernel density estimation (KDE) framework to estimate population density while ensuring data remains local.
  * Developed a federated Random Fourier Feature (RFF) KDE approach projecting user info onto spatially delocalized basis functions, enhancing privacy without hurting accuracy.

* **Location Leakage in Federated Signal Maps**, 2021.11 – 2022.4.
  * Executed gradient leakage attacks on federated signal map prediction, reconstructing average locations from private spatio-temporal datasets.
  * Proposed batch selection defenses to obfuscate true location, balancing utility in mapping with privacy protection.

* **SaferQ: Obfuscating Search Queries via Generative Adversarial Privacy**, 2020.3 – 2020.5.
  * Developed SaferQ, extending the GAP framework for sequence generation to obfuscate search queries while balancing privacy and utility.

* **Secure Federated XGBoost Framework**, 2018.9 – 2019.8.
  * Designed a secure federated XGBoost framework incorporating anonymized data aggregation to balance privacy and performance.


Publications
======
(* denotes equal contributions)

**Yang, Mengwei**, Buyukates, Baturalp, and Shen, Yanning, and Markopoulou, Athina, “Valuing Solo and Synergy in Federated Learning“, Under submission.

**Yang, Mengwei**, Buyukates, Baturalp, and Markopoulou, Athina, “Rewarding the Rare: Maverick-Aware Shapley Valuation in Federated Learning“, Under submission.

Chu, Tianyue\*, **Yang, Mengwei**\*, Laoutaris, Nikolaos, and Markopoulou, Athina, “[PriPrune: Quantifying and Preserving Privacy in Pruned Federated Learning](https://doi.org/10.1145/3702241)”, accepted to Transactions on Modeling and Performance Evaluation of Computing Systems (ToMPECS), October 2024.

**Yang, Mengwei**, Jarin, Ismat, Buyukates, Baturalp, Avestimehr, Salman, Markopoulou, Athina, “[Maverick-Aware Shapley Valuation for Client Selection in Federated Learning](https://arxiv.org/pdf/2405.12590)”, poster in ISIT workshop on “[Informational Theoretic methods for Trustworthy ML” (IT-TML)](https://sites.google.com/view/it-tml2024/schedule?authuser=0), July 7th 2024, Athens, Greece.


Chu, Tianyue, **Yang, Mengwei**, Laoutaris, Nikolaos, and Markopoulou, Athina, “Information-Theoretical Bounds on Privacy Leakage in Pruned Federated Learning”, poster and presentation, ISIT workshop on “[Informational Theoretic methods for Trustworthy ML” (IT-TML)](https://sites.google.com/view/it-tml2024/schedule?authuser=0), July 7th 2024, Athens, Greece

Bakopoulou, Evita\*, **Yang, Mengwei**\*, and Zhang, Jiang and Psounis, Konstantinos and Markopoulou, Athina, "[Location leakage in federated signal maps](https://www.computer.org/csdl/journal/tm/2024/06/10315165/1S2UkRgrKMw).", in IEEE Transactions on Mobile Computing, vol. 23, no. 06, pp. 6936-6953, June 2024.

Zong, Zixiao and **Yang, Mengwei** and Ley, Justin and Butts, Carter T and Markopoulou, Athina, "[Privacy by projection: Federated population density estimation by projecting on random features](https://petsymposium.org/popets/2023/popets-2023-0019.pdf).", in Proceedings on Privacy Enhancing Technologies (PoPETs), 2023(1), Lausanne, Switzerland, July 2023.

**Yang, Mengwei** and Liu, Shuqi, Xu, Jie, Tan, Guozhen, Li, Congduan, and Song, Linqi. "[Achieving privacy-preserving cross-silo anomaly detection using federated XGBoost](https://doi.org/10.1016/j.jfranklin.2023.04.002)." Journal of the Franklin Institute 360, no. 9 (2023): 6194-6210.

**Yang, Mengwei** and Song, Linqi and Xu, Jie and Li, Congduan and Tan, Guozhen, "[The Tradeoff Between Privacy and Accuracy in Anomaly Detection Using Federated XGBoost](https://arxiv.org/pdf/1907.07157.pdf)", accepted and to appear in IJCAI Workshop: [International Workshop on Federated Machine Learning for User Privacy and Data Confidentiality (IJCAI-FL 2019)](https://federated-learning.org/fl-ijcai-2019/).

