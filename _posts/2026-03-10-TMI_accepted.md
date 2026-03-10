---
layout: post
author: minju
title: 이시열, 서민경 학생, "ASTRA-Net" IEEE TMI 저널 논문 Accept
image: /images/research/airway_tmi.jpg
sub: IEEE Transactions on Medical Imaging 저널 논문 게재 승인
---
우리 연구실의 이시열, 서민경 학생이 IEEE Transactions on Medical Imaging 저널 논문 게재가 승인되었습니다.
<img src='/images/research/airway_tmi.jpg' style="width: 100%; max-width: 1000px; height: auto;" alt="Responsive Image">

"Discovery of Peripheral Airway Beyond Incomplete CT Annotations for Navigational Bronchoscopy"
<br>
위 논문에서는 흉부 CT 영상에서 기도(Airway)를 추출(분할; Segmentation)하기 위한 Anatomical Segmentation with Tree-aware Refinement Attention Network (ASTRA-Net)을 제안합니다.
흉부 CT에서 기도는 내부가 어두운 원형 구조로 식별되는데, 얇은 기도로 갈수록 경계(Boundary)가 모호해지고, 내부와 외부의 픽셀 밝기 차이가 비슷하여 구분에 어려움이 있다. 
이를 위하여 디자인된 ASTRA-Net은 흉부 구조물(혈관, 폐)와 기도의 형태(반지름, 중심과의 거리) 등의 해부학적인 지식을 이용하여 학습하는 네트워크이다. 보다 깊고 미세한 기도 추출을 위한 Edge-Guided Attention (EGA)를 도입하여 학습 단계를 거치고, 후최적화 단계에서는 저해상도 CT에 대처하기 위한 지식 증류 기반의 학습으로 미세 기도에 대한 민감성을 향상시켰다.
제안된 모델은 Tree Detected Ratio (TDR), Branch Detected Ratio (BDR) 지표에서 SOTA에 비하여 크게 향상된 성능을 보였고, Airway Tree Modeling 2022 (ATM'22) 대회의 Post-validation phase에서 두 지표 1위를 기록하고 있다. 
한편, ASTRA-Net은 정답(Label)보다 더 깊고 미세한 기도 가지를 찾아내는 결과로 인하여, Dice Score Coefficient (DSC), Precision (PRE) 지표 부분에서는 다소 하향된 경향을 보인다. 
그러나 이는 지도학습에 사용된 정답이 불완전한 것으로, 이를 입증하기 위한 추가 Labeling을 진행하여, 더 찾은 부분(Over-segmentation)이 실제로 올바르게 찾은 기도임을 확인하였다. 
추가적으로, ASTRA-Net은 공개 데이터셋 뿐만 아니라, 양산부산대학교 병원의 원내 데이터셋(in-house)을 이용하여 일반화 성능을 검증하였다. (공개 데이터셋으로 학습 후 in-house 데이터셋으로 평가만 진행)
최종적으로 ASTRA-Net을 활용할 수 있는 분야(기관지 내시경 가이드, C-arm 퓨전)에서의 프로토타입을 보였다. 