# Sequential Sentence Classification in Medical Abstracts
Building Tribrid embedding model 

Overview:

Implemented a natural language processing (NLP) model inspired by the 2017 paper "PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts." The project aimed to address the challenge of efficiently navigating through the increasing number of Randomized Controlled Trial (RCT) papers with unstructured abstracts.

Problem Statement:

With the rising volume of RCT papers, those lacking structured abstracts can pose difficulties in comprehension, potentially slowing down researchers. The objective was to develop an NLP model capable of classifying abstract sentences into specific roles (e.g., objective, methods, results), facilitating quick literature skimming for researchers.

Solution:

Created a comprehensive NLP model, referred to as SkimLit, enabling the classification of abstract sentences based on their roles. This model allowed researchers to skim through literature quickly and delve deeper into specific sections when needed.

Key Contributions:

Downloaded and utilized the PubMed RCT200k dataset from GitHub.
Developed a robust preprocessing function to prepare data for modeling.
Conducted a series of modeling experiments, including baseline TF-IDF classifiers and deep models with various embeddings and positional features.
Implemented a multimodal model that considered multiple types of data inputs.
Replicated the model architecture outlined in the paper "Neural networks for joint sentence classification in medical paper abstracts" (https://arxiv.org/abs/1612.05251).
Outcome:
The project successfully demonstrated the potential of NLP models in classifying sequential sentences within medical abstracts, providing a valuable tool for researchers to efficiently navigate and comprehend large volumes of literature.


Model Architecture:

![model](https://github.com/charanj15076/NLP_tribrid_embed/assets/37012040/5f0ed2bf-65ae-4631-89c8-ad7dc2e4c4d5)


Different project results :

![model_results](https://github.com/charanj15076/NLP_tribrid_embed/assets/37012040/135c4529-2301-443d-aee0-d3e2040c0cbe)
