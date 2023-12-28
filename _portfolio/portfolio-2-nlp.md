---
title: "News Classification with ChatGPT"
excerpt: "News Classification with ChatGPT leveraging prompt engineering"
collection: portfolio
tags:
  - nlp
  - gpt
  - llm
  - prompt-engineering
---

![chatgpt](/images/chatgpt.jpeg){: .align-center width="300px"}
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/vikrampande7/prompt-engineering){:target="_blank"}

- News classification is of importance in the field of information retrieval and media analysis.
- Dataset: AG News (AG’s News Corpus): : It contains 4 largest classes from the original corpus. Each class contains 30,000 training samples and 1900 testing samples and the total number of training samples is 120,000 and testing samples is 7,600. The classes are divided into categories: world, sports, business, and science/technology.
- Prompting Strategy
1.	Baseline:
Large Language Models (LLMs) are typically trained on extensive datasets, allowing them to work effectively with direct inputs and outputs. When prompted directly, an LLM can often generate a reasonably accurate response in a single attempt. This approach is referred to as "zero-shot prompting" and is considered a baseline technique in prompt engineering. In simple terms, the model is presented with a straightforward question without any surrounding context or background information, and it is expected to provide a corresponding answer. The extended version would be “few-shot-prompting”.

2.	Few-shot prompting:
In few-shot prompting, only a small number of examples/shots are also provided in prompt. This helps model in decision making for new data and useful when annotated data is limited to guide its understanding of a particular task or generate desired responses.

3.	Chain-of-thought (CoT):
Chain-of-thought (CoT) prompting enables complex reasoning capabilities through intermediate reasoning steps. To maintain a coherent flow of conversation. Instead of asking isolated or individual questions, this approach involves generating prompts that build upon the previous responses or questions, forming a logical and connected chain of thought in the conversation. [6]

4.	Zero Shot Chain-of-thought (CoT):
A novel concept, the zero-shot CoT (Kojima et al. 2022)[7], introduces a distinct approach by incorporating the phrase "Let's think step by step" into the original prompt. This strategy aims to enhance model performance. This approach empowers the model with the capacity to engage in systematic and logical reasoning. By introducing the directive to "think step by step," it encourages the model to break down complex problems into manageable components, facilitating more coherent and reasoned responses.
