# OpenAI
OpenAI is an AI research and deployment company, known for developing advanced AI models like ChatGPT and DALL-E. Their mission is to develop artificial general intelligence (AGI).

## ChatGPT
ChatGPT originates from two key components: "Chat" and "GPT."
ChatGPT is a LLM (large language models)

1. **Chat:** This term refers to the conversational aspect of the AI. It signifies the primary function, which is to engage in dialogue with users, answering questions, providing information, and simulating a conversational partner in a wide range of topics.

2. **GPT:** This stands for "Generative Pretrained Transformer." Let's break down this term:
   - **Generative:** This indicates ability to generate text, create responses, complete text prompts, and even generate creative content like stories or poems.
   - **Pretrained:** This means it has been trained on a large dataset before being deployed. Training involved processing a vast amount of text data to understand and mimic human language patterns.
   - **Transformer:** This refers to the type of neural network architecture used in the design. The Transformer architecture is known for its efficiency in handling sequential data (like text) and its ability to manage long-range dependencies in language. It was introduced in a 2017 paper titled "Attention Is All You Need" by researchers at Google.

### Usage
ChatGPT can be used through frotnend chat interface or the OpenAI APIs. You can even build your own ChatGPT based on these apis.

## Models
### 3.5
- 175B parameters
- 96 Layers

### Moderation API
Both the input and the output are sent to a Moderation API that censor any considered non-legal/ethical content.

### Token and context limit
"token" refers to the smallest unit of text processed by the model, which could be a word or part of a word.
The "context limit," on the other hand, is the maximum number of tokens the model can consider from prior parts of a chat conversation, which is also limited and at some point will be taken out of the "memory" of the model