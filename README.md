# TrekBuddy Guide Text Generator


### 프로젝트 소개
<a href=https://github.com/Yang-ga-hyeon/TrekBuddy>한국어 텍스트 모델 기반 여행 가이드 어플리케이션 TrekBuddy</a>의 가이드 텍스트 생성 모델입니다.

## ⏲개발 기간
* 2023.08.01 ~ 2023.11.10

### 🧑‍🤝‍🧑멤버
- 조수빈: Project Leader, ML Data Collection & Preprocess, App Develop, Database Management, 가이드 페이지, 검색 페이지, 스크랩 페이지
- 양가현: Main App Developer, Database Management, 로그인 페이지, 회원가입 페이지, 가이드 페이지, 가이드 상세 페이지
- 김윤선: Data Preprocess & Model Finetuning, App Develop, Database Management, 가이드 페이지, 개인정보 수정 페이지, 리뷰 페이지, 로그 페이지

### 💻개발 환경
- **Pretrained-model** : 한국어 Bart 모델 오픈 소스 (https://github.com/SKT-AI/KoBART) <img src="https://img.shields.io/badge/google colab-F9AB00?style=for-the-badge&logo=google colab&logoColor=white">
- **Training data** : AI hub 요약문 및 레포트 생성 데이터 (https://aihub.or.kr/aihubdata/data/view.do?currMenu=115&topMenu=100&aihubDataSe=realm&dataSetSn=582) <img width="100" height="20" src="https://github.com/Yang-ga-hyeon/TrekBuddy/assets/111068038/f4264824-e151-4a5b-94ea-c257113cf0b8">
- **Deep Learning Framework** :<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"> <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
- **TTS** : NAVER CLOVA <img width="50" height="50" src="https://github.com/Yang-ga-hyeon/TrekBuddy/assets/111068038/9af716e9-dd8c-411c-bffb-7ab7c03a04b3">
- **Database** : <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=Firebase&logoColor=white">

## 아키텍처
<img width="1348" alt="아키텍처-기술" src="https://github.com/Yang-ga-hyeon/TrekBuddy/assets/111068038/3fe28e87-8341-44bc-86b0-77526c2b430d">
  
  *Selenium이 아닌 Scrapy로 변경


## 설치방법 How to Build
- Directory 구조
.
│
├──data     //train&test data
│  ├── train.tsv
│  └── test.tsv
├──checkpoint
│  └──model_chp    //checkpoint
│      └──epoch=49-val_loss=0.000.ckpt
│      └──epoch=74-val_loss=0.000.ckpt
│      └──epoch=99-val_loss=0.000.ckpt
├──wandb    //코드 실행시 생성
│  └──run-20230917_132222-kype9vho
│      └──files
│      └──logs
│      └──tmp
│      └──run-kype9vho.wandb
│  └──run-20230917_132442-n2sehfxv
├──.gitignore //SKT KoBART open source
├──.gitmodules
├──requirements.txt
├──LICENSE
├──dataset.py
├──download_binary.py
├──get_model_binary.py
├──infer.py
├──model.py
├──train.py
└──rouge_metric.py


## 사용방법 How to Test
- 

## Data Description
-


## Open Source
-



