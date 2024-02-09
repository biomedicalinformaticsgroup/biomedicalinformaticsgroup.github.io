---
layout: post
title:  "An Integrative Network Approach for Longitudinal Stratification in Parkinson's Disease"
date:   2024-02-09 09:00:00 +0000
categories: research
---

<img style="margin-left: 2rem" align="right" src="assets/baseline_comparison.png" width = "500px" >

#### *Barry Ryan , Riccardo Marioni and T. Ian Simpson*

<div style="text-align: justify"> Parkinson's Disease (PD) is a neurodegenerative disorder characterized by motor symptoms resulting from the loss of dopamine-producing neurons in the brain. Currently, there is no cure for the disease which is in part due to the heterogeneity in patient symptoms, trajectories and manifestations. There is a known genetic component of PD and genomic datasets have helped to uncover some aspects of the disease. Understanding the longitudinal variability of PD is essential as it has been theorised that there are different triggers and underlying disease mechanisms at different points during disease progression. In this paper, we perform longitudinal and cross-sectional experiments to identify which data modalities or combinations of modalities are informative at different time points. We use clinical, genomic, and proteomic data from the Parkinson's Progressive Markers Initiative (PPMI). We validate the importance of flexible data integration by highlighting the varying combinations of data modalities for optimal stratification at different disease stages in idiopathic PD. We show there is a shared signal in the DNAm signatures of participants with a mutation in a causal gene of PD and participants with idiopathic PD. We also show that integration of SNP and DNAm data modalities has potential for use as an early diagnostic tool for individuals with a genetic cause of PD.

<br>

MOGDx is a flexible tool to integrate multiple omic measures and perform classification tasks. This approach uses a network taxonomy to combine patient similarity matrices into a single network and perform node classification using a Graph Convolutional Network. It is a preferred tool to perform analysis on the PPMI dataset due to its flexibility. It can integrate any number of modalities, whilst simultaneously allowing for the retention of the maximum number of patients possible, in contrast to other existing methodologies. See our preprint on MOGDx for more information [here](https://www.medrxiv.org/content/10.1101/2023.07.09.23292410v1)

<br>

In this paper, we look at two disease subgroups: those who have a mutation in a casaul gene for PD, labelled *Genetic* and those who have no known genetic cause or sporadic onset, labelled *Idiopathic*. Using MOGDx, we have tested all available combinations of genomic data from the PPMI dataset. We highlight the performance of the best performing modalities in the figure on the right by comparing it to the worst performing modality and a baseline clinical assessment modality called the MDS-UPDRS. We obtain strongest performance when classifying in the subgroup who have a mutation in a casaul gene. We found that no single modality or combination of modality achieved optimal performance at every time point in the idiopathic subgroup, highlighting the importance of flexible modality integration. We also found that worst performance is achieved when the two subgroups are considered jointly. DNAm was predicitve for all experiments at almost every timepoint, indicating the presence of an epigenetic modification between individuals with PD and those without, regardless of subgroup. 


<img style="margin-left: 1rem" align="left" src="assets/year3_flow.png" width = "1000px" > 

<div>&nbsp

Finally, we found that a combination of SNP and DNAm achieved excellent stratification accuracy in the genetic subgroup at all time points. Optimal performance was observed by a model trained at year 3, the latest time point available in the PPMI dataset. Our results show that this combination of modalities could be used as an early diagnostic tool and such a tool should be trained using PD patients who have progressed to a later disease stage. 

</div>



For more information find the preprint to our paper online [here](https://www.medrxiv.org/content/10.1101/2024.01.25.24301595v2)

