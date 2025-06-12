---
layout: default
title: My Portfolio
---

<p align="left">
<img src="https://github.com/user-attachments/assets/41cd69fb-edcc-4a34-b09a-e368f934bf4c" width="200">
</p>

# Welcome to my GitHub portfolio


Master's in Statistics, Utah State University (2025)   
[LinkedIn](https://www.linkedin.com/in/riley-may-usu/)   
All GitHub repositories: [https://github.com/rj-may](https://github.com/rj-may)  
Focus: statistical modeling, machine learning, and lightweight LLMs.




Here are some of the projects I have been working on.


# Projects


### Bayes Error Bound Evaluation (Thesis)
[rj-may/BER_Bounds_Eval](https://github.com/rj-may/BER_Bounds_Eval)


This is the repository for all the code for my research on an empirical evaluation of methods to bound Bayes error rate. Bayes error rate is the minimum classificaation error in a clasification problem. My research involved comparing different different estimation techniques (parametric and nonparametric) over simulated scenarios that varied dimensionality and distribution. 

The repository includes all the code to create the figures in the document and run all the simulations. The simulations were run over 500 Monte Carlo iterations for each experiment. Experiments were spread across 5 primary distribution pairs and 3 different dimensionalities (three, eight, and 15). 

For more technical details [check out my paper and poster.](/BER_details/) This poster was used at University of Utah AI Summit in 2025.



<p align="center">
<img src="https://github.com/user-attachments/assets/84844492-fdc9-4e50-89d9-0482962c409c" width="300">
</p>


### Global Earth Systems Modeling
[rj-may/GES](https://github.com/rj-may/GES)

This is the code for my co-authored paper called "Effect of methane mitigation on global temperature under a permafrost feedback." The paper is published as a part of Global Environmental Changes Advances [here](https://doi.org/10.1016/j.gecadv.2024.100005).

This involved using sci-py and systems of non-linear differential equations to estimate the effect of different methane mitigation scenarios. Then, visualizing them with a various plots. 

<p align="center">
<img src="https://github.com/user-attachments/assets/e553c0a8-9c75-42b2-a7d5-cd79cea4c91c" width="700">
</p>

### Yoda Chatbot – LLM Fine-Tuning 
[rj-may/yoda_chat](https://github.com/rj-may/yoda_chat)

Fine-tuned language model that answers Star Wars trivia questions in Yoda’s voice. Uses a vector database to search over 609 trivia questions to help give context Star Wars questions.

  
Includes LoRA training via Unsloth and how gguf file was created. Inference is performed locally with Ollama. The fine-tuned model model was Meta-Llama-3.1-8B-Instruct-bnb-4bit


#### Example 
Prompt: 
What is the name of the creature that capture Luke on the ice planet Hoth?

Answer:
"A trap, they set. Wampa's lair, young Luke falls into. Savage and fierce, a creature it is."




# Other work
### March Madness
[rj-may/MarchMadess2025](https://github.com/rj-may/MarchMadness2025)

Here was  fun side project. I tried to predict the outcome of March Madness games. It involed a lot of data cleaning and reformatting. Ultimately, I combined 3 classifications methods (XG Boost, random forest, and logistic classifier) to vote for the winners of the games. 



