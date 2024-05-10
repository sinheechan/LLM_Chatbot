# LLM_to_Chatbot

<br/>

<img src="img/LLM_bot.png">

<br/>

**[ LLM 이란? ]**

- 대형 언어 모델(LLM)은 방대한 양의 데이터를 기반으로 사전 학습된 초대형 딥 러닝 모델이다.
  
- 모델은 "자기 지도 학습(self-supervised learning)" 방식으로 사전 훈련되며, 대량의 텍스트 데이터를 사용하여 다음 단어를 예측하도록 학습된다.
  
- 일반적으로 LLM은 다양한 자연어 처리 작업에 적용될 수 있으며, 텍스트 생성, 감정 분석, 문장 유사도 측정 등 다양한 작업에 활용된다.

**[ 동작 원리 ]**

- LLM 작동 방식의 핵심 요소는 단어를 나타내는 방식이다.
  
- 일반적인 형태의 기계 학습은 숫자 표를 사용하여 각 단어를 표현하나 비슷한 의미를 가진 단어와 같은 단어 간의 관계를 인식할 수 없다.
  
- 하지만 워드 임베딩과 같은 다차원 벡터를 사용하여 벡터 공간에서 문맥상 의미가 비슷하거나 다른 관계가 있는 단어가 서로 가깝도록 단어를 표현함으로써 어느정도 한계를 극복했다.

- 트랜스포머는 워드 임베딩을 사용하여 인코더를 통해 `텍스트를 숫자 표현으로 사전 처리하고 비슷한 의미를 가진 단어 및 구문의 문맥은 물론 품사와 같은 단어 간의 기타 관계를 이해`할 수 있다.

- 그러면 LLM은 `디코더를 통해 이러한 언어 지식을 적용하여 고유한 출력을 생성`할 수 있습니다.

<br/><br/>

## Link

- 서울과학기술대학교 , Teddysum , 연세대 MLPLab 에서 개발한 모델이며 모델에 대한 이해화 학습을 목표로 진행합니다.

<br/><br/>

## Model Introduce

<br/>

**[ Llama-3-Open-Ko-8B ]**

- Llama-3-Open-Ko-8B 모델은 "Llama-3-8B"를 기반으로하여 60GB 이상의 중복 제거된 텍스트와 공개적으로 사용 가능한 리소스를 이용하여 학습되었습니다.
  
- 이 모델은 한국어 토크나이저를 사용하여 177억 개 이상의 토큰으로 사전 학습되었습니다.

<br/>

**[ MLP-KTLim/llama-3-Korean-Bllossom-8B ]**

- Bllossom 언어 모델은 LLama3를 기반으로 한 한-영 이중 언어 모델로, 한국어와 영어의 지식 연계성을 높여주며, 한국어 표현력을 향상시키기 위해 어휘 확장을 제공합니다.
  
- 특화된 데이터를 활용하여 한국어와 한국 문화에 맞춤형 명령어를 제공하고, 인간 피드백을 반영하고, 비전-언어 정렬을 지원합니다.
