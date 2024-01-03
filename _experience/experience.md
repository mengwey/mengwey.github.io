---
# title: "Paper Title Number 3"
collection: experience
permalink: /experience/experience
# excerpt: "" 
# date: 2015-10-01
# venue: 'Journal 1'
# paperurl: 'http://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---


**Work Experience**
---------------------

* 07/2022 - 09/2022: Engineering Intern
  * Syntiant Corp.
  * Research on keyword spotting with student-teacher framework.
  
* 06/2020 - 01/2021: Data Science Internship
  * Ericsson Inc.
  * Research on secure federated learning with XGBoost.

**Research Experience**
---------------------

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

