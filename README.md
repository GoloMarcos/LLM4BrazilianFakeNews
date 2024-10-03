# On the use of Large Language Models to Detect Brazilian Politics Fake News

- Marcos Gôlo (University of São Paulo) | marcosgolo@usp.br
- Adriel Mori (Federal University of Goiás) | adrielmori@discente.ufg.br
- William de Oliveira (Federal University of Goiás) | william.william@discente.ufg.br
- Jacson Barbosa (Federal University of Goiás) | jacson_rodrigues@ufg.br
- Valdemar Graciano-Neto (Federal University of Goiás) | valdemarneto@ufg.br
- Eliomar de Lima (Federal University of Goiás) | eliomar@ufg.br
- Ricardo Marcacini (Federal University of Goiás) | ricardo.marcacini@icmc.usp.br

# Citing:

If you use any part of this code in your research, please cite it using the following BibTex entry
```latex
@inproceedings{ref:Golo2024,
  title={On the use of Large Language Models to Detect Brazilian Politics Fake News},
  author={Gôlo, Marcos PS and Mori, Adriel LV and Oliveira, William G and Barbosa, Jacson R and Graciano-Neto, Valdemar V and de Lima, Eliomar A. and Marcacini, Ricardo M},
  booktitle={Anais do XXI Encontro Nacional de Inteligência Artificial e Computacional},
  pages={X--X},
  year={2024},
  organization={SBC}
}
```

# Abstract 
Machine learning methods are proposed to mitigate the spread of fake Brazilian news about politics so as not to harm society. Supervised algorithms are explored, requiring labeled news to train. However, labeling a high volume of news can be complex, onerous, time-consuming, error-prone, and costly. Hence, large language models (LLMs) have been used to detect fake news once LLMs are unsupervised methods that can play the role of classifiers. Most fake news detection studies explore the OpenAI LLMs (require payment) and lack an empirical evaluation with other LLMs. However, several open-source models obtain comparative and state-of-the-art (SOTA) results. We highlight that these models have yet to be explored in detecting fake Brazilian news about politics, which is crucial as it directly impacts society. In this sense, we propose a new dataset for detecting fake Brazilian news about politics and an empirical evaluation of open-source LLMs and OpenAI LLMs. In our results, the LLM from Google (Gemma) outperformed the other six LLMs, including GPT-4, proving to be the most promising model for detecting fake news about Brazilian politics.

#

#

#

# Requirements
 - python >= 3.12
 - pandas
 - ollama
 - scikit-learn
 - matplotlib
 - openai == 0.28
