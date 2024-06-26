# 2023-KMU-Undergraduate-Research-Internship
국민대학교 2023학년도 동계방학 학부생 연구인턴십 프로그램
---
## 1. 배경 & 목적
- 주관 : 국민대학교 산학협력단
- 목적 : 학부수업에서 배운 전공지식을 바탕으로 다양한 분야의 연구실에서 연구 및 실험 경험을 통해 연구 현장 및 연구프로젝트에 대한 이해도를 높이고 대학원 진학 등 진로 탐색의 기회를 제공 하고자 함

---

## 2. 주요일정
- 2023.11.27.(월) ~ 2023.12.12.(화) : 접수기간
- 2023.12.13.(수) : 평가 및 대상자 선발
- 2023.12.14.(목) : 대상자 통보
- 2023.12.18.(월) ~ 2024.01.26.(금) : 인턴십 수행(6주)
- 2024.02.02.(금) : 결과보고서 제출
---
## 3. 연구 목적 및 필요성
- 테니스 도메인의 경우 골프 도메인에 비해 동작 분석 연구 결과와 video dataset이 많지 않았다. 또한, 골프의 경우 사용자의 골프
자세를 측정 및 분석하여 자세 보정 서비스를 제공하는 플랫폼이 시중에 출시 되어있다. 최근 테니스 수요가 커지고 있는 만큼 테니
스 이용층의 테니스 자세 보정 서비스 니즈가 증가할 것이다. 이에 프로와 아마추어의 테니스 동작 유사도 분석 연구를 통해 사용자
의 동작을 SMPL Rendering 3D 영상과 동작 유사도를 함께 보여주는 시스템을 개발해 보고자 한다.
---
## 4. 연구 내용 목차
1. 관련 논문 및 데이터셋 조사
2. 관련 모델 Inference
3. 동작 유사도 측정 방식
4. 추후 연구 계획
5. 참고문헌

## 5. 연구 결과
- 예상 결과  
테니스 동작의 전체 유사도와 관절별 동작 유사도를 계산하여 프로와 아마추어의 테니스 동작 유사도를 분석할 수 있을 것으로 예상한다.

- 과제 결과 및 개선방안
1. SMPL Rendering
SMPL로 생성한 3D mesh rendering output의 프레임 간 기준점이 없어 영상으로 변환 시 떨리는 현상이 있었다.
Tracking model(Co-Tracker)로 영상 속 사람의 발끝, 손끝 등 특정 신체 부위를 추적하여 이를 기준점으로 삼아
프레임 간 3D mesh rendering 결과를 보정하고자 한다.

2. 동작 유사도 측정 방식
직교 좌표계 상의 3D 관절 좌표를 구면 좌표계 상에서 기준 관절과 주변 관절과의 극값과 방위각을 포함하는 관절
각도 벡터로 변환한다. 관절 각도 벡터와 DTW 알고리즘을 활용하여 동작 유사도 측정 방식을 정립하고자 한다.

---
## 6. 기대효과 및 활용방안
- 전체 유사도뿐만 아니라 관절 별 유사도를 측정할 수 있고 이 점을 활용해 테니스 동작의 주를 이루는 팔동작의 동작 유사도를 집
중적으로 분석할 수 있다. 사용자는 테니스 12가지 동작 중 전문가와 자신의 동작 유사도를 부위별로 측정할 수 있으며 SMPL
Rendering을 통해 3D Video로도 확인할 수 있을 것으로 기대한다.
---
# 7. 자료
- 결과보고서  
  [[결과보고서] 학부연구생 인턴십.pdf](https://drive.google.com/file/d/1d3AkJKOdB5ZSGBWCKHF0BAPG7Ijo04fJ/view?usp=drive_link)  
