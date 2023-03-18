# langchain
Introduce various applications using LangChain

## Contents
* [Basic docker operations](#basic-docker-operations)
* [API](#api)
* [LangChain](#langchain)
    * [Models](#models)
    * [Text Generation](#text-generation)
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

### Text Generation
* [SequentialChain](https://github.com/fuyu-quant/langchain/blob/main/examples/SequentialChain.ipynb)
* [QA_generation](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_generation.ipynb)


### Chat Model
* [simple_chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/simple_chat_model.ipynb)  
単純なchat model

* [role_chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/role_chat_model.ipynb)  
役になりきって応答するchat model

* [search_chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/chat_model.ipynb)  
検索により情報を調べて回答するchat modelの構築

* [search_chat_model](https://github.com/fuyu-quant/langchain/blob/main/examples/chat_model.ipynb)  
検索により情報を調べて回答するchat modelの構築



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