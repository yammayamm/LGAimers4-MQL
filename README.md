# About LG Aimers
[LG Aimers](https://www.lgaimers.ai/)는 최고의 교수진이 함께 하는 AI교육과 LG의 실제 데이터를 다루는 AI해커톤에 참여할 수 있는 경험의 기회를 제공하는 LG그룹의 청년 교육 프로그램이다. LG AI연구원에서 진행하며 1개월의 온라인 교육과 1개월의 해커톤으로 구성된다. 해커톤에서는 LG의 여러 계열사가 보유한 다양한 산업의 현장 Data를 직접 다루고, 문제를 해결하는 실무 경험을 쌓을 수 있다.

## LG Aimers 4기
- 해커톤 주제: MQL 데이터 기반 B2B 영업기회 창출 예측 모델 개발

  <img width="658" alt="image" src="https://github.com/yammayamm/LGAimers4-MQL/assets/49015100/66990dca-d638-40c0-bc3f-7388e1f6dfcb">

- 기간: 2024.02.01\~2024.02.26(온라인), 2024.04.06~2024.04.07(오프라인)
- 결과: Public 3rd, Private(Final) 3rd 🥉
  ![image](https://github.com/yammayamm/LGAimers4-MQL/assets/49015100/855810d1-f578-4926-8bcd-6fb8052b99f5)

## Model
CatBoostClassifier + Optuna (hyper-parameter tuning) 

기본 catboost 모델에 가장 높은 가중치(0.4)를 주고 튜닝한 4개의 모델들에 동일한 가중치(0.15)를 주어 soft voting 진행

<img width="1256" alt="image" src="https://github.com/yammayamm/LGAimers4-MQL/assets/49015100/1ee965c9-3f54-4cd3-9f1c-7bb1a8d603b2">
