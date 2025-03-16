# 공지
해당 코드북은 **2025년 3월 25일** 이후 일괄 업로드 예정입니다.

---
# 닥터, 코드를 만나다

<div align="center">
  <img src="https://via.placeholder.com/200x200" alt="닥터, 코드를 만나다 로고">
  <p>인공지능과 코딩의 세계로 떠나는 여행</p>
  
  [![GitHub stars](https://img.shields.io/github/stars/yourusername/dr-meets-code.svg?style=social&label=Star)](https://github.com/yourusername/dr-meets-code)
  [![GitHub forks](https://img.shields.io/github/forks/yourusername/dr-meets-code.svg?style=social&label=Fork)](https://github.com/yourusername/dr-meets-code/fork)
  [![GitHub license](https://img.shields.io/github/license/yourusername/dr-meets-code.svg)](https://github.com/yourusername/dr-meets-code/blob/main/LICENSE)
  [![Twitter](https://img.shields.io/twitter/url/https/github.com/yourusername/dr-meets-code.svg?style=social)](https://twitter.com/intent/tweet?text=Check%20out%20this%20amazing%20AI%20coding%20workbook:&url=https%3A%2F%2Fgithub.com%2Fyourusername%2Fdr-meets-code)
</div>

## 📖 소개

'닥터, 코드를 만나다'는 인공지능 코딩의 세계로 여러분을 초대합니다. 이 워크북은 AI와 프로그래밍의 기초부터 고급 주제까지 다루며, 모든 예제는 Google Colab에서 바로 실행할 수 있도록 제공됩니다.

이 저장소는 책의 모든 코드 예제와 추가 자료를 포함하고 있으며, 독자들이 실시간으로 코드를 실행하고 수정하며 배울 수 있는 환경을 제공합니다.

## 🚀 시작하기

### 사전 요구사항

* Google 계정 (Colab 사용을 위해 필요)
* 기본적인 프로그래밍 지식 (권장사항)
* 호기심과 학습에 대한 열정 😊

### Google Colab 사용 방법

1. 각 챕터 폴더 내의 `.ipynb` 파일을 클릭합니다.
2. "Open in Colab" 버튼을 클릭합니다.
3. 파일이 Google Colab에서 열립니다.
4. 코드 셀을 실행하려면 셀 왼쪽의 ▶️ 버튼을 클릭하거나 `Shift+Enter`를 누릅니다.

<div align="center">
  <img src="https://via.placeholder.com/600x300" alt="Colab 사용 방법">
  <p>Google Colab 인터페이스 예시</p>
</div>

### 로컬에서 실행하기
* 사전 요구사항: [git](Installation_guide_git), [python](Installation_guide_python) 설치
* Git terminal 실행
```bash
# 저장소 복제
git clone https://github.com/DoctorCode-InhaGaime/DoctorCode-Workbook.git

# 챕터별 디렉토리 이동 (ex: Chapter 1)
cd Chapter1

# (선택사항) 가상 환경 생성 및 활성화
python -m venv venv
source venv/bin/activate  # Windows에서는: venv\Scripts\activate

# 필요한 패키지 설치
pip install -r requirements.txt

# Jupyter 노트북 실행
jupyter notebook
```
* 다른 Chapter로 넘어가기 전! 꼭 가상환경 (venv, pipenv 등)을 deactivate 시켜주세요!
```
deactivate
```
What_is_AI.i
## 📚 목차

저장소는 책의 챕터별로 구성되어 있습니다:

### [Chapter 1: AI와 함께하는 미래의 의사들: 의대생과 전공의를 위한 필수 가이드](./Chapter1/)
- [1.1 의료 AI 입문: 파이썬 설치와 Google Colab 활용 가이드](./Chapter1/1.1_Basic_Guide.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter1/1.1_What_is_AI.ipynb)
- [1.2 의학 연구자를 위한 AI 개발 환경 설정 가이드](./Chapter1/1.2_Environment_Setup.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter1/1.2_Environment_Setup.ipynb)
- [1.3 의학 연구자를 위한 AI 개발 환경 설정 가이드](./Chapter1/1.2_Environment_Setup.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter1/1.2_Environment_Setup.ipynb)
- [1.4 의학 연구자를 위한 AI 개발 환경 설정 가이드](./Chapter1/1.2_Environment_Setup.ipynb)
- [1.5 의학 연구자를 위한 AI 개발 환경 설정 가이드](./Chapter1/1.2_Environment_Setup.ipynb)

### [Chapter 2: 임상 연구와 데이터 분석의 열쇠, 파이썬 알아보기](./Chapter2/)
- [2.1 의료 정보 처리를 위한 파이썬 기초: 데이터 타입과 구조](./Chapter2/2.1_Data_Analysis_Basics.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.1_Data_Analysis_Basics.ipynb)
- [2.2 의학 공식의 새로운 접근: 파이썬으로 Anion Gap 이해하기](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)
- [2.3 파이썬으로 구현하는 고칼륨혈증 감별 진단: TTKG에서 알고리즘까지](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)
- [2.4 파이썬으로 구현하는 쿠싱증후군 진단 알고리즘: 복잡한 의학 지식을 코드로 정리하기](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)
- [2.5 파이썬으로 구현하는 CHA2DS2-VASc 점수 계산기: for문과 while문의 활용](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)
- [2.6 파이썬 클래스와 모듈로 구현하는 고칼륨혈증 관리 시스템](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)
- [2.7 의사의 새로운 파트너, AI: 파이썬으로 시작하는 의료 혁신의 여정](./Chapter2/2.2_Data_Visualization.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter2/2.2_Data_Visualization.ipynb)

### [Chapter 3: 의료 AI의 모든것: 기초 개념부터 최신 기술까지](./Chapter3/)
- [3.1 의료 AI 개발의 7단계 파이프라인: 데이터 마이닝부터 모델 배포까지](./Chapter3/3.1_AI_Development_Pipeline.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.1_AI_Development_Pipeline.ipynb)
- [3.2 의료 AI의 기초: 머신 러닝과 딥 러닝의 핵심 개념 이해하기](./Chapter3/3.2_ML_DL_Core_Concepts.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.2_ML_DL_Core_Concepts.ipynb)
- [3.3 의료 AI 개발의 필수 도구: 주요 프레임워크 총정리](./Chapter3/3.3_Essential_Frameworks.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.3_Essential_Frameworks.ipynb)
- [3.4 의료 현장의 머신 러닝: 주요 기법과 임상 응용](./Chapter3/3.4_ML_Clinical_Applications.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.4_ML_Clinical_Applications.ipynb)
- [3.5 의료 혁신을 이끄는 딥 러닝: 주요 기법과 임상 응용](./Chapter3/3.5_DL_Clinical_Applications.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.5_DL_Clinical_Applications.ipynb)
- [3.6 의료 AI의 최신 트렌드: 첨단 기술과 도구들](./Chapter3/3.6_Latest_AI_Trends.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter3/3.6_Latest_AI_Trends.ipynb)

### [Chapter 4: 의료 인공지능 개발의 출발선: 환경 구축부터 리소스 탐색까지](./Chapter4/)
- [4.1 의대생과 전공의를 위한 의료 AI 코드 탐험: Github, Hugging Face, Papers with Code 활용법](./Chapter4/4.1_AI_Code_Exploration.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter4/4.1_AI_Code_Exploration.ipynb)
- [4.2 의대생과 전공의를 위한 의료 AI 데이터셋 가이드](./Chapter4/4.2_Medical_AI_Datasets.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter4/4.2_Medical_AI_Datasets.ipynb)
- [4.3 의료 인공지능 개발의 게임 체인저: LLM의 활용과 가능성](./Chapter4/4.3_LLM_Applications.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter4/4.3_LLM_Applications.ipynb)

### [Chapter 5: 영상 이미지 분석을 위한 딥러닝](./Chapter5/)
- [5.1 MedMNIST와 MONAI: 의료 AI 연구의 효율적인 시작점](./Chapter5/5.1_MedMNIST_MONAI.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.1_MedMNIST_MONAI.ipynb)
- [5.2 AI로 풀어가는 chest X-ray 판독의 도전](./Chapter5/5.2_Chest_Xray_AI.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.2_Chest_Xray_AI.ipynb)
- [5.3 Complete Anatomy를 넘어서: AI로 구현하는 개인화된 3D 인체 모델](./Chapter5/5.3_Personalized_3D_Models.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.3_Personalized_3D_Models.ipynb)
- [5.4 근육을 읽는 AI의 눈: 정형외과 수술의 정밀한 평가를 위하여](./Chapter5/5.4_Orthopedic_Surgery_AI.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.4_Orthopedic_Surgery_AI.ipynb)
- [5.5 30초의 압박에서 자동화된 분석까지: 의학 교육과 기술의 만남](./Chapter5/5.5_Automated_Medical_Analysis.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.5_Automated_Medical_Analysis.ipynb)
- [5.6 개원 의사의 필수 도구: 초음파와 AI의 시너지](./Chapter5/5.6_Ultrasound_AI_Synergy.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.6_Ultrasound_AI_Synergy.ipynb)
- [5.7 MediaPipe BlazePose: 의료 현장의 움직임 분석을 혁신하는 실시간 자세 추정 기술](./Chapter5/5.7_MediaPipe_BlazePose.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter5/5.7_MediaPipe_BlazePose.ipynb)

### [Chapter 6: 시계열 자료 분석을 위한 딥러닝](./Chapter6/)
- [6.1 아침 7시의 악몽 탈출하기: 딥 러닝으로 혈당 관리 혁신](./Chapter6/6.1_Glucose_Management_AI.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter6/6.1_Glucose_Management_AI.ipynb)
- [6.2 AI의 청진기: 딥 러닝이 읽어내는 심장의 리듬](./Chapter6/6.2_Heart_Rhythm_AI.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter6/6.2_Heart_Rhythm_AI.ipynb)

### [Chapter 7: 생성형 AI 및 자연어 처리](./Chapter7/)
- [7.1 의료 기록의 새로운 패러다임: LLaMA 모델과 AI의 만남](./Chapter7/7.1_LLaMA_Medical_Records.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter7/7.1_LLaMA_Medical_Records.ipynb)
- [7.2 AI로 진화하는 의대 족보: GPT-4 스마트 학습 혁명](./Chapter7/7.2_GPT4_Medical_Education.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter7/7.2_GPT4_Medical_Education.ipynb)
  
### [Chapter 8: Medical GitHub: 미래 의사를 위한 AI 플레이그라운드](./Chapter8/)
- [8.1 GitHub 저장소 생성](./Chapter8/8.1_Creating_GitHub_Repository.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.1_Creating_GitHub_Repository.ipynb)
- [8.2 로컬 환경 설정](./Chapter8/8.2_Local_Environment_Setup.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.2_Local_Environment_Setup.ipynb)
- [8.3 프로젝트 구조화](./Chapter8/8.3_Project_Structure.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.3_Project_Structure.ipynb)
- [8.4 README 작성](./Chapter8/8.4_Writing_README.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.4_Writing_README.ipynb)
- [8.5 의료 데이터 처리 시 고려사항](./Chapter8/8.5_Medical_Data_Considerations.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.5_Medical_Data_Considerations.ipynb)
- [8.6 GitHub에서 SAM 활용하기](./Chapter8/8.6_Using_SAM_GitHub.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Chapter8/8.6_Using_SAM_GitHub.ipynb)

### [부록: 심화 학습](./Appendix/)
- [A.1 강화학습](./Appendix/A.1_Reinforcement_Learning.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Appendix/A.1_Reinforcement_Learning.ipynb)
- [A.2 프로젝트 아이디어](./Appendix/A.2_Project_Ideas.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/dr-meets-code/blob/main/Appendix/A.2_Project_Ideas.ipynb)

## 🛠️ 기술 스택

이 프로젝트는 다음 기술을 활용합니다:

- ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) Python 3.7+
- ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) TensorFlow 2.x
- ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) PyTorch
- ![Scikit-learn](https://img.shields.io/badge/ScikitLearn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) Scikit-learn
- ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) Pandas
- ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) NumPy
- ![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square) Matplotlib
- ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white) Jupyter/Colab

## 📝 라이센스

이 프로젝트는 MIT 라이센스 하에 배포됩니다. 자세한 내용은 [LICENSE](./LICENSE) 파일을 참조하세요.

## 📞 연락처

저자: 박현우, 유준일, 김현수
깃허브 관리자: 김현수 (E-mail: inhagaime@gmail.com)

프로젝트 링크: [https://github.com/DoctorCode-InhaGaime/DoctorCode-Workbook](https://github.com/DoctorCode-InhaGaime/DoctorCode-Workbook)

## 🙏 감사의 말

* Google Colab 팀에게 무료 GPU 환경 제공에 감사드립니다.
* We thank the Google Colab team for providing the free GPU environment.
* 모든 오픈 소스 라이브러리 개발자들에게 감사드립니다.
* We thank all the developers of open-source libraries.
* 이 프로젝트에 영감을 준 모든 교육자들에게 감사드립니다.
* We thank all the educators who inspired this project.
* 피드백과 지원을 아끼지 않은 독자 여러분께 감사드립니다.
* We thank the readers for their invaluable feedback and support.

---

<div align="center">
  <p>❤️ 코딩을 즐기세요! ❤️</p>
  <p>Made with passion in South Korea 🇰🇷</p>
</div>
