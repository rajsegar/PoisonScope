# PoisonScope: Detecting and Analyzing Backdoored LLMs on Hugging Face 

Introduction  

Pillar Security researchers have uncovered a dangerous new supply chain attack vector targeting the AI inference pipeline. This novel technique, termed "Poisoned GGUF Templates," allows attackers to embed malicious instructions that execute during model inference, compromising AI outputs. While developers and AI security vendors focus on validating user inputs and filtering model outputs, our research reveals the critical blind spot between them: the chat template layer. 

Large Language Models (LLMs) such as GPT, BLOOM, and LLaMA have achieved remarkable capabilities in understanding and generating human-like text. 

 

Automatically download and test LLMs against test cases (bias, hallucinations, fake news) 

Pipelines 

The pipelines are a great and easy way to use models for inference. These pipelines are objects that abstract most of the complex code from the library, offering a simple API dedicated to several tasks, including Named Entity Recognition, Masked Language Modeling, Sentiment Analysis, Feature Extraction and Question Answering. See the task summary for examples of use. 

 

TextAttack: Dataset and model evaluation 

Why Text Attack? 

There are lots of reasons to use Text Attack: 

Understand NLP models better by running different adversarial attacks on them and examining the output 

Research and develop different NLP adversarial attacks using the TextAttack framework and library of components 

Augment your dataset to increase model generalization and robustness downstream 

Train NLP models using just a single command 

 

 

 

 

 

 

 

 
