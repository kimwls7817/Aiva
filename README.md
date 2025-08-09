<h1 align="center" style="color:black; font-weight:bold;">
  아이바(Aiva)
</h1>

<p align="center" style="color:gray; font-size:14px;">
  당신의 육아비서
</p>


<p align="center">
  <img width="300" height="300" alt="aiva_name_image" src="https://github.com/user-attachments/assets/a3886fda-f091-42ae-94ac-6cbcdf98f89f" />
  <img width="500" height="500" alt="aiva_logo" src="https://github.com/user-attachments/assets/74de9561-abea-4c44-8c40-6f35fb7a5fc9" />
</p>

<p align="left">
  <a href="#"><img alt="Status" src="https://img.shields.io/badge/status-alpha-blue"></a>
  <a href="#"><img alt="Hackathon" src="https://img.shields.io/badge/2025%20Seoul%20WomenTech-우다다-ff69b4"></a>
  <a href="#"><img alt="Flutter" src="https://img.shields.io/badge/app-Flutter-informational"></a>
  <a href="#"><img alt="LLM" src="https://img.shields.io/badge/LLM-OpenAI%20gpt--3.5--turbo-6C63FF"></a>
  <a href="#"><img alt="License" src="https://img.shields.io/badge/license-TBD-lightgrey"></a>
</p>

> **“2025 서울 우먼테크 해커톤” 우다다 팀의 아이바(Aiva) 앱 서비스 저장소입니다.**  
> 팀명: **우다다**  
> 팀원: **최문경**(팀장/기획/디자인), **이다영**(백엔드), **김예진**(프론트엔드/앱·AI)

---

## 목차
- [소개](#소개)
- [주요 기능](#주요-기능)
- [AI 서비스](#ai-서비스)
- [시스템 아키텍처](#시스템-아키텍처)
- [환경 변수](#환경-변수)
- [API 개요](#api-개요)
- [앱폴더 구조](#앱폴더-구조예시)
- [문의](#문의)

---

## 소개
아이바(Aiva)는 **육아 정보를 즉시·정확하게** 제공하는 **AI 기반 육아 비서**입니다.  
대화형 UI로 부모의 고민을 이해하고, 신뢰 가능한 자료와 컨텍스트를 바탕으로 개인화된 조언을 제공합니다.

( 각 프로젝프 폴더의 파일은 Ai service.md, App service.md페이지의 링크를 통해 확인하실 수 있습니다. )

---

## 주요 기능
**APP service**
1. **홈 화면**: Aiva AI와 대화하고, **대화 기록**을 확인하여 연속 맥락으로 조언을 받습니다.  
2. **커뮤니티**: 다른 사용자의 글과 **육아/정책 배너**를 통해 정보를 공유·확인합니다.  
3. **마이페이지**: 사용자/자녀 정보를 등록·수정하여 **개인화 품질**을 높입니다.

---

## AI 서비스
**AI service**
- **모델**: OpenAI `gpt-3.5-turbo` 사용  
- **생성 방식**: RAG(검색 증강 생성) + **few-shot 예시 기반 질의 유사도 검색** 후 답변 생성  
- (선택) **출처 표시** 및 **대화 요약** 기능 확장 가능

> 추후 모델/세부 파이프라인은 쉽게 교체할 수 있도록 모듈화되어 있습니다. (*예: `MODEL` 환경변수 변경*)

---

## 시스템 아키텍처

<p align="center">
  <img width="2525" height="774" alt="aiva server architecture drawio" src="https://github.com/user-attachments/assets/45ac2b1a-7e93-45b3-ad5a-e95c4f089062" />
</p>

---

## 앱앱폴더-구조예시
<img width="435" height="198" alt="image" src="https://github.com/user-attachments/assets/dcde9ee9-c83d-4719-9400-d15740cfd954" /></br>
<img width="437" height="253" alt="image" src="https://github.com/user-attachments/assets/3a395d84-52ae-4863-8a88-a4b213aa9798" /></br>
<img width="436" height="287" alt="image" src="https://github.com/user-attachments/assets/9a96d0de-76ad-4a23-81af-97f2195bc2a0" /></br>

---

## 문의

**이메일**
- 우다다 팀메일: wudada0722@gmail.com

