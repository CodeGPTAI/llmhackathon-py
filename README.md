# Create an app with the Mistral API and Code GPT

### This project implements a chat application using the Mistral API and CodeGPT, developed with [Streamlit](https://streamlit.io/).

<!-- add an image -->
<img src="https://raw.githubusercontent.com/gustavoespindola/llmhackathon-py/refs/heads/master/hackathon.gif" alt="llmhackathon" width="100%">

This project demonstrates the integration of advanced AI models through:
- Mistral AI API for language processing
- CodeGPT API to interact with specialized agents
- Streamlit for an intuitive user interface

## 🛠️ Prerequisites

To use this application you will need:

### For Basic Implementation
**Integration with Mistral API**
   - Obtain your [Mistral API Key](https://console.mistral.ai/api-keys/)
   - Test API endpoints using the provided .http file ([Mistral Endpoints Documentation](https://docs.mistral.ai/api/#tag/models))
   - Implement chat functionality using Streamlit

### For Advanced Features
**Setting up the CodeGPT Agent**
   - Create an AI Agent through CodeGPT
   - Load the necessary agent data
   - Configure the agent ID
   - Configure the CodeGPT API key
   - Implement interactions with the agent in the chat interface

## 📚 Essential Resources

- [🎯 LLMHackathon](https://llmhackathon.dev/)
- [🔑 Mistral API Documentation](https://console.mistral.ai/api-keys/)
- [🎯 Mistral Endpoints](https://docs.mistral.ai/api/#tag/models)
- [📚 Streamlit Documentation](https://streamlit.io/)
- [🚀 Register on CodeGPT](app.codegpt.co/r/gustavo)
- [📖 CodeGPT API Key](https://app.codegpt.co/en/apikeys)
- [📖 CodeGPT Documentation](https://developers.codegpt.co/reference/completion-beta)

---

## 🔧 Installation Instructions

**Clone the repository**

`git clone https://github.com/gustavoespindola/llmhackathon-py`

**Enter the project folder**

`cd llmhackathon-py`

**Install dependencies**
```bash
# Install required dependencies
  pip install -r requirements.txt

## Start the development server
```Bash
  streamlit run app.py
```

You can now view your Streamlit app in your browser.
```Bash
  ➜  Local URL: http://localhost:8501
  ➜  Network URL: http://192.168.100.5:8501
```
The application will be available at `http://localhost:8501`

## 🌐 Deployment Guide

Deployment on Streamlit Cloud

1. Create an account on Streamlit
2. Create a new project
3. Link with the repository
4. Configure environment variables
5. Execute the deployment

### Configure environment variables:

- Managing secrets in [Streamlit Local](https://docs.streamlit.io/develop/api-reference/connections/st.secrets)
- Managing secrets in [Streamlit Cloud](https://docs.streamlit.io/deploy/streamlit-community-cloud/deploy-your-app/secrets-management)

Enter the .secrets folder and open the secrets.toml file. In this file, enter the following environment variables:

For the Mistral example, use the variable `MISTRAL_API_KEY` and `MISTRAL_MODEL`
[🔑 Mistral API Documentation](https://console.mistral.ai/api-keys/)

For the CodeGPT example, use the variable `CODEGPT_API_KEY`
[📖 CodeGPT API Key](https://app.codegpt.co/en/apikeys)
