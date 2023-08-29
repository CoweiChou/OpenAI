# OpenAI

## What is OpenAI?
OpenAI 是一家人工智能研究實驗室和公司，致力研究、開發先進的自然語言處理（NLP）和深度學習模型。其中最知名的之一是 GPT（Generative Pre-trained Transformer）系列模型，它是基於Transformer架構的語言模型，能夠生成具有連貫性和多樣性的文本。

OpenAI is an artificial intelligence research laboratory and company dedicated to researching and developing advanced natural language processing (NLP) and deep learning models. One of its most prominent contributions is the GPT (Generative Pre-trained Transformer) series of models, which are language models based on the Transformer architecture capable of generating text with coherence and diversity.

#

## How to use
- 串接openai的API，提供多種不同的模型和功能 https://platform.openai.com/docs/models
- 每個模型都有不同的參數需要設定調整，也可能需要特定的輸入格式和資料預處理
- 了解每個模型的收費模式和tokens輸入和輸出數量的限制
- Token 是文本的最小單位，可以是單詞、子詞、字符或者其他語言單位，具體取決於模型的設計。
#
- Integrate OpenAI's API to access a variety of different models and functionalities. The documentation can be found at https://platform.openai.com/docs/models.
- Each model has distinct parameters that need to be configured and adjusted. Specific input formats and data preprocessing might also be required.
- Familiarize yourself with the pricing structure and the limitations on tokens for input and output for each model.
- Tokens are the smallest units of text used in OpenAI models. They can represent words, subwords, characters, or other linguistic units, depending on the model's design.


#

##  Model demo
### GPT-3.5 / text-davinci-003
以 `text-davinci-003` 模型為例。這個模型可以根據一個給定的提示（prompt）來生成相關的文本。
`model` 參數指定了使用的模型，`prompt` 參數是生成文本的提示，`max_tokens` 控制生成文本的最大長度，`top_p`、`frequency_penalty` 和 `presence_penalty` 則是生成文本的一些設定。

Taking the `text-davinci-003` model as an example. This model can generate relevant text based on a given prompt.
The `model` parameter specifies the model being used, the `prompt` parameter is the prompt for generating text, `max_tokens` controls the maximum length of the generated text, and `top_p`, `frequency_penalty`, and `presence_penalty` are some settings for generating text.

