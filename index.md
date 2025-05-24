---
layout: default
title: My Portfolio
---

# Welcome to My Portfolio



Master's in Statistics, Utah State University (2025)  
[LinkedIn](https://www.linkedin.com/in/riley-may-usu/)  
Focus: Statistical modeling, ML evaluation, and lightweight LLMs



Here are some of the projects I have been working on.


# Projects


### Bayes Error Bound Evaluation (Thesis)
[rj-may/BER_Bounds_Eval](https://github.com/rj-may/BER_Bounds_Eval)

This is the repository for all the code for my research on an empirical evaluation of methods to bound Bayes error rate. Bayes error rate is the minimum classificaation error in a clasification problem. My research involved comparing different different estimation techniques (parametric and nonparametric) over simulated scenarios that varied dimensionality and distribution. 

The repository includes all the code to create the figures in the document and run all the simulations. The simulations were run over 500 Monte Carlo iterations for each experiment. Experiments were spread across 5 primary distribution pairs and 3 different dimensionalities (three, eight, and 15). 


### Global Earth Systems Modeling
[rj-may/GES](https://github.com/rj-may/GES)

This is the code for my co-authored paper called "Effect of methane mitigation on global temperature under a permafrost feedback." The paper is published as a part of Global Environmental Changes Advances [here](https://doi.org/10.1016/j.gecadv.2024.100005).

This involved using sci-py and systems of non-linear differential equations to estimate the effect of different methane mitigation scenarios. Then, visualizing them with a various plots. 




### Yoda Chatbot – LLM Fine-Tuning 
[rj-may/yoda_chat](https://github.com/rj-may/yoda_chat)

Fine-tuned language model that answers Star Wars trivia questions in Yoda’s voice. Uses a vector database to search over trivia questions to help give context Star Wars questions.
  
Includes LoRA training via Unsloth and how gguf file was created. Inference is performed locally with Ollama. 


# Other work
### March Maddness
[MarchMaddness2025](https://github.com/rj-may/MarchMadness2025)

Here was  fun side project. I tried to predict the outcome of March Madness games. It involed a lot of data cleaning and reformatting. Ultimately, I combined 3 classifications methods (XG Boost, random forest, and logistic classifier) to vote for the winners of the games. 
