![oreilly-logo](images/oreilly.png)

# Optimizing LLMs with Fine-Tuning and Prompt Engineering


This repository contains code for the [O'Reilly Live Online Training for Optimizing LLMs with Fine-Tuning and Prompt Engineering](https://www.oreilly.com/live-events/optimizing-llms-with-fine-tuning-and-prompt-engineering/0642572011351)

This advanced course is designed for machine learning engineers and software developers looking to elevate the performance and precision of large language models (LLMs). This course focuses on two critical aspects of LLM optimization: fine-tuning models on specific datasets to tailor their capabilities and mastering the craft of prompt engineering to generate accurate and contextually relevant outputs.

Over the course of this training, you will explore the intricacies of fine-tuning LLMs like GPT, learning how to adapt pre-trained models to specific tasks and use cases. Additionally, you will delve into the nuances of prompt engineering, discovering how to design and refine prompts that effectively guide LLM behavior. By the end of the course, you will have a deep understanding of how to maximize the potential of LLMs, making them more responsive and valuable in a variety of applications. This course is essential for anyone aiming to push the boundaries of what LLMs can achieve in real-world scenarios.

### Notebooks

#### Comparing Fine-tuned OpenAI + BERT

  - [`bert_app_review.ipynb`](notebooks/bert_app_review.ipynb): Fine-tuning a BERT model for app review classification.
  - [`openai_app_review_fine_tuning.ipynb`](notebooks/openai_app_review_fine_tuning.ipynb): Fine-tuning OpenAI models for app review classification.

#### Fine-tuning embeddings

- [Fine-tuning Embeddings For Rec Engines](https://colab.research.google.com/drive/1JfxyxdGCDjYeO52Bk1JzW4Af94xndTws?usp=sharing): Fine-tuning embedding engines using custom preference data

- [Fine-tuning Embeddings  with Synthetic Data](https://colab.research.google.com/drive/1FOr9hgMEcTa8UJJSuKjoHpohVb-Qz-FJ?usp=sharing) - Using GPT-4o to create synthetic queries for a corpus to increase the quality of open-source embedding models

#### SAWYER - Training a chat model with RLF

  - [`SAWYER_LLAMA_SFT.ipynb`](notebooks/SAWYER_LLAMA_SFT.ipynb): Fine-tuning the Llama-3 model to create the SAWYER bot.
  - [`SAWYER_Reward_Model.ipynb`](notebooks/SAWYER_Reward_Model.ipynb): Training a reward model from human preferences for the SAWYER bot.
  - [`SAWYER_RLF.ipynb`](notebooks/SAWYER_RLF.ipynb): Applying Reinforcement Learning from Human Feedback (RLHF) to align the SAWYER bot.
  - [`SAWYER_USE_SAWYER.ipynb`](notebooks/SAWYER_USE_SAWYER.ipynb): Using the SAWYER bot.

#### Distillation + Quantization

  - [`distillation_example_1.ipynb`](notebooks/distillation_example_1.ipynb): Exploring knowledge distillation techniques for transformer models.
  - [`distillation_example_2.ipynb`](notebooks/distillation_example_2.ipynb): Advanced distillation methods and applications.
  - [`llama_quantization.ipynb`](notebooks/llama_quantization.ipynb): Quantizing Llama models for efficient deployment.


## Instructor

![](images/square_headshot_small.jpg)

**Sinan Ozdemir** is the Founder and CTO of LoopGenius where he uses State of the art AI to help people create and run their businesses. Sinan is a former lecturer of Data Science at Johns Hopkins University and the author of multiple textbooks on data science and machine learning. Additionally, he is the founder of the recently acquired Kylie.ai, an enterprise-grade conversational AI platform with RPA capabilities. He holds a master’s degree in Pure Mathematics from Johns Hopkins University and is based in San Francisco, CA.

