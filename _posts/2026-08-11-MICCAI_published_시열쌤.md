---
layout: post
author: minju
title: 이시열 학생, “wBCAM” MICCAI 컨퍼런스 논문 Accept
image: /images/news/2026/miccai_logo.png
sub: Medical Image Computing and Computer Assisted Intervention, MICCAI 2026 컨퍼런스 논문 게재 승인
---
우리 연구실의 이시열 학생이 Medical Image Computing and Computer Assisted Intervention, MICCAI 2026 컨퍼런스 논문 게재 승인을 받았습니다.

<img src='/images/news/2026/miccai_시열쌤.png' style="width: 100%; max-width: 1000px; height: auto;" alt="Responsive Image">

"wBCAM: Windowed Bi-directional Cross-Attention with Mamba for Enhanced 3D Vascular Reconstruction in Free-Hand Photoacoustic and Ultrasound Imaging"은 외부 추적 장치 없이 프리핸드 광음향·초음파(PAUS) 영상의 스캔 움직임을 추정하고 3D 혈관 구조를 재구성하는 센서리스 프레임워크를 제안하여 2026 국제의료영상컴퓨팅 및 인터벤션 학술대회(MICCAI)에 게재될 예정이다.

통합 광음향·초음파(PAUS) 영상은 기존 초음파(US) 영상과 광음향(PA) 영상을 하나의 시스템에서 동시에 획득할 수 있어 높은 임상 적용 가능성을 가진다. 그러나 휴대형 PAUS 시스템에서는 신뢰할 수 있는 스캔 궤적 정보 없이 3D 혈관 구조를 재구성하기 어려우며, 외부 추적 장치를 사용할 경우 비용과 시스템 복잡성이 증가한다.

본 연구에서 제안한 windowed Bi-directional Cross-Attention with Mamba (wBCAM)는 windowed bi-directional cross-attention과 Mamba 기반 global memory를 결합하여 장거리 스캔 동역학을 모델링하고, 시간적으로 일관된 움직임 추정을 수행한다. 이를 통해 외부 추적 장치 없이 프리핸드 PAUS 영상으로부터 안정적인 고해상도 3D 광음향 혈관 구조를 재구성할 수 있다.

제안 방법은 동적 환경에서 획득한 생체 내(in vivo) 인체 전완 데이터셋을 이용하여 검증하였다. 정량적·정성적 평가 결과, wBCAM은 장거리 움직임 추정 성능을 향상시키고 안정적인 고해상도 3D 혈관 재구성을 가능하게 하였다.

[GitHub Repository](https://github.com/pnu-amilab/wBCAM)