# KoAlpaca_llama_index
- [llama_index](https://github.com/jerryjliu/llama_index/tree/main)는 사용자가 갖고 있는 private 데이터를 LLMs에 추가, 확장하기 위해 제안된 data framework
- **UnStructured Data**(pdf, txt, videos, images, etc.), **Structured Data**(Excel, SQL, etc.) **Semi-Structured**(Salesforce, Notion, etc.) 데이터를 활용할 수 있음

 ### 예제
- LLM
  - [beomi/KoAlpaca](https://github.com/Beomi/KoAlpaca)
- Document
  - [Viquna 모델 정리.pdf](https://github.com/Jinhyeong-Lim/KoAlpaca_llama_index/files/11927708/Viquna.pdf)

|Type|Text|
|---|---|
|Query|Viquna 모델 학습 방법에 대해 설명해줘|
|[ChatKoAlpaca](https://chat.koalpaca.com/)|Viquna 모델은 Hierarchical relationship model을기반으로 한 얼굴 인식 및 객체 검출에 사용되는 딥러닝 모델입니다. Viquna는sklearn과 torch 모델이며 linear regression, binary classification, semi-supervised learning등의 서브 모델을 포함하고 있습니다.|
|KoAlpaca_llama_index (using Document)|Viquna 모델은 대화 기반 챗봇 학습 방법으로 대화 데이터를 사용하여 학습하는 언어 모델입니다. 이 모델은 대화 데이터를 사용하여 새로운 대화 데이터를 생성하고 이를 사용하여 학습하며, 이를 통해 새로운 대화를 생성하는 능력을 향상시키고 있습니다|
