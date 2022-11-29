![header](https://capsule-render.vercel.app/api?type=slice&color=auto&height=200&section=header&text=Mini-Project2&fontSize=70fontAlign=70&fontAlignY=35&rotate=13&desc=자연어%20분석&descSize=15)

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Flookinsight%2Fhit-counter&count_bg=%237CC49E&title_bg=%2330779C&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

<div align=right><h1>📚 STACKS</h1></div>
<div align=right> 
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">
  <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=for-the-badge&logo=Visual Studio Code&logoColor=white">
  <img src="https://img.shields.io/badge/Amazon-FF9900?style=for-the-badge&logo=Amazon&logoColor=white">
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> 
  <img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> 
  <br>
  </div>
  <br>
  
<div align=center><h1> 💻구로 Playdata 빅데이터 분석과정 </h1></div>
<div align=center><h2> 📊Mini-Project  : 머신러닝, 딥러닝 분석기법을 활용한 데이터 분석 및 시각화 </h2></div>
<div align=center><h3> 📆기간: 2022.11월 25일(금) ~ 2022.11.28(월)</h3></div>
<div align=center><h3> 🧑5️조: 최준열, 남태현, 김가람, 이승민</h3></div>
<br>

<h3> 🌦미니 프로젝트 진행의 역할 분담에 대한 고민 </h3>

**🌧고민**: 

- 미니 프로젝트를 진행하게 되면 팀이 구성되고 팀원들과 협업의 방식으로 프로젝트를 진행하게 됩니다. 
  하지만, 현재 시점에서 팀원마다 배움의 정도, 배운 내용의 범위와 이해의 수준이 다 다르기 때문에 특정 개인의 주도로 프로젝트가 진행이 될 가능성이 높고 주도하는 팀원에게 프로젝트 협업의 비중 자체가 집중 될 가능성이 높습니다. 그런데 그렇게 되면 실무자가 아닌 배우는 입장에서는 프로젝트를 통해서 배우고 발전하는 기회를 놓치는 결과가 나올 가능성도 높다는 문제의식이 생겼습니다. 
<br> 

   **그러다 보니, ✏**
   
- 이번 프로젝트를 진행하는 것에 있어서 프로젝트를 완성하는 것도 중요하지만, 프로젝트를 통해서 몰랐던 부분에 대한 공부를 하고 각자 관심 있고 시도해 보고 싶은 분석을 실제로 직접 몸으로 익혀보는 것도 중요하다는 생각을 하게 되었습니다. 
<br>

   **그래서 우리 5조는, 🌥**
 
  프로젝트 기간을 분할해서 사용해 보기로 했습니다.
  
<br>
<br>

* 프로젝트 방향성: 자연어 처리를 기반으로 한 머신러닝, 딥러닝 분석 하기

* 1차 개인 프로젝트 Develop: 머신러닝, 딥러닝의 분석 기법 중에서 자연어 처리를 통한 분석 기법을 각자 익혀가며 develop 해보기

   > 기간: 11.25 ~ 26일 2일
     
   > 목표: 26일까지 팀원 스스로 개인 프로젝트 진행하기
    
           🚩 26일 저녁. 팀으로써 완성시킬 프로젝트 하나를 정하고 팀프로젝트로 결과를 낸다
     
     
   > 진행 내용
   
      - 자연어 처리에 대한 공부 
      
      - 도서 추천 서비스 구현해보기 
      
      - 언어 데이터를 기반으로 챗봇 시스템 구현
      
      - 토이 챗봇(특정 목적 중신) 구현해보기 
      
      - Docker, conda 등 가상환경 시도해보기
      
      - Git 을 통한 버전관리 익숙해지기, Github를 통한 프로젝트 관리 익숙해지기 
  <br>
      
   > 시행착오 및 문제점:
   
      - 챗봇 시스템 구현에 대한 참고 자료의 기한이 오래 지나다 보니 라이브러리 버전 문제, 코드 변경 문제, 
        시스템 환경 적용에 대한 오류 문제 등 많이 발생
      
      - 언어기반, 자연어 기반의 분석을 진행하려면 많은 양질의 데이터가 필요. 
        하지만, 원데이터의 벡터 변환, 인코딩등 필수적으로 거치는 처리를 하면 자료의 크기가 무한정 커짐 
        
      - 자연어 분석에 필요한 전처리, 변환 등을 할 때, 
        언어별 특성에 맞는 처리를 해줘야 하기 때문에 적용되는 기법도 다르고 분석 시간이 매우 오래 걸림(특히 한국어)
      
      - 배경이 되는 다양한 이론이나 기법등에 대한 이해가 기반이 되어야 하는데 여러 모로 이해하는데 어려움이 컸음
  <br>
  
   
   **그렇지만 우리 5조는, 🌤**
      
      각자 자료를 찾아보며 문제나 시행 착오를 해결해 나가고, 팀원끼리 도움을 주고 받으면서 발전시켜 나갈 수 있었음
  <br>     
 
  
 * 팀 프로젝트 완성: 각자 개인이 진행한 프로젝트 중에서 팀으로써 완성해 볼 수 있는 프로젝트를 협의를 통해 선정함
 
    > 기간: 11.25(개인 프로젝트 포함) ~ 11. 29(오전)
    
    > 주제: 아마존 도서 목록 데이터를 통한 유사 도서 추천 모델 구현
    
    > 선정이유: 개인 프로젝트 중에서 진행이 가장 잘 됐으면서도 프로젝트 기간 내 유의미한 결과를 도출할 수 있는 가능성이 높다고 판단

    > 목표: 도서 제목을 입력하면 해당 책과 가장 유사한 도서목록 5개를 추천해주는 모델 구현

    > 분석 기법: TF-IDF, 코사인 유사도, Word2vec 등
    
    > 시각화 표현: Streamlit 연동을 통한 시각화 구현 

    > 시행착오 및 문제점: 
    
      1. 방대한 데이터 양: 원 데이터(컬럼수: 10개, 도서량: 12만권 이상, 약 1.5Gb) 
         - 원 데이터 크기도 컸지만, 벡터 변환, 인코딩등등 필요한 처리 과정을 거쳤을 때 무한 정 커진 데이터로 인한 시스템 과부화 및 오래 걸리는 시간 
         
         📌 해결을 위한 아이디어: 분석데이터 크기 제한을 통해 최대한 시스템 과부화를 방지. 
         
         📌 결과 도달을 위한 불가피한 선택 - 프로젝트 결과 도출을 위한 버릴 건 버리기
      <br>    
         
      2. 시스템 사양의 문제: CPU, RAM, GPU 등의 낮은 사양으로 인해 잦은 시스템 오류 및 과부하에 따른 시스템 다운
      
         📌 당장 시스템을 바꿀 수 있지 않는 한 데이터의 양을 조절하는 방법 외에는 현실적으로 해결 할 수 없었음
         
         📌 서버나 SQL 등을 통한 데이터 관리의 중요성을 깨닫는 계기
      <br>     
         
      3. 분석 기법의 배경 이론 및 분석 진행 과정에 대한 이해의 어려움 
       
         📌 수학은 고등학교 졸업하면 전공이 아닌 이상 쓸 일이 있나?
         
         📌 수학의 배경이 튼튼하지 않으면 이 세상이 왜 이렇게 돌아가는지 이해하기 어려운 세상이 되어 가고 있음
        
         📌 Digital - 숫자로 이루어지는 세상
      <br>    
         
      4. 언어 데이터의 전처리 및 분석에 사용한 코드 적용의 어려움
      
         📌 구글링, 팀원 간의 토의, 참고 도서등을 통해 수정 보완
         
  <br>       
  <br>       
     
   **결국 우리는, 📍**
      
   [도서 제목 유사도 기반 추천 모델 - Stremlit 구현](https://nammtaeehyeonn-reco-recommend-utwo4b.streamlit.app/)
