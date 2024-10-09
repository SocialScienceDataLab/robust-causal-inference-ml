# Robust Causal Inference using Double/Debiased Machine Learning: A Guide for Empirical Research

Achim Ahrens
<achim.ahrens@gess.ethz.ch>

*Version: MZES Social Science Data Lab, 2024-09-18*

## Abstract

Motivated by their robustness to partially unknown functional forms, supervised machine learning estimators are increasingly leveraged for causal inference. One method that has received much attention is double/debiased machine learning (DML), which allows leveraging generic supervised machine learners for the estimation of common (causal) parameters. In this paper, we review DML and provide practical guidance to empirical researchers. We highlight three points: First, DML allows researchers to focus their attention on defining credible identifying assumptions while weakening assumptions of convenience such as linearity. Second, DML is versatile in that it can accommodate high-dimensional sets of variables (e.g. arising from text data) but also provides a cheap and sensible robustness check when only a few controls or instruments are observed. Third, the use of poorly validated machine learners may yield misleading inferences. Considering a diverse set of nuisance function estimators (including parametric estimators) alleviates this problem. We use several applications to illustrate these main points and derive practically relevant recommendations for empirical researchers.

📝 [Slides](https://github.com/SocialScienceDataLab/robust-causal-inference-ml/blob/main/robust_causal_inference_ml_ahrens_2024.pdf)

## About the Instructor

Achim Ahrens is a Senior Researcher at the Public Policy Group, ETH Zurich, and the Immigration Policy Lab (ETH/Stanford). He holds an MSc in Economics from University of Edinburgh and a PhD in Economics from Heriot-Watt University. Achim has worked on empirical projects in a wide range of fields including housing economics, migration, and labor economics. Achim has a strong interest in the intersection of causal inference and machine learning, and in algorithmic fairness.
