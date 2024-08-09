---
title: "Methods for analysis of spatial peptidergic communication networks"
collection: research
type: "Summer Internship"
permalink: /research/CCIgraphs
venue: "Allen Institute"
date: 2024-08-10
location: "Seattle, WA"
---

#### Introduction

Communication in the brain occurs in 2 main ways: wired communication and wireless communication.

In the fisrt case, neurons communicate across a synapse with electrical and chemical signals. 

In the latter case, neruons communicate via the diffusion of small molecules (peptides). 

Peptides released by one neuron can bind to G-protein coupled receptors (GPCRs) on other neurons and modulate their activity. 

In this study, we focus on this latter mode of communication.

Many such cognate neuropeptide-GPCR pairs have been identified in the literature. These constitute multiple molecularly distinct communication networks between neurons. 

Single cell transcriptomic data suggests that a vast majority of cortical neurons participate in such communication in a cell-type dependent manner (Smith et al. 2019).

We study cell to cell communication with spatial transcriptomic data.

Spatial transcriptomic experiments measure gene expression while preserving context within the tissue. We consider a recent whole mouse brain dataset obtained with an in-situ hybridization-based technique called MERFISH (Yao et al. 2023) and develop graph-based methods to study the organization of putative peptidergic communicatio nnetworks.

We explore regimes in which neighborhood information is helpful for cell type classification with graph neural networks and adapt Node2Vec (Grover et al. 2016) to obtain multilayer graph embeddings. We speculate that cell clusters obtained in this way correspond to spatial domains relevant from a functional point of view.




