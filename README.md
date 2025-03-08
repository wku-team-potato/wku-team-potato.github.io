# Nutrition Manager

## 🏆 결과
📌 **수상 내역:**  
-  **2024년 캡스톤디자인 경진대회 우수상**  

## 👥 팀원 소개  

| 이름 | 역할 | GitHub |
|------|-----------------------------|--------------------------------|
| **gguip1** | 팀장 / 백엔드 개발 / AI 모델 개발 / 인프라 | [GitHub](https://github.com/gguip1) |
| **aronmin** | 팀원 / 안드로이드 개발 | [GitHub](https://github.com/aronmin) |
| **Lsmini** | 팀원 / UI/UX 디자인 | [GitHub](https://github.com/Lsmini) |

---

## 📌 프로젝트 개요

### 개발 기간  
- **2024.09.12 ~ 2024.12.18**  

### 프로젝트명  
- **Nutrition Manager**  

### 프로젝트 목표  
- **AI 기반 간편한 식단 기록** – 이미지 인식을 활용한 자동 식단 입력  
- **포인트 & 리더보드 시스템** – 사용자 경쟁 요소를 추가하여 지속적인 앱 사용 유도  
- **관리자 기능 제공** – 웹 페이지를 통해 관리자 전용 관리 기능 제공  

<!-- ### 주요 기능  
- **식단 기록** – AI를 활용한 자동 기록 기능 (텍스트, 이미지 입력 지원)  
- **포인트 적립** – 기록 및 목표 달성 시 포인트 획득 가능  
- **리더보드** – 사용자 랭킹 시스템 제공  
- **상점 기능** – 적립한 포인트로 물건 구매 가능  
- **관리자 기능** – 관리자만 접근 가능한 웹 페이지에서 데이터 관리  -->

## 🏗️ 시스템 구성도  
![System Architecture](../assets/images/system_architecture.png) 

## 🛠️ 기술 스택  

### 📌 안드로이드 애플리케이션
<p> <img src="https://img.shields.io/badge/Kotlin-%230095D5.svg?style=for-the-badge&logo=kotlin&logoColor=white"/> <img src="https://img.shields.io/badge/Android-%233DDC84.svg?style=for-the-badge&logo=android&logoColor=white"/> <img src="https://img.shields.io/badge/XML-%23E34F26.svg?style=for-the-badge&logo=xml&logoColor=white"/> </p>

### 📌 백엔드 서버
<p> <img src="https://img.shields.io/badge/Azure-%230078D4.svg?style=for-the-badge&logo=microsoftazure&logoColor=white"/> <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/NGINX-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/Gunicorn-%23449960.svg?style=for-the-badge&logo=gunicorn&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white"/></p>

### 📌 관리자 웹 페이지
<p><img src="https://img.shields.io/badge/Spring%20Boot-%236DB33F.svg?style=for-the-badge&logo=springboot&logoColor=white"/> <img src="https://img.shields.io/badge/Thymeleaf-%23005F0F.svg?style=for-the-badge&logo=thymeleaf&logoColor=white"/> </p>

### 📌 AI 백엔드 서버
<p> <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=for-the-badge&logo=docker&logoColor=white"/> <img src="https://img.shields.io/badge/NGINX-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"/> <img src="https://img.shields.io/badge/Django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"/> <img src="https://img.shields.io/badge/Gunicorn-%23449960.svg?style=for-the-badge&logo=gunicorn&logoColor=white"/> <img src="https://img.shields.io/badge/Ultralytics-%23FF4081.svg?style=for-the-badge&logo=ultralytics&logoColor=white"/> </p>

### 📌 개발 도구
<p> <img src="https://img.shields.io/badge/Android%20Studio-%233DDC84.svg?style=for-the-badge&logo=androidstudio&logoColor=white"/> <img src="https://img.shields.io/badge/IntelliJ%20IDEA-%23000000.svg?style=for-the-badge&logo=intellijidea&logoColor=white"/> <img src="https://img.shields.io/badge/VS%20Code-%23007ACC.svg?style=for-the-badge&logo=visualstudiocode&logoColor=white"/> <img src="https://img.shields.io/badge/MySQL%20Workbench-%234479A1.svg?style=for-the-badge&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Postman-%23FF6C37.svg?style=for-the-badge&logo=postman&logoColor=white"/> <img src="https://img.shields.io/badge/PuTTY-%23000000.svg?style=for-the-badge&logo=windows-terminal&logoColor=white"/> <img src="https://img.shields.io/badge/FileZilla-%23BF0000.svg?style=for-the-badge&logo=filezilla&logoColor=white"/> </p>

## 🔗 프로젝트 구조  

Nutrition Manager는 아래와 같은 서브 프로젝트로 구성됩니다.  

| 구성 요소 | 설명 | GitHub |
|------------|-------------------------------------------------|----------------|
| **안드로이드 애플리케이션** | 사용자가 식단을 기록하고 포인트를 관리할 수 있는 모바일 앱 | [GitHub](https://github.com/wku-team-potato/N.M_FE) |
| **관리자 웹 페이지** | 관리자만 접근 가능한 웹 페이지에서 데이터 관리 | [GitHub](https://github.com/wku-team-potato/N.M_Manager) |
| **백엔드 서버** | 회원 관리(가입, 로그인), 식단 등록, 물건 구매 등 REST API 제공 | [GitHub](https://github.com/wku-team-potato/N.M_BE) |
| **AI 백엔드 서버** | 음식 사진을 분석하여 인식 결과를 반환하는 REST API 제공 | [GitHub](https://github.com/wku-team-potato/N.M_AI_BE) |
| **AI 인공지능 학습 코드** | AI 모델 학습 및 개선 코드 | [GitHub](https://github.com/wku-team-potato/FoodDetectAI-YOLO) |

---
