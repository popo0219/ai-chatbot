# Chatbot for Users
## 1.Overview:
The main motto of ChatBot is to provide a powerful, versatile, and human-like conversational experience. As an AI language model developed by OpenAI, ChatGPT's primary goal is to understand and generate human-like text responses based on the input it receives. It aims to assist users in various tasks, answer questions, engage in meaningful conversations, and provide valuable information.
## 2. Motivation:
Building a ChatBot for customer service involves training the model with diverse customer queries, prioritizing real-time responses, ensuring scalability, personalization, and error handling. Integration with existing systems, testing, data privacy, and feedback mechanisms enhance the chatbot's performance, providing timely and accurate responses to improve customer satisfaction and reduce workload on support agents.
## 3. Success Metrics:
The success of the chatbot will be measured based on the following metrics:

- Customer engagement (e.g., click-through rate, time spent on the platform)
- Reduced response time
- Increased customer satisfaction (e.g., NPS score)
## 4. Requirements & Constraints:
Functional requirements:
- The chatbot should be able to understand and respond to customer queries in a natural language.
- The chatbot should be integrated with existing customer support platforms.
- The chatbot should provide quick and accurate responses to customer queries.
## Constraints:
- The cost of the chatbot should be minimal.
- The chatbot's latency should be below 5 seconds.

## 5. What's in-scope & out-of-scope?
### In-scope:
- Developing a chatbot that can interact with customers in a natural language and provide quick and accurate responses to their queries.
- Integrating the chatbot with existing customer support platforms.
### Out-of-scope:
Developing a custom customer support platform.
## 6. Methodology:
### Problem Statement:
The problem will be framed as a natural language processing (NLP) problem, where the goal is to develop a system that can understand and respond to customer queries in a natural language.

### Data:
The chatbot will be trained on a dataset of customer queries and responses. The input data needed during serving will be the customer's query.

The model will be trained on the HuggingFace Samsum dataset
