---
title: (10/24) First Seminar by Prof. Jonathan Frankle
date: 2022-10-16 19:15:00 +0900
categories: [Seminar, Gauss Jr. Colloquium]
tags: [Jonathan Frankle, Seminar, MosaicML, Lottery Ticket Hypothesis, Gauss Jr. Colloquium]
pin: true
---

Hello! 

I'm glad to announce to you that our first seminar of **"Gauss Jr. Colloquium"** seminar series is reserved.
Prof. Jonathan Frankle has accepted our proposal.
He will give us a talk about making large-scale neural network training faster, 
which is related to his famous work, [The Lottery Ticket Hypothesis](https://openreview.net/pdf?id=rJl-b3RcF7), and his recent work in [MosaicML](https://www.mosaicml.com/).

The seminar title is **"Faster Neural Network Training, Algorithmically"**.
It will have a 45 minutes talk + up to 45 minutes of Q&A and discussion over Zoom.
More details about seminar are below.

Thank you!

# Faster Neural Network Training, Algorithmically

## Date & Time
#### 2022-10-24 09:30 AM - 11:30 AM

## Zoom Link
#### TBA

## Abstract 
Training modern neural networks is time-consuming, expensive, and energy-intensive. As the cost of training state-of-the-art networks doubles in size every few months, it is difficult for researchers and businesses without immense budgets to keep up. In this talk, I will describe one approach for managing this challenge: changing the training algorithm itself. While many companies and researchers are focused on building hardware and systems to allow existing algorithms to run faster in a mathematically equivalent fashion, there is nothing sacred about this math. To the contrary, training neural networks is inherently approximate, relying on noisy data, convex optimizers in nonconvex regimes, and ad hoc tricks and hacks that seem to work well in practice for reasons that elude us. I will argue that we should exploit the approximate nature of neural network training to change the math of training in order to improve efficiency. This viewpoint, which I studied during my PhD work on neural network sparsity and the Lottery Ticket Hypothesis, is now being applied at scale at MosaicML.
I will discuss how we have put this approach into practice at MosaicML, including the empirical approach to research that we take, the dozens of algorithmic changes we have studied (which are freely available open source), the science behind how these changes interact with each other (the composition problem), and how we evaluate whether these changes have been effective. I will also detail several surprises we have encountered and lessons we have learned along the way. In the year since we began this work in earnest, we have reduced the training times of standard computer vision benchmarks (ResNet-50 on ImageNet, DeepLab-v3 on ADE-20K) by 5-7x and standard language models (BERT and GPT on C4) by 2-4x, and we believe we are just scratching the surface. I will close by describing several exciting research questions that have emerged in the course of this research.

## Bio
Jonathan Frankle is Chief Scientist at MosaicML, where he leads the company's research team toward the goal of developing more efficient algorithms for training neural networks. In his PhD at MIT, he empirically studied deep learning with Prof. Michael Carbin, specifically the properties of sparse networks that allow them to train effectively (his "Lottery Ticket Hypothesis"). He will be joining the faculty of the School of Engineering and Applied Sciences at Harvard in the fall of 2023 as an assistant professor. He earned his BSE and MSE in computer science at Princeton and has previously spent time at Google Brain, Facebook AI Research, Microsoft, and Georgetown Law.
