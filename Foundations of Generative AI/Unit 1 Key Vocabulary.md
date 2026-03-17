# Unit 1 Key Vocabulary

## Core AI Concepts
1. **Generative AI**: A type of artificial intelligence that can create entirely new content, such as text, images, and sounds. Unlike older AI that just analyzes existing data, it learns from vast amounts of information to produce new, realistic outputs.
2. **Model**: In the context of AI, a model is the core program or algorithm that has been "trained" on data to perform a specific task. For example, GPT-4 is a specific model created by OpenAI. Think of it as the digital brain that has learned a skill.
3. **Parameters**: These are the internal variables that a model learns during its training. The number of parameters (often measured in billions) is a rough indicator of a model's size and complexity. More parameters generally mean the model can learn more nuanced patterns from the data.
4. **Hallucination** This is a term used to describe when an AI model confidently generates false or nonsensical information. Because LLMs are designed to predict the next word, not to know facts, they can sometimes invent details that sound plausible but are not true. This is a key limitation to be aware of.

## How LLMs Work: From Prompt to Response
1. **Large Language Model (LLM)**: The engine behind most text-based generative AI. An LLM is a complex system trained to predict the most likely next word (or "token") in a sentence based on the words that came before it. It doesn't "understand" language like a human; instead, it's an expert at recognizing and recreating complex patterns from text data. Think of it as a very advanced autocomplete.
2. **Prompt**: The instruction, question, or text you give to an LLM to get it started. The prompt provides the context the model needs to generate a relevant response.
3. **Tokenization**: The first step in processing a prompt. The text is broken down into smaller pieces called tokens. A token can be a full word, a part of a word (like pre- or -ing), or a piece of punctuation.
4. **Embedding**: After tokenization, each token is converted into a numerical format called an "embedding vector." This allows the model to work with words mathematically. Words with similar meanings, like "car" and "automobile," will have similar numerical representations.
5. **Transformer Architecture**: The modern neural network design that powers most LLMs. Its key innovation is the self-attention mechanism, which lets the model look at all the words in a prompt at once. This helps it understand the context and relationships between words, even if they are far apart in a sentence, making it very effective for generating coherent text.
6. **Attention Mechanism**: The part of the Transformer architecture that allows the model to weigh the importance of different tokens when generating a response. For example, in the sentence "The gray cat sat on the mat," the attention mechanism helps the model understand that "cat" is the key subject, which is crucial for predicting what comes next.
7. **Probability Distribution**: After analyzing the prompt, the LLM creates a ranked list of all the possible words in its vocabulary, each with a score indicating how likely it is to be the correct next word.
8. **Token Selection (Sampling)**: The final step, where the model picks the next token from the probability list. There are several ways to do this:
9. **Greedy Sampling**: The simplest method, which always picks the token with the highest probability score. This is safe but can be repetitive
10. **Temperature Sampling**: A method that adds a bit of controlled randomness. A higher "temperature" encourages more creative and unexpected word choices, while a lower temperature keeps the output focused and predictable
11. **Top-K / Top-P Sampling**: These techniques narrow the choices to a small group of the most likely tokens before the final selection is made, balancing creativity and coherence.

## Advanced Concepts: A Look Ahead
1. **Prompt Engineering**: The skill of designing and refining prompts to get the most accurate, relevant, and useful responses from a generative AI model.
2. **AI Orchestration**: The process of combining multiple AI models and tools to accomplish a complex task that a single model couldn't handle on its own.
3. **Retrieval Augmented Generation (RAG)**: A technique that allows an LLM to access and use external, up-to-date information (like company documents or recent news articles) to answer questions more accurately. This helps reduce hallucinations.
4. **Function Calling**: An advanced capability that allows an LLM to use external tools or APIs. For example, a model could use a function to get the current weather, book a reservation, or access a proprietary database.
5. **Agentic AI**: An AI system that can autonomously plan and execute a series of tasks to achieve a high-level goal. Instead of just responding to a single prompt, an AI agent can reason, use tools, and adapt its approach to get a job done.
