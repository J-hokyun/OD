# 🎧 사용자 맞춤 오디오북 서비스

![서비스 이미지](https://github.com/user-attachments/assets/bccb87d5-f3f9-4b11-94cb-da81957bce75)

## 📅 진행기간
**2023.12 ~ 2024.01**

## 📖 프로젝트 개요
사용자가 원하는 음성을 AI에 학습시키거나 원하는 음성으로 오디오 북을 들을 수 있도록 하는 플랫폼입니다.

## 🛠️ 개발환경

- **언어**: Python
- **프레임워크**: Django
- **데이터베이스**: PostgreSQL
- **AI 도구**: TTS, DALLE3, RVC
- **클라우드**: AWS
- **협업 툴**: JIRA
- **버전 및 이슈관리**: Github

---

## 📌 맡은 역할
1. **사용자 회원가입**
2. **사용자 로그인**
3. **도서 즐겨찾기 CRUD**
4. **음성 등록 CRUD**
5. **고객 센터 문의 CRUD**

---

## 💡 주요 기능

### 1. 로그인 및 회원가입
- Google, Kakao 소셜 회원가입 및 로그인을 제공합니다.
- Jwt 토큰 발행을 통해 사용자의 권한을 체크합니다.

![로그인 화면](https://github.com/user-attachments/assets/c6caa91d-d460-42f0-8b95-0ca1e7084f17)

### 2. 오디오 북 선택
- 홈 화면에서 원하는 오디오 북을 선택할 수 있습니다.
- 장르별로 확인하며 좋아요 기능을 제공합니다.

![오디오 북 선택 화면](https://github.com/user-attachments/assets/d932aca3-c6e5-4a78-931e-9963ca2924e7)

### 3. 오디오 청취
- 다양한 성우의 음성을 선택하여 청취할 수 있습니다.
- 플랫폼 제공 음성, 사용자 등록 음성, 타인이 등록한 음성 목록 중 선택 가능합니다.

![오디오 청취 화면](https://github.com/user-attachments/assets/e1099ff0-9738-49c8-bd90-e36ffa4dc40c)
![음성 선택 화면](https://github.com/user-attachments/assets/a7d228f1-9d9f-4d8f-98d0-8110fb42270d)

### 4. 사용자 음성 학습
- 음성 MP3 파일을 업로드하여 AI 학습을 진행할 수 있습니다.
- 학습된 음성의 공개 여부를 설정할 수 있습니다.

![음성 학습 화면](https://github.com/user-attachments/assets/93c27c0b-3690-466c-91be-74b18f92689a)
![음성 설정 화면](https://github.com/user-attachments/assets/553d009f-97f2-4a9a-b1bb-0e3c3ac7113e)

### 5. 사용자 커뮤니티 기능
- 책에 대한 토론을 진행할 수 있는 토론방을 제공합니다.
- 신규 도서 신청 및 1:1 문의 기능을 포함합니다.

![커뮤니티 기능 화면](https://github.com/user-attachments/assets/32a5cd32-5878-40e0-99a4-aa4d35fd323b)

---
