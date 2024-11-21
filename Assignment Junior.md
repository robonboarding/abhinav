# Technical Test Outline for Junior Engineers

---

## Introduction

The purpose of this technical test is to evaluate a candidate's practical software engineering skills in a controlled environment. This test focuses on real-world problem-solving and includes an introduction, a hands-on coding session, and a follow-up discussion to explore the candidate’s approach and understanding.

### Test Duration:
- **Introduction**: 15 minutes to cover test setup and objectives
- **Coding Task**: 3 hours of hands-on engineering work
- **Technical Discussion**: 15 minutes to review solutions and discuss thought processes

---

## Pre-installed Tools

- ChatGPT client
- Visual Studio Code
- PyCharm
- IntelliJ
- HomeBrew
- Spider
---

## Pre-installed Coding Languages

- Python3
- JavaScript
- Java
- Node.js
- PHP
- Scala
- C++
- C#

---

## The Case

### Explanation of the Exercise
Candidates are tasked with building a small backend application that can handle basic RESTful API requests. The backend should interact with an LLM (large language model) endpoint hosted on Azure (details are in the technical tips section) to fulfill specific application functionalities.

**Objective**: To create a functional backend that can process data from an Azure-hosted LLM and deliver structured responses.

---

## Tips

To encourage a comprehensive approach, candidates should keep the following in mind:

- **API Design**: Think about creating a simple, clear API interface for future frontend integration.
- **Scalability**: Consider how the backend could handle increased demand or future feature expansion.
- **Error Handling and Security**: Implement robust error handling and basic security best practices.
- **Tool usage**: Use all tools at your disposal. We want to evaluate your ability to develop, similar to a day-to-day in the office so make smart use of Google and ChatGPT. 

---

## Technical Details

**LLM Endpoint on Azure**: Candidates will use an LLM hosted on Azure to provide specific functionalities within the application. The interaction with this LLM should be evident in the backend code.

- **Endpoint for LLM hosted on Azure**: Candidates will interact with an LLM (large language model) endpoint hosted on Azure to provide specific functionalities within the application. This interaction should be evident in both the backend and frontend implementations.
- GPT-4o-mini: https://open-ai-resource-rob.openai.azure.com/openai/deployments/gpt-4o-mini/chat/completions?api-version=2024-08-01-preview
- Text-embedding: https://open-ai-resource-rob.openai.azure.com/openai/deployments/text-embedding-3-large/embeddings?api-version=2023-05-15
- The API key can be found in the Key Vault storage secrets in the azure account that was setup. Keyvault name: open-ai-keys-rob, secret name: open-ai-resource-rob
- The code can be deployed to an assigned azure resource group with your name in it. If your resource group is missing or not working well feel free to use the backup resourcegroup
- Azure account: email:Robapplicant@outlook.com, pwd: Rabobank
- Make sure to upload your code to a github (feel free to use the current github account and create a new repo, or create it in your own git and add robonboarding@outlook.com as a contributor)
- Since everyone takes different approaches you could be blocked by permissions that aren't covered yet for the account. If that happens let us know as soon as possible and we'll give you access to the resource if the request is valid

---

## Evaluation

### Expectations of the Demo

Candidates are expected to demonstrate a basic but functional backend application that reflects their technical abilities and understanding of modern application structures. In the demo you'll have time to explain your chain of thoughts behind the decisions you've taken during the development process. Also, you can elaborate on the setbacks, future improvements, architecture etc. 

### Evaluation Attributes
Candidates will be evaluated based on:

- **Creativity**: Innovative approaches or features implemented in the backend.
- **Capability to Learn**: Adaptation and utilization of both new and familiar technologies.
- **Code Quality**: Readability, structure, and adherence to coding best practices.

---

## Key Steps in Development

1. **Backend Creation**: A working backend that can handle RESTful API requests.
2. **LLM Integration**: Successfully integrate the backend with the Azure-hosted LLM.

---

## Getting started

- On the Rabobank laptop, Create a directory in /documents/ with your name. Here you can make your changes for local development. 
- Make sure to check out your resources in azure with the account provided in the technical details
- Start with a very basic poc before adding creative extra's
- Create a new directory on your local machine for all of your development in documents/

