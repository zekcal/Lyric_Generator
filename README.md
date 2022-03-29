# AI_07_Section_4_Project
#### 1. 코드스테이츠 AI/빅 데이터 부트캠프 섹션 4 프로젝트입니다.  
코드 스테이츠 AI/빅 데이터 부트캠프에서 약 5일간(22.01.07 ~ 22.01.12) 진행한 프로젝트입니다.

#### 2. 이 프로젝트의 주제는 '딥 러닝으로 작사가 실종 사태 방지하기'입니다.  
'만약 작사가가 사라져 녹음을 당장 해야하는데 가사가 없다면 이를 딥 러닝을 통해 해결할 수 있지 않을까?'라는 상황 설정을 하고 진행한 프로젝트입니다.

#### 3. 이 프로젝트의 목표는 '자연어 생성을 활용한 결과물을 만들어보기'입니다.  
딥 러닝 과정에서 자연어 생성 부분이 흥미로웠고, 작사 또한 관심을 둔 부분이기 때문에 이 둘을 동시에 시도해보고자 했습니다.

#### 4. 프로젝트의 진행 순서는 크게 '데이터(가사) 크롤링 - 토큰화 - 딥 러닝을 통한 학습 - 파인 튜닝을 통한 학습 - ainize를 활용한 학습'입니다.  
구체적인 과정은 각 ipynb 파일을 참조해주시면 감사하겠습니다. 추가적으로, 4_fine_tuning.ipynb는 Google Colab, 다른 파일은 로컬의 Conda 가상환경에서 진행되었습니다. Konlpy, gensim, transformers, gluonnlp, sentencepieces, JPype1 등은 pip를 통한 설치를 진행하였습니다.

#### 5. 이 프로젝트를 진행하며 느낀점은 다음과 같습니다.  
  1. 결과물의 만족도가 낮음  
    - 가수가 발매한 음악이 적으면 퀄리티도 낮아질 수밖에 없으며, 또한 이 사실을 감안하더라도 정말 가사다운 글이라 할 수 있을지 모호함.
  2. 딥 러닝의 특징 : 모호한 진행  
    - 라이브러리의 활용, 구글링의 역할 등이 중요했고, 딥 러닝 특성 상 내부 과정까지 완전히 이해할 수가 없었고 답답함을 종종 느낌.
  3. 흥미로움  
    - 1.에도 불구하고, 구체적인 결과물이 나오고, 흥미로운 주제가 섞인 프로젝트를 진행하니 어려웠음에도 더 즐거움을 느낌.
