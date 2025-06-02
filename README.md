# 👋 안녕하세요, 백엔드 개발자 김보현입니다.

이용자가 사용하기 편한 사이트를 개발하는 백엔드 개발자입니다. 
내가 짠 코드를 스스로 의심하고 질문하며 백엔드 뿐만 아닌 프론트 개발도 가능한 풀스택 개발자를 목표로 합니다.


---


## 💻 **사용 기술(Tech Stack)**
### **프로그래밍 언어**
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=for-the-badge&logo=java&logoColor=white)

### **프레임워크 및 라이브러리**
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Mysql](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
<img src="https://img.shields.io/badge/fastapi-%23009688.svg?&style=for-the-badge&logo=fastapi&logoColor=white" />

### **도구**
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![android studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=eclipse&logoColor=white)



---

# 📂 **대표 프로젝트**

---

## 🎬 AI_Kpop_Camera_System (SAMURAI AI 기반 K-pop 자동 카메라 시스템)
📆 개발 기간: 2025.05.26 – 2024.06.02

🧠 프로젝트 개요
AI_Kpop_Camera_System은 SAMURAI AI 객체 추적 기술을 활용하여 K-pop 공연 영상에서 각 멤버를 자동으로 추적하고, 방송급 품질의 개인 직캠을 생성하는 영상 처리 시스템입니다.
사용자가 마우스로 간단히 멤버를 선택하면, AI가 자동으로 전체 영상에서 해당 멤버를 추적하여 부드럽고 안정적인 개인 직캠을 생성합니다.
6가지 색상 슬롯 시스템으로 최대 6명의 멤버를 동시에 처리할 수 있으며, 가우시안 스무딩 알고리즘을 통해 전문적인 카메라 워크를 구현합니다.
마우스 드래그로 직관적인 멤버 선택이 가능합니다.

🔍 주요 기여
 - 🎥 카메라 워크: 가우시안 스무딩으로 떨림 없는 부드러운 움직임 구현
 - 📹 이중 출력 시스템: 개인 직캠 (400×750)과 전체 뷰 영상 동시 생성
 - 📊 과학적 분석: 움직임 패턴 분석 및 누락 프레임 자동 보간

🧰 기술 스택
Python, OpenCV, SAMURAI AI, NumPy, SciPy, Pillow, Gaussian Filtering

📎 자세한 정보
[Food_Find GitHub 바로가기](https://github.com/KBohyeon/AI-Powered-K-pop-Camera-System)


---
## 🔍 Food_Find (식당 찾기 사이트)
📆 개발 기간: 2025.04 – 2025.05

🧠 프로젝트 개요  
Food_Find는 식당을 선택하기 힘들 때 사용하는 웹 사이트입니다.
불필요한 정보 없이 최소한의 정보를 사용하여 제공합니다.
회원가입 및 로그인, 신규 식당 등록, 리뷰(글씨, 사진, 평점)작성 및 수정, 검색이 가능하며,
검색시 사용자와의 거리를 측정하여 가까운 순으로 보여 가까운 식당을 보다 빠르게 선택 할 수 있게 도움을 줍니다.
일반 사용자는 식당 예약 및 취소가 가능하며 사장님의 경우 예약한 손님들의 예약을 관리 할 수 있습니다.

🔍 주요 기여
- 🖼️ 사이트 UI/UX 디자인
- 💾 DB 설계 및 구현
- 🗂️ 데이터 처리 및 저장
- 🧠 식당 예약 Redis 분산락 구현 
- 📍 사용자와 식당의 거리 계산

🧰 기술 스택   
- Java, JavaScript, HTML, CSS, Spring Boot, Mysql, Redis
  
📎 자세한 정보  
[Food_Find GitHub 바로가기](https://github.com/KBohyeon/Food_Find)

---

## 🔍 Naver_Store_Scraping (네이버 스토어 스크래핑 도구)
📆 개발 기간: 2025.05.22 – 2025.05.26

🧠 프로젝트 개요  
Naver_Shopping_Scraping은 네이버 스토어에서 상품 정보를 자동으로 수집하는 웹 스크래핑 도구입니다.</br>
사용자가 원하는 만큼의 데이터를 수집하여 CSV 파일로 저장하며, 실시간으로 스크래핑 과정을 확인할 수 있습니다.</br>
제품명, 가격, 평점, 리뷰 개수 등의 핵심 정보를 효율적으로 수집하여 데이터 분석 및 가격 비교에 활용할 수 있습니다.</br>
브라우저 창을 통해 스크롤 과정을 시각적으로 확인하면서 터미널에서는 실시간으로 수집된 상품 정보를 상세히 볼 수 있습니다.

🔍 주요 기여
- 🖥️ 시각적 스크래핑: 브라우저 창에서 스크롤 과정 실시간 확인
- 📊 실시간 데이터 출력: 터미널에서 수집된 상품 정보 즉시 표시
- 🔄 다양한 수집 모드: 커스텀 스크롤, 최대 스크롤 옵션
- 💾 CSV 자동 저장: 수집된 데이터를 구조화된 형태로 저장
- 📈 통계 정보 제공: 평균 가격, 평점 등 분석 정보 자동 계산

🧰 기술 스택   
- Python, Selenium, Pandas
  
📎 자세한 정보  
[Naver_Store_Scraping GitHub 바로가기](https://github.com/KBohyeon/scraping)

---

## 🔍 Food_Check_App (음식 객체 인식)

🧠 프로젝트 개요  
Food_check_App은 어플에 접속 후 학습된 yolov5 모델을 이용하여 사진을 업로드시 음식의 이름과 칼로리를 표시해 줍니다.

🔍 주요 기여
- 🧠 PyTorch기반 Yolov5 모델 학습
- 💾 이미지 처리 및 어플과 FastAPI 연동

🧰 기술 스택   
- Java, Python, PHP, PyTorch, YOLOv5, FastApi
  
📎 자세한 정보  
[Yolov5_Food_Check GitHub 바로가기](https://github.com/KBohyeon/Yolov5_Food_Check)

---

## 📱 SyncBook(주소록 자동 등록 어플)
📆 개발 기간: 2025.02 – 2025.02

🧠 프로젝트 개요  
매학기 마다 방과후 학생들 180 ~ 200명을 일일이 전화번호를 입력하시는 부모님을 위한 어플입니다.
사이트에서 엑셀 파일을 업로드 후 어플에 있는 버튼 클릭시 자동으로 주소록이 저장, 수정됩니다.

🔍 주요 기여
- 💾 DB 설계 및 구현
- 🗂️ 데이터 처리 및 저장을 위한 사이트 개발
- 📱 휴대폰, 어플, 데이터베이스 연동 및 저장 

🧰 기술 스택   
- Java, PHP, Android Studio, Mysql, Apache
  
📎 자세한 정보  
[address_book GitHub 바로가기](https://github.com/KBohyeon/Address-Book-Management-App)

---

## 🤖 KU_Pepper (로봇 제어 프로젝트)
📆 개발 기간: 2023.09 – 2024.06

🧠 프로젝트 개요  
KU_Pepper는 경남대학교 컴퓨터공학부 졸업작품에서 진행된 프로젝트로,  
휴머노이드 로봇 Pepper를 제어하여 대화형 서비스를 통해 원하는 위치로 안내하며, 자연스러운 몸 동작을 구현하였습니다.  
학생, 방문자 등 사람과 상호작용하는 로봇 서비스 시나리오를 직접 개발하고 시연하였습니다.

🔍 주요 기여
- 💻 Flask를 사용하여 소켓 서버 개발
- 🗺️ ROS-Gmapping을 사용한 장소 맵핑
- 🤖 Choregraph(모션 생성프로그램)을 통해 Pepper 로봇의 모션 제작
- 🔧 Pepper 장애물 회피 능력 개선 및 위치 안내

🧰 기술 스택  
- Platform: SoftBank Robotics Pepper  
- Language: Python  
- Library/SDK: NAOqi, qiMotion, ROS, Choregraph

📎 자세한 정보  
[KU_Pepper GitHub 바로가기](https://github.com/KBohyeon/kupepper_ros)



## ✨ **관심 분야**

- 어플리케이션 개발
- 웹사이트 개발
