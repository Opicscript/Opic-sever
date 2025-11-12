# 💬 OPIc-Script Server  
> Node.js 기반 GPT API 연동 영어 스크립트 생성 서버

---

## 📘 Overview
**OPIc-Script Server**는 **Node.js + Express** 기반의 AI 연동 백엔드 서버로,  
영어 말하기 시험인 **OPIc**의 질문 유형에 따라 자동으로 영어 스크립트를 생성해주는 시스템입니다. 
AI가 생성한 답변에 대해 피드백을 기록하고 관리할 수 있습니다.  

백엔드 구조 설계부터 API 라우팅, 데이터베이스 연동까지 전반적인 서버 로직을 직접 구현하였으며,  
**GPT API(OpenAI)**를 활용하여 자연스러운 영어 답변 생성을 지원합니다.

---

## ⚙️ Tech Stack
- **Runtime:** Node.js (v18+)
- **Framework:** Express.js  
- **Database:** MongoDB + Mongoose ODM  
- **API Integration:** OpenAI GPT API  
- **Environment:** dotenv, nodemon
- **Version Control:** Git, GitHub

---

## 🧩 Features
| 기능 | 설명 |
|------|------|
| 🧠 **GPT API 연동** | 사용자 입력(질문 유형)에 따라 ChatGPT API를 호출해 영어 스크립트 자동 생성 |
| 👤 **로그인 및 회원 관리** | JWT 기반 사용자 인증 및 세션 유지 |
| 💾 **데이터베이스 CRUD** | MongoDB를 통한 스크립트/피드백 데이터 저장 및 조회 |
| 🗂️ **피드백 시스템** | AI 또는 사용자가 입력한 피드백을 개별 스크립트에 연결해 관리 |
| 🚀 **RESTful API 구조화** | Express 라우팅과 컨트롤러 계층 분리로 유지보수성 강화 |

---
