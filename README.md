# <대규모 언어 모델, 핵심만 빠르게!>(인사이트, 2025)

이 책은 안드리 부르코프의 베스트셀러 《머신러닝, 핵심만 빠르게!》의 후속작으로, 언어 모델링의 기초부터 시작하여 최신 대규모 언어 모델(LLM)을 간결하면서도 철저하게 다룬다. 독자들은 이 책을 통해 현대 머신러닝과 신경망의 수학적 기초, 파이썬으로 구현하는 카운트, RNN 기반 언어 모델, 파이토치로 직접 만드는 트랜스포머, LLM 실습(지시 미세 튜닝, 프롬프트 엔지니어링)까지 체계적으로 학습할 수 있다.

실행 가능한 파이썬 코드와 구글 코랩 환경을 기반으로 실습형으로 구성된 이 책은 누구나 단계별로 따라가며 이해를 확장할 수 있다. 언어 모델이 단순한 n-그램 통계에서 출발해 오늘날 AI의 핵심 기술로 성장해 온 과정을 카운트 기반 방.법부터 시작해서 최신 트랜스포머 아키텍처까지 설명하며, 원리와 구현을 함께 다룬다. 각 장은 앞선 내용을 토대로 점진적으로 발전하며, 복잡한 개념도 명확한 설명과 그림, 실습을 통해 쉽게 이해할 수 있도록 구성되어 있다.

이 책에서 다루는 내용
- 머신러닝과 신경망의 핵심 개념
- 텍스트 표현 기법과 기본 언어 모델링
- 파이토치로 RNN과 트랜스포머 구현하기
- 언어 모델의 미세 튜닝과 프롬프트 엔지니어링 실무 지침
- 환각 문제와 모델 평가에 관한 주요 고려 사항

| 장.절 | 노트북 | 스크립트 |
|--|--|--|
| 1.2 | [quadratic_loss.ipynb](quadratic_loss.ipynb) | [quadratic_loss.py](quadratic_loss.py) |
| 2.3 | [byte_pair_encoding.ipynb](byte_pair_encoding.ipynb) ||
| 2.5 | [count_language_model.ipynb](count_language_model.ipynb) ||
| 3.6 | [news_RNN_language_model.ipynb](news_RNN_language_model.ipynb) ||
| 4.9 | [news_decoder_language_model.ipynb](news_decoder_language_model.ipynb) ||
| 5.3.1 | [emotion_classifier_LR.ipynb](emotion_classifier_LR.ipynb) ||
| 5.3.2 | [emotion_GPT2_as_text_generator.ipynb](emotion_GPT2_as_text_generator.ipynb) ||
| 5.3.3 | [instruct_GPT2.ipynb](instruct_GPT2.ipynb) ||
| 5.4 | [sampling_method.ipynb](sampling_method.ipynb) ||
| 5.5.2 | [emotion_GPT2_as_text_generator_LoRA.ipynb](emotion_GPT2_as_text_generator_LoRA.ipynb) ||
| 5.6 | [emotion_GPT2_as_classifier.ipynb](emotion_GPT2_as_classifier.ipynb) ||

### 추가 코드
* 임베딩 층과 선형층의 동등성 : [embedding_vs_linear.ipynb](embedding_vs_linear.ipynb)
* CNN을 이용한 텍스트 감정 분류 : [emotion_classifier_CNN.ipynb](emotion_classifier_CNN.ipynb)
* 분서 분류기 훈련하기 : [document_classifier_with_LLMs_as_labelers.ipynb](document_classifier_with_LLMs_as_labelers.ipynb)
* 밑바닥부터 단일 GPU 사용한 GRPO 구현 : [GRPO.ipynb](GRPO.ipynb)
* 밑바닥부터 분산 GRPO 구현 : [GRPO_From_Scratch_Multi_GPU_DataParallel_Qwen_2_5_1_5B_Instruct.ipynb](GRPO_From_Scratch_Multi_GPU_DataParallel_Qwen_2_5_1_5B_Instruct.ipynb)
* `trl` 라이브러를 사용한 GRPO 구현 : [GRPO_Qwen_0_5_Instruct.ipynb](GRPO_Qwen_0_5_Instruct.ipynb) 

<img src="https://tensorflow.blog/wp-content/uploads/2025/10/cover-the-lm-book.jpg" width="600">
