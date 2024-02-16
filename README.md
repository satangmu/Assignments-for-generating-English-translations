# 자연스러운 영한 번역문 생성 과제
- 경진대회 기간 : 2023-10-27 ~ 2023-11-08
- 참가인원 : 64명
- 자연어(NLP) 영역 | BLEU Score
## 문제 정의
- 보다 자연스러운 기계 번역문을 생성하기 위한 영한 번역 및 사후 교정 문제


## 기술 스택
![py](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=Numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white)


## 데이터
- Input : 영어 문장 (7만여건)
- Output : 한국어 문장 (1만여건)

## 데이터 셋
![스크린샷 2024-01-25 195118](https://github.com/satangmu/Assignments-for-generating-English-translations/assets/148983269/d36ab77d-2c53-4f0e-8f32-28a4b87aaf0f)
- id : row 식별자
- text : 원문 (영어)
- mt : 기계 번역 결과 (교정 전)
- target : 번역문 (한국어)


## 평가지표
![스크린샷 2024-01-25 193340](https://github.com/satangmu/Assignments-for-generating-English-translations/assets/148983269/2221ce00-b4de-48df-870a-720b3f231474)


## 진행 과정
데이터 전처리 -> 모델 선택 -> 하이퍼 파라미터 튜닝 -> 제출


## 최종사용 모델
![스크린샷 2024-01-25 210914](https://github.com/satangmu/Assignments-for-generating-English-translations/assets/148983269/6e0d0fb9-1bb9-42d2-98fa-b7243ac0839d)

- KE-T5 : https://github.com/AIRC-KETI/ke-t5

## 결과
- 순위 : 6/64
- BLEU : 42.2919
![스크린샷 2024-01-25 193742](https://github.com/satangmu/Assignments-for-generating-English-translations/assets/148983269/ed79c992-6b22-490b-b573-45334c37686c)


