# ECE635 Project: Home Safety System Using LLM Agents


**Motivation**

We have both taken machine learning courses during our undergraduate studies and enjoyed learning about the field. We would like to take a further step into utilizing the skills we have acquired and further improving them, while also exploring a more specific machine learning application through LLM agents. We believe this specific project will help us expand our understanding and give us the opportunity to be creative in our problem-solving. As popular LLMs become increasingly popular and useful, such as ChatGPT and Gemini, understanding how to use and incorporate them into projects is an incredibly valuable skill to learn. LLMs could be especially useful in smart home scenarios, as it could take in different data types from multiple devices/sensors to make high-level decisions: a concept we’d like to demonstrate through this project.


**Design Goals**

- Implement a home safety system using LLM agents that recognizes different fire scenarios and makes consistent decisions about how to handle them.
- Have the LLM make high-level decisions about where to send real-time data to be processed/tested
- The LLM should be able to make decisions and output results in a realistic timeframe, as housefires are incredibly time-sensitive.

**Deliverables**

An LLM that can take in inputs from sensors and build a system for fire detection
The model should be able to use multiple types of data (ex: images, audio, smoke levels)
The system should be able to notify the user/house owner if indeed a fire is detected


**Software/Hardware Requirements**

The only hardware needed is a laptop/computer with a CUDA-enabled GPU, or at the very least, one that can access google colab. For software, the system will be run on Python using LLM libraries and multiple datasets for smoke detection, fire images, and any other fire detection methods


**Team Responsibilities**

Katie: Model setup and training, networking, writing paper

Jay: Gathering and preprocessing datasets, research, model testing, writing paper



**References**
LangChain Tutorial: https://www.deeplearning.ai/short-courses/functions-tools-agents-langchain/

HuggingGPT: https://arxiv.org/pdf/2303.17580 
