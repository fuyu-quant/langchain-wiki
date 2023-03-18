# langchain
Introduce various applications using LangChain

## Contents
* [Basic docker operations](#basic-docker-operations)
* [API](#api)
* [LangChain](#langchain)
    * [Models](#models)
    * [Chat Model](#chat-model)
    * [Q&A](#qa)
    * [Summary](#summary)
    * [Utility](#utility)
* [Reference](#reference) 


## [Basic docker operation](https://github.com/fuyu-quant/dockerfile-for-data-scientists)

## How to set up the API
Set the following environment variables
```bash
LANGCHAIN_HANDLER="langchain"
OPENAI_API_KEY=""
SERPAPI_API_KEY=""
HUGGINGFACEHUB_API_TOKEN=""

```

* [OpenAI](https://platform.openai.com/account/api-keys)
* [Google Search API](https://serpapi.com/dashboard)
* [Hugging Face API](https://huggingface.co/settings/tokens)
* [CohereAI API](https://dashboard.cohere.ai/api-keys)


## LangChain


### Models
* [models](https://github.com/fuyu-quant/langchain/blob/main/examples/models.ipynb)



### Chat Model
* [base_chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/base_chat_model.ipynb)  
基本的なchat modelの構築
* [chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/chat_model.ipynb)  
応用的なchat modelの構築



### Q&A
* [QA_for_document](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_for_document.ipynb)
* [QA_for_document_with_source](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_for_document_with_source.ipynb)



### Summary
* [text_summary](https://github.com/fuyu-quant/langchain/blob/main/examples/text_summary.ipynb)



### Utility
* [LLMMathChain](https://github.com/fuyu-quant/langchain/blob/main/examples/LLMMathChain.ipynb)
* [PALChain](https://github.com/fuyu-quant/langchain/blob/main/examples/PALChain.ipynb)



## Reference
* https://zenn.dev/hamakou108/articles/ddddf1aa5a6100