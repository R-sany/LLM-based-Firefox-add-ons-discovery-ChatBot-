# Create an LLM-based Chat AI Firefox Add-ons Discovery Feature

## Project Description
The project aims to leverage the intuitive conversational appeal of chat AI to help Firefox users find the right browser extensions for their distinct needs. Indeed for many Firefox users — especially those unfamiliar with browser extensions — the process of finding an effective, trustworthy extension among tens of thousands of options can be a daunting and seemingly insurmountable challenge. Chat AI presents an opportunity to demystify the add-ons discovery experience. Users will be able to simply explain their browsing problem/issue/desire and the chat tool will find the best Firefox extension solution for them.

## Project Tasks

To build the Chat AI, we need open sourced softwares. This could be break down into following sub tasks. The subtasks are not in ordered.

- [Choosing open sourched LLM](#choosing-open-sourched-llm)
- [Choosing a LLM application creation framework](#choosing-a-llm-application-creation-framework)
- [Implement LLM with the framework](#implement-llm-with-the-framework)
- [Connecting Mozilla Add-ons API to framework](#monnecting-mozilla-add-ons-api-to-framework)
- [Pre-tuned or fine-tuned the model](#pre-tuned-or-fine-tuned-the-model)
- Deployment of the model to Cloud
- Creating ChatBot frontend
- Test and production

### Choosing open sourched LLM

There are few good ready-to-use  open sourced Large Language Models are availble which can be used for this project. These models are trained on huge datasets with billions of parameters. So, it will be able to understnd the user's need.
Here are some recent top LLMs.
- Llama2
- Claude 2
- MPT-7B
- Falcon
- Vicuna-13B

### Choosing a LLM application creation framework

LLM application frameworks are needed to wrap model with external drives or api calling. It makes the process far easier. One of the most used framework is ```Langchain```. It provides a wide range of tools to create custom made LLM application. There's also other open sourced frameworks too. ```FlowiseAI```, ```Auto-GPT```, ```AgentGPT``` are some of them.






