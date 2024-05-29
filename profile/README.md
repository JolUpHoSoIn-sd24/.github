

<div align=center>
	<img src="https://github.com/JolUpHoSoIn-sd24/.github/assets/62142245/459839e8-823b-4d6e-8cce-4a970b85a81e" width=600>
</div>
<div align=center>
	<h3>📚 Tech Stack 📚</h3>
	<p>✨ Platforms & Languages ✨</p>
</div>
<div align="center">
	<img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=Flutter&logoColor=white " />
	<img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=Dart&logoColor=white " />
	<br/>
    	<img src="https://img.shields.io/badge/java-47A248?style=for-the-badge&logo=java&logoColor=white " />
	<img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white " />
    	<img src="https://img.shields.io/badge/Shell-5391FE?style=for-the-badge&logo=Shell&logoColor=white " />
	<br/>
    	<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white " />
	<img src="https://img.shields.io/badge/Qdrant-DD244D?style=for-the-badge&logoColor=white" />
 	<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white " />
	<br/>
 	<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white " />
  	<img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white " />
	<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&&logo=TensorFlow&logoColor=white" />
    	<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&&logo=OpenCV&logoColor=white" />
	<br/>
	<img src="https://img.shields.io/badge/Google%20Cloud Platform-4285F4?style=for-the-badge&logo=Google%20Cloud&logoColor=white" />
</div>
<br>
<div align=center>
	<p>🛠 Tools 🛠</p>
</div>
<div align=center>
	<img src="https://img.shields.io/badge/intellijidea-2C2255?style=for-the-badge&logo=intellijidea&logoColor=white" />
	<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" />
	<br/>
	<img src="https://img.shields.io/badge/androidstudio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white " />
	<img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white " />
	<img src="https://img.shields.io/badge/Xcode-007ACC?style=for-the-badge&logo=Xcode&logoColor=white" />
 	<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white" />
	<br/>
 	<img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white" />
  	<img src="https://img.shields.io/badge/slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" />
</div>
<br>

## 프로젝트 개요
테니스 파트너 & 코트 매칭 및 무인심판 서비스
<br/>
AI 기반 개인 맞춤형 테니스 플레이어 및 테니스 코트 매칭 기능, 비전 AI 기반 라인콜링 및 오토 스코어링 기능을 제공하는 올인원 테니스 매칭 플랫폼 입니다.
<br/>
<br/>
<div align="center">
	<img src="https://github.com/JolUpHoSoIn-sd24/.github/assets/62142245/91447a54-5d6e-403f-af39-710571fa68d6" width="1000">
</div>
<br/>

## 프로젝트 주요 기능
<div align="center">
	<img width="1000" alt="image" src="https://github.com/JolUpHoSoIn-sd24/.github/assets/62142245/e8a2e85b-c680-42ae-843f-86e9bba08e4c">
</div>

테니스 재미쓰는은 두 가지 메인 기능을 통해 테니스 플레이어에게 편의 기능을 제공합니다.

**1. 사용자 정보 기반 플레이어, 테니스 코트 매칭**
  - 사용자가 사전에 매칭에 필요한 정보를 등록합니다. 현재 위치, 이동 가능 거리, 희망 시간,경기 목적, 진지한 정도, 사용자의 테니스 실력(NTRP)와 같은 주요 feature들을 임베딩하여 저장합니다.
  - 임베딩된 각 유저들의 벡터들을 VectorDB에 담은 후, distance 기반 top K를 추천합니다.
  - 사용자가 등록한 정보에 기반하여, 경기 일시-테니스 코트-상대 플레이어 3가지가 쌍으로 연결되어 한 번에 추천됩니다.
  - 추천된 경기는 카드 UI로 제공되며, 사용자는 왼쪽(YES) 또는 오른쪽(NO)으로 스와이프하여 경기 의사를 결정할 수 있습니다.
  - 서로 매치된 유저들은 해당하는 테니스 코트의 이용 요금을 분할결제 후, 경기를 진행하게 됩니다.
    
  
**2. AI 라인콜링 및 오토 스코어링**
  - 사용자는 스마트폰 카메라를 이용하여 테니스 경기를 실시간 스트리밍합니다. AI 모델이 코트 규격을 인식하고, 테니스 공을 실시간으로 추적하여 자동으로 실점 여부를 판독합니다.
  - 득점 여부를 음성으로 안내하여, 경기자들은 라인콜링에 대한 분쟁 없이 테니스 경기를 진행할 수 있습니다.
<br/>

## 프로젝트 상세정보
2024-1학기 아주대학교 SW캡스톤디자인 과목에서 JolUpHoSoIn 팀이 2024년 3월부터 6월까지 진행하였습니다.

아래의 링크에서 보다 자세하게 프로젝트를 확인할 수 있습니다.
- softcon: https://softcon.ajou.ac.kr/works/works.asp?uid=1801 (아주대학교 소프트콘)
<br/>
<img width="90%" src="https://github.com/JolUpHoSoIn-sd24/.github/assets/62142245/fbcd1843-6f56-4697-b013-3cd28487ed05">
<br/>
<br/>

## 프로젝트 레포지토리
<br/>
AI, 프론트엔드, 백엔드 레포지토리를 아래 링크에서 확인하실 수 있습니다.
<br/>

- main: https://github.com/JolUpHoSoIn-sd24
- AI: https://github.com/JolUpHoSoIn-sd24/tennisfunai
- frontend: https://github.com/JolUpHoSoIn-sd24/tennisfunapp
- backend: https://github.com/JolUpHoSoIn-sd24/tennisfunserver

<br/>

### 팀 소개

|이름|역할|email|github|
|---|---|---|---|
|송정우|AI 개발|jws5346@ajou.ac.kr|https://github.com/KyleJSong|
|김관주|백엔드 개발|kkj6235@ajou.ac.kr|https://github.com/kkj6235|
|한승훈|백엔드 개발|hsh1223@ajou.ac.kr|https://github.com/shhan730|
|김동령|프론트엔드 개발|insoyafear@ajou.ac.kr|https://github.com/Dolmaeng|
|김영찬|프론트엔드 개발|ych601@ajou.ac.kr|https://github.com/rladudcks|

<br/>
