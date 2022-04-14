---
layout: post
categories:
  - talk
title:  "Functional Synthesis: An Ideal Meeting Ground for Formal Methods and Machine Learning"
author: "Priyanka Golia"
fixture: "14-04-2022"
coordinates: "KD103, 5 PM IST, 15th Sept 2021"
link: 
tags: 
---
## Abstract

Don't we all dream of the perfect assistant whom we can just tell what to do and the assistant can figure out how to accomplish the tasks? Formally, given a specification F(X,Y) over the set of input variables X and output variables Y, we want the assistant, aka functional synthesis engine, to design a function G such that (X,Y=G(X)) satisfies F. Functional synthesis has been studied for over 150 years, dating back Boole in 1850's and yet scalability remains a core challenge. Motivated by progress in machine learning, we design a new algorithmic framework Manthan, which views functional synthesis as a classification problem, relying on advances in constrained sampling for data generation, and advances in automated reasoning for a novel proof-guided refinement and provable verification.
On an extensive and rigorous evaluation over 609 benchmarks, we demonstrate that Manthan significantly improves upon the current state of the art, solving 509 benchmarks in comparison to 280, which is the most solved by a state of the art technique. The significant performance improvements, along with our detailed analysis, highlights several interesting avenues of future work at the intersection of machine learning, constrained sampling, and automated reasoning.

The talk is based on following two papers:
1. [CAV-2020](https://priyanka-golia.github.io/publication/cav20-manthan/cav20-manthan.pdf)
2. [ICCAD 2021](https://arxiv.org/pdf/2108.05717.pdf).