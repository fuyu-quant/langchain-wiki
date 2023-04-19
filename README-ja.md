# langchain
Introduce various applications using LangChain

## Contents
* [API](#api)
* [LangChain](#langchain)
    * [Models](#models)
    * [Promts](#prompts)
    * [Indexes](#indexes)
    * [Memory](#memory)
    * [Chains](#chains)
    * [Agents](#agents)
    * [Others](#others)
* [Use case](#use-case)
    * [Models](#models)
    * [Text Generation](#text-generation)
    * [Chat Model](#chat-model)
    * [Q&A](#qa)
    * [Summary](#summary)
    * [Utility](#utility)
* [Reference](#reference) 



## How to set up the API
Set the following environment variables
```bash
LANGCHAIN_HANDLER="langchain"
OPENAI_API_KEY=""
SERPAPI_API_KEY=""
HUGGINGFACEHUB_API_TOKEN=""

# 上記の内容を.envファイルに書き込み以下を実行
source .env
```

* [OpenAI](https://platform.openai.com/account/api-keys)
* [Google Search API](https://serpapi.com/dashboard)
* [News API](https://newsapi.org/docs/get-started)
* [The Movie Database API](https://developers.themoviedb.org/3/getting-started/authentication)
* [Hugging Face API](https://huggingface.co/settings/tokens)
* [CohereAI API](https://dashboard.cohere.ai/api-keys)



## LangChain
* LLMs
    * [OpenAI]()
    * [GPT4all](https://github.com/fuyu-quant/langchain/blob/main/models/LLMs/GPT4all.ipynb)
    * [llama-cpp](https://github.com/fuyu-quant/langchain/blob/main/models/LLMs/llama-cpp.ipynb)
    * [RWKV-4](https://github.com/fuyu-quant/langchain/blob/main/models/LLMs/RWKV.ipynb)
### text-embedding-models


### Models

### Prompts

### Indexes

### Memory

### Chains

### Agents

### others



## Use case

### Models
* [OpenAI Models](https://github.com/fuyu-quant/langchain/blob/main/examples/openai_models.ipynb)

* [Model Comparison](https://github.com/fuyu-quant/langchain/blob/main/examples/model_comparison.ipynb)

### Text Generation
* [SequentialChain](https://github.com/fuyu-quant/langchain/blob/main/examples/SequentialChain.ipynb)
* [QA Generation](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_generation.ipynb)


### Chat Model
* [simple chat model](https://github.com/fuyu-quant/langchain/blob/main/examples/simple_chat_model.ipynb)  
単純なchat model，何かになりきって回答することもできる

* [translate chat model](https://github.com/fuyu-quant/langchain/blob/main/examples/translate_chat_model.ipynb)  
翻訳するchat modelの構築

* [search chat model](https://github.com/fuyu-quant/langchain/blob/main/examples/search_chat_model.ipynb)  
検索により情報を調べて回答するchat modelの構築

* [conversation chat model](https://github.com/fuyu-quant/langchain/blob/main/examples/conversation_chat_model.ipynb)  
会話のためのchat modelの構築，記憶の保持の方法なども設定できる

* [customize chat model](https://github.com/fuyu-quant/langchain/blob/main/examples/customize_chat_model.ipynb)  
chat modelのさまざまなカスタマイズ方法



### Q&A
* [QA for document](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_for_document.ipynb)
* [QA for document with source](https://github.com/fuyu-quant/langchain/blob/main/examples/QA_for_document_with_source.ipynb)



### Summary
* [text summary](https://github.com/fuyu-quant/langchain/blob/main/examples/text_summary.ipynb)



### Utility
* [LLMMathChain](https://github.com/fuyu-quant/langchain/blob/main/examples/LLMMathChain.ipynb)
* [PALChain](https://github.com/fuyu-quant/langchain/blob/main/examples/PALChain.ipynb)
* [LLMBashChaion](https://github.com/fuyu-quant/langchain/blob/main/examples/LLMBashChain.ipynb)
* [LLMCheckerChain](https://github.com/fuyu-quant/langchain/blob/main/examples/LLMCheckerChain.ipynb)
* [LLMRequestsChain](https://github.com/fuyu-quant/langchain/blob/main/examples/LLMRequestsChain.ipynb)
* [OpenAIModerationChain](https://github.com/fuyu-quant/langchain/blob/main/examples/OpenAIModerationChain.ipynb)

## Reference
* https://zenn.dev/hamakou108/articles/ddddf1aa5a6100