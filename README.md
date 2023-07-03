# KoAlpaca_llama_index

<img width="237" alt="image" src="https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/assets/64317686/5d9e9142-0250-4785-a798-24b35e1c2bee">
<img width="225" alt="image" src="https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/assets/64317686/bef6f7da-712e-4e46-a3a6-e3081fdbc378">

- [llama_index](https://github.com/jerryjliu/llama_index/tree/main)는 사용자가 갖고 있는 private 데이터를 LLMs에 추가, 확장하기 위해 제안된 data framework
- **UnStructured Data**(pdf, txt, videos, images, etc.), **Structured Data**(Excel, SQL, etc.) **Semi-Structured**(Salesforce, Notion, etc.) 데이터를 활용할 수 있음

 ### 예제
- LLM
  - [beomi/KoAlpaca](https://github.com/Beomi/KoAlpaca)
- Document
  - [Vicuna.pdf](https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/files/11933271/Vicuna.pdf)


|Type|Text|
|---|---|
|Query|Vicuna 모델 학습 방법에 대해 설명해줘|
|[ChatKoAlpaca](https://chat.koalpaca.com/)|Vikuna 모델의 학습 방법은 지도학습으로, 데이터를 기반으로 모델이 연속적인 출력을 생성합니다.|
|KoAlpaca-7B_llama_index (using Document)|Vicuna 모델은 대화 내 텍스트 데이터를 이용하여 샘플을 추출하고 처리하며, 이를 토론토 알고리즘을 사용하여 최종 출력을 생성합니다. 이 모델은 대화 내 텍스트 데이터를 이용하여 샘플을 추출하고 처리하며, 이를 토론토 알고리즘을 사용하여 최종 출력을 생성합니다. 이러한 한계를 해결하기 위해 Vicuna가 future research의 open starting point가 되길|
|KoVicuna-7B_llama_index|Vicuna 모델은 컨텍스트 정보를 활용하여 대화 상호작용을 더 잘 이해하고 응답을 생성하는 방법을 학습하도록 설계되었습니다. 이는 챗봇 및 기타 자연어 처리 애플리케이션에 유용할 수 있습니다. 이 모델은 대화 샘플 70,000개를 사용하여 학습되었으며, 더 나은 성능을 위해 챗봇 및 기타 모델에 사용|
