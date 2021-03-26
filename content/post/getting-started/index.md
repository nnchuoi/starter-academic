---
title: Safety and Security of Embedded Systems : from Modeling to Verification and Validation
subtitle: Habilitation à diriger des recherches (HDR)

# Summary for listings and search engines
summary: Embedded Systems, Model-Based Systems Engineering (MBSE), Model-Based Safety Assessment (MBSA), Safety, Security, Model Checking, Attack Modeling

# Link this post with a project
projects: []

# Date published
date: "2020-12-13T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin
- 吳恩達

tags:
- Academic
- 开源

categories:
- Demo
- 教程
---

## Abstract

This HDR document summarizes my research activities on the safety and security of complex embedded systems, with a model-based approach. The safety and security properties are formally modeled and verified, early from the design process of the system, which helps to reduce late errors and development time. The main contributions presented here are as follows.

First, we proposed to integrate safety analysis into the system engineering process to ensure consistency between the design models and the safety assessment. Model-to-model transformation algorithms are used to automatically generate, from system models, the safety artifacts that are Failure Modes and Effects Analysis (FMEA) and Dynamic Fault Trees (DFT). These results will allow designers to validate or not the architecture of a system and, if necessary, to add, for example, redundant components in order to guarantee the reliability of critical subsystems. For this, a Safety Profile  and a Redundancy Profile have been integrated directly into the static model of the system under study. In order to complete these structural analyses, the dynamic behavior of the system with nominal and error states, as well as the propagation of these errors, all modeled in a semi-formal language, i.e., SysML, is transformed into a formal language, i.e., NuSMV, to verify if the safety requirements are met by the system.

Our second contribution concerns the modeling of attacks in cyber-physical systems, where connectivity is increasingly present. Extended attack trees are modeled from atomic attacks, using temporal logic operators to describe the propagation of threats. An Extended Attack Tree Profile and a Connectivity Profile are proposed to model the attack and the system respectively. The models are then transformed into NuSMV code, and a model checker is used to check if the system is secure against attacks represented in temporal specifications.

The various analyses in this research suggest some improvements and open up new perspectives for future work on the convergence of safety and cybersecurity in embedded systems. My goal in the coming years is to approach the two analyses directly in a single high-level formal language like AltaRica. The scientific barrier to be lifted will be to find how to adapt a language initially dedicated to safety, which deals with random and unintentional events using statistical methods, to security, with intentional threats for which relevant statistics cannot generally be defined. In parallel, to exploit formal methods at the software level and provide other practical tools to address the general issue of correctness in systems, my second perspective will be to study the combination between static binary code analysis and machine learning for the detection of vulnerability in embedded systems.
