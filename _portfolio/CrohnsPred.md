---
title: "CrohnsPred"
excerpt: "A Deep Neural Network for Genetic Risk Prediction of Crohn's Disease.<br/><img src='/images/CP_cover_image.png'>"
collection: portfolio
---

Crohn’s Disease (CD) is a chronic illness that has seen a dramatic increase in global prevalence and incidence in the last two decades (Roda et al., 2020). 
The development of Crohn’s has been partially attributed, amongst other factors, to certain mutations in one’s genes (Aleksejs Sazonovs et al., 2021). 
Most current techniques in Bioinformatics focus on investigating how relevant single genetic mutations are in the development of CD and can fall short in considering important interactions between sparse mutations, which are believed to greatly influence the development of complex illnesses like Crohn’s (Behravan et al., 2018).

![alt text](/images/DTC_to_CD.png)

This project proposes a Deep Neural Network, *CrohnsPred*, for the prediction of an individual’s Genetic Risk of Crohn’s Disease based on sample-level genotype mutation data. This approach leverages the ability of DNNs to identify patterns and discover links amongst great amounts of data, which have been shown to outperform various statistical models currently used for the polygenic score calculation for other polygenic diseases (Zhou et al., 2023). To preserve data anonymity and reduce ethical concerns, the genetic and phenotypic data used for the Network training and testing was created as synthetic data through the HAPNEST software (Wharrie et al., 2022).

![alt text](/images/DNN.png)

The prediction tool is integrated into a publicly accessible web-based dashboard, which allows the users to get a personalized prediction
and access their score through eye-catching graphics and visualizations for a facile understanding of the results. 

Network Implemetation and Data Analysis available [here](https://github.com/belfioreasia/CrohnsPred). \\
Webapp interface available [here](https://github.com/belfioreasia/WebApp).