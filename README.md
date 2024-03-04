# Temporal Convolutional Autoencoder를 사용한 스마트 그리드에서의 FDIA 탐지 기법
False Data Injection Attack Detection in Smart Grid using Temporal Convolutional Autoencoder

## 프로젝트 요약
스마트 그리드(Smart Grid)는 분산된 측정 장치간 양방향 통신을 중심으로 하는 상호 연결된 구조로 인해 사이버 공격에 취약하다. False Data Injection Attack(FDIA)과 같은 사이버 공격은 스마트 미터에서 측정된 전력 데이터를 조작하여 대규모 정전과 같은 피해를 초래할 수 있다. FDIA 탐지는 전력 데이터의 복잡한 시간적 패턴과 정답이 없는 관측 데이터로 인해 성능 향상에 어려움을 가진다. 이를 해결하기 위해,  Temporal Convolutional Network(TCN)와 Autoencoder를 결합한 FDIA 탐지 모델을 구현한다. 실제 데이터와 함께, 제안된 모델은 탐지 정확성 측면에서 기존 탐지 기법에 비교하여 우수한 성능을 보여주었다.

## FDIA 탐지 전체 과정
![정보과학회 논문그림1](https://github.com/y00ns/FDIA_with_TCN/assets/104632673/8665a66c-1ccd-4e9c-911e-79cd2229e3f0)


## TCN-AE 모델 구조
![정보과학회 논문그림2](https://github.com/y00ns/FDIA_with_TCN/assets/104632673/d72d6e9d-2a5c-4feb-9be5-887c5b56b148)


## 전력 데이터에 공격 주입
![정보과학회 논문그림3](https://github.com/y00ns/FDIA_with_TCN/assets/104632673/9a6b9e21-92a7-49d9-ba75-8549df001f92)
