---
layout: default
title: Key Results of Bayes Error Rate Research  
description:  Empirical Evaluation of Bayes Error Rate Bounds in Binary Classification
permalink: /BER_details/
---

To go back to [main page](/)

# Key results
The four experiments outlined here show how the different BER bounds were tested. All other dimensions in the experiments were sampled from equivalent distributions.  The following table summarizes the key results with the least and most amount of samples. 

<p align="center">
<img src="https://github.com/user-attachments/assets/78d4b5c4-ef18-4a1b-9232-7bdb6115005e" alt="four_cases_grid" width="600"/>
</p>

<p align="center">
 <img src="https://github.com/user-attachments/assets/eeec758b-7045-4f15-8b91-221681eec041" alt="Tablular Results" width="900"/>
 </p>

 Table: Validation and width results across different sample sizes and dimensions for four different experiments. Highlighted are
the narrowest bounds that have a validity greater than 0.5. These experiments are averaged over 500 Monte Carlo iterations.


This table demonstrates that as dimensionality increases, the bounds become unreliable. The only bounds that capture the BER in high dimensions are too wide to meaningfully indicate where the BER lies.  Another significant takewaway from these research is that althought the data from which the distributions were sampled from were from normal, the parametric Bhattacharyya bound with the normal assumption still is able to bound the BER.

## The poster

For the poster presented at the University of Utah AI summit, you can download it here [poster.pdf.](https://github.com/user-attachments/files/20787933/poster_U_AI_summit.-.updated.pdf)

<p align="center">
 <img src="https://github.com/user-attachments/assets/4295efb5-65cf-447f-a069-4efaf518d0ab" alt="Poster preview" width="400"/>
 </p>


## The paper

The paper pending approval is here [thesis.pdf](https://github.com/user-attachments/files/20680357/thesis_pending.pdf)
