# 大模型离线翻译

## Sakura大模型

::: tip
推荐使用，配置简单，效果好，也可以纯cpu运行轻量模型 
:::

部署方法可参考 https://github.com/SakuraLLM/SakuraLLM/wiki

## 大模型通用接口

也可以使用[llama.cpp](https://github.com/ggerganov/llama.cpp) 、[ollama](https://github.com/ollama/ollama)、[one-api](https://github.com/songquanpeng/one-api)之类的工具进行模型的部署，然后将地址和模型填入。

也可以使用Kaggle之类的平台来把模型部署到云端，这时可能会需要用到SECRET_KEY，其他时候可以无视SECRET_KEY参数。