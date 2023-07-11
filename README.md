# KoAlpaca_llama_index

<img width="237" alt="image" src="https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/assets/64317686/5d9e9142-0250-4785-a798-24b35e1c2bee">
<img width="225" alt="image" src="https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/assets/64317686/bef6f7da-712e-4e46-a3a6-e3081fdbc378">


### [KoAlpaca](https://github.com/Beomi/KoAlpaca)
Korean Alpaca Model based on Stanford Alpaca (feat. LLAMA and Polyglot-ko)
- Stanford Alpaca 모델을 학습한 방식과 동일한 방식으로 학습을 진행한, 한국어를 이해하는 Alpaca 모델입니다

### [llama_index](https://github.com/jerryjliu/llama_index/tree/main)
LlamaIndex (GPT Index) is a data framework for your LLM application

- llama_index는 사용자가 갖고 있는 private 데이터를 LLMs에 추가, 확장하기 위해 제안된 data framework
- **UnStructured Data**(pdf, txt, videos, images, etc.), **Structured Data**(Excel, SQL, etc.) **Semi-Structured**(Salesforce, Notion, etc.) 데이터를 활용할 수 있음


## Overview
- [BingChat](https://www.microsoft.com/en-us/edge/features/bing-chat?form=MT00D8), [SearchGPT](https://channeltech.naver.com/contentDetail/20)와 같이 검색을 위해 사용자가 작성한 쿼리에 대한 답변을 LLM을 사용하여 생성해주는 서비스
- 한국어 위키피디아 데이터 셋을 활용하여 대량의 문서를 미리 인덱싱하고, 쿼리가 주어졌을 때 관련 내용을 찾고 LLM을 활용하여 이를 바탕으로 답변을 생성해주는 프레임워크 구축
