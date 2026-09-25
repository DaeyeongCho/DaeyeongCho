# 조대영 | Daeyeong Cho

**Software Engineer · AI Applications & Cloud Infrastructure**

Python과 LLM/RAG를 활용한 소프트웨어 개발, Kubernetes 기반 마이크로서비스, 멀티 클라우드 인프라를 다룹니다.  
컨테이너 운영 정보와 서비스 간 통신 흐름을 분석하고, AI를 활용한 배포·오류 지원 기술을 연구·개발했습니다.

**Currently:** Python Developer @ SmartBank  
**Background:** 부산대학교 컴퓨터공학전공 공학석사 · 소프트웨어공학 연구실(SELab) 연구원

[GitHub](https://github.com/DaeyeongCho) · [Portfolio](https://daeyeongcho.github.io/) · [ORCID](https://orcid.org/0009-0005-3903-5723) · [Email](mailto:jdy5989@naver.com)

## Experience

### SmartBank / 스마트뱅크
**Python Developer · AI Service & Backend** | Sep 2026 – Present

- 참여 영역: 에이젠틱 AI 기반 도면관리 서비스 플랫폼 개발
- 개발 방향: Python 기반 백엔드·API와 LLM/RAG를 활용한 문서 검색·분석 및 AI Agent 연계

### Pusan National University · Software Engineering Lab(SELab)
**연구원** | Jan 2024 – Feb 2026

- 컨테이너 기반 마이크로서비스의 배치·약결합 및 RAG 기반 오류 식별·해소 방안 생성 기술 연구·개발
- 멀티 클라우드 메타데이터 관리, AI 가속기 자원 관리 및 모니터링 환경 구성

## Engineering & Research

### RAG 기반 마이크로서비스 오류 식별 및 해소 방안 생성

**문제:** 컨테이너 상태만으로 파악하기 어려운 서비스 간 연결·기능 오류를 식별하고 RAG를 활용해 오류 해소 방안을 제시하는 방법을 연구·개발했습니다.

- Kubernetes 운영 정보와 YAML 명세, Jaeger 통신 흐름을 수집·분석하고 배포·약결합 오류 유형 도출
- LangChain과 ChromaDB를 활용한 RAG 지식 베이스 구축
- 운영 정보와 기존 오류 사례를 활용한 LLM 기반 오류 식별 및 해소 방안 생성·비교 평가

**Tech:** Python · Kubernetes · Jaeger · LangChain · ChromaDB · LLM/RAG  
**Project:** 컨테이너 기반 마이크로서비스 개발을 위한 스마트 프레임워크 기술 — 한국연구재단(NRF), 2024.03–2026.01  
**Resources:** [실험 자료](https://github.com/DaeyeongCho/MSAError) · [2026 저널 논문](https://doi.org/10.23019/kingpc.22.4.202608.002) · 석사학위논문

### LLM 기반 마이크로서비스 배치·약결합

**개요:** 마이크로서비스의 기능과 연결 관계를 해석하고 사용자 요구사항에 맞게 서비스를 선택·배포할 수 있도록 LLM을 적용하는 방법을 연구·개발했습니다.

- Kubernetes Pod / Service / Deployment 명세에서 기능·약결합 요소 분석
- BCE(Boundary-Control-Entity) 패턴과 LLM Fine-tuning을 활용한 배치 유형 식별
- 사용자 요구사항 기반 마이크로서비스 추천 및 약결합 배포 프로토타입 구현·검증

**Tech:** Python · Kubernetes · Docker · OpenAI API · LLM Fine-tuning  
**Project:** 컨테이너 기반 마이크로서비스 개발을 위한 스마트 프레임워크 기술 — 한국연구재단(NRF), 2024.03–2026.01  
**Resources:** [2025 저널 논문](https://doi.org/10.3745/TKIPS.2025.14.1.21) · [특허 출원](https://patents.google.com/patent/KR20260065458A/ko) · ACK 2024 ETRI 원장상

### 멀티 클라우드 메타데이터 및 AI 가속기 자원 관리

**문제:** 클라우드별로 다른 메타데이터와 자원 정보를 활용하여 인프라 탐색·관리와 운영 상태 확인을 지원하는 도구를 개발했습니다.

- Go·React 기반 멀티 클라우드 메타데이터 분류·검색 도구 개발 참여
- AWS·Google Cloud의 AI 가속기 자원 관리 및 멀티 클라우드 연동 기술 개발 참여
- Managed Kubernetes 기반 인프라와 Prometheus·Grafana 모니터링 환경 구성

**Tech:** Go · React · AWS · Google Cloud · Azure · Kubernetes · Prometheus · Grafana · JMeter  
**Project:**
- 멀티 클라우드 관리 플랫폼 대상 AI 컴퓨팅 가속 자원 관리를 위한 선행 기술 개발 — 한국전자통신연구원(ETRI), 2025.09–2026.01
- 컴퓨팅 인프라 운영 지원을 위한 멀티 클라우드 메타 정보 분류 및 검색 도구 개발 — 한국전자통신연구원(ETRI), 2024.11–2025.03

## Core Tech Stack

| Area | Technologies |
| --- | --- |
| Languages / Development | Python · Java · Go · C/C++ · React |
| AI / Data | LLM · RAG · LangChain · ChromaDB · OpenAI API · Fine-tuning |
| Cloud / Infrastructure | Kubernetes · Docker · AWS · Google Cloud · Azure · Linux |
| Observability / Testing | Prometheus · Grafana · Jaeger · JMeter |

## Publications

**학술 논문 7편 (Journal 3 · Conference 4) · 석사학위논문 1편**

### Journal Papers

- **컨테이너 기반 마이크로서비스 오류 처리를 위한 검색 증강 생성 적용 방법**  
  정수민, **조대영**, 박준석, 염근혁  
  한국차세대컴퓨팅학회 논문지, Vol. 22, No. 4, pp. 22–35, 2026.  
  [DOI: 10.23019/kingpc.22.4.202608.002](https://doi.org/10.23019/kingpc.22.4.202608.002)

- **마이크로서비스 아키텍처 결합 결정을 지원하는 학습 기반 관리 방법**  
  정수민, **조대영**, 박준석, 염근혁  
  한국차세대컴퓨팅학회 논문지, Vol. 21, No. 5, pp. 7–21, 2025.  
  [DOI: 10.23019/kingpc.21.5.202510.001](https://doi.org/10.23019/kingpc.21.5.202510.001)

- **BCE 패턴 학습에 기반한 사용자 요구사항 맞춤형 마이크로서비스 약결합 배포 방법**  
  **조대영**, 정수민, 박준석, 염근혁  
  정보처리학회 논문지(KTSDE), Vol. 14, No. 1, pp. 21–31, 2025.  
  [DOI: 10.3745/TKIPS.2025.14.1.21](https://doi.org/10.3745/TKIPS.2025.14.1.21)

<details>
<summary>Conference Papers · 4편</summary>

- **컨테이너 기반 마이크로서비스 운영 지원을 위한 검색 증강 생성(RAG) 적용 기법**  
  정수민, **조대영**, 박준석, 염근혁  
  ACK 2025, Vol. 32, No. 2, pp. 493–496, 2025.  
  [논문 정보](https://kiss.kstudy.com/Detail/Ar?key=4209918)

- **RAG를 적용한 컨테이너 기반 마이크로서비스 배포 오류 식별 및 해소 방법**  
  **조대영**, 정수민, 박준석, 염근혁  
  2025 한국컴퓨터종합학술대회(KCC 2025), pp. 388–390, 2025.  
  [논문 정보](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12318188)

- **BCE 패턴 기반 마이크로서비스 아키텍처의 배치 유형 식별을 위한 생성형 AI 파인튜닝 방법**  
  **조대영**, 정수민, 박준석, 염근혁  
  ACK 2024, Vol. 31, No. 2, pp. 451–454, 2024.  
  🏆 **한국전자통신연구원(ETRI) 원장상**  
  [논문 정보](https://kiss.kstudy.com/Detail/Ar?key=4155949)

- **생성형 AI를 적용한 컨테이너 기반의 마이크로서비스 배치 기법**  
  **조대영**, 정수민, 박준석, 염근혁  
  2024 한국컴퓨터종합학술대회(KCC 2024), pp. 313–315, 2024.

</details>

### Master's Thesis

- **RAG를 적용한 컨테이너 기반 마이크로서비스의 오류 식별 방법**  
  **조대영**, 부산대학교 대학원, pp. 1-52, 2026.

## Patent

**생성형 AI 학습 기반 마이크로서비스 약결합 지원 시스템 및 방법**

- 특허 출원 실적 1건 · 최초 출원일: **2024-10-29**
- 마이크로서비스 명세와 명세 구분 방안을 생성형 AI 학습에 활용하여 마이크로서비스 약결합을 지원하는 기술
- [관련 공개문헌: KR20260065458A](https://patents.google.com/patent/KR20260065458A/ko)

<details>
<summary>관련 공개문헌의 서지정보</summary>

- 공개 명칭: **생성형 AI 학습에 기반한 마이크로서비스 약결합 지원 방법 및 시스템**
- 발명자: 염근혁, **조대영**, 박준석, 정수민
- 출원인: 부산대학교 산학협력단
- 공개문헌의 출원번호 / 출원일: **10-2025-0004204 / 2025-01-10**
- 우선권 기초출원 번호 / 날짜: **10-2024-0150030 / 2024-10-29**
- 공개번호 / 공개일: **10-2026-0065458 / 2026-05-08**
</details>

## Achievements

- **ACK 2024 한국전자통신연구원(ETRI) 원장상** — 제1저자
- **컴퓨터프로그램 저작권 등록 5건**
- 학술 논문 **7편** · 석사학위논문 **1편** · 특허 출원 실적 **1건**

## Education

### 부산대학교 대학원

**정보융합공학과 컴퓨터공학전공 · 공학석사**  
Mar 2024 – Feb 2026 · **GPA 4.06 / 4.5**

### 동국대학교 WISE캠퍼스

**ICT·빅데이터학부 컴퓨터공학전공 · 공학사**  
Mar 2022 – Feb 2024 · **GPA 4.23 / 4.5**

## Contact & Links

- Email: [jdy5989@naver.com](mailto:jdy5989@naver.com)
- Portfolio: [daeyeongcho.github.io](https://daeyeongcho.github.io/)
- GitHub: [github.com/DaeyeongCho](https://github.com/DaeyeongCho)
- ORCID: [0009-0005-3903-5723](https://orcid.org/0009-0005-3903-5723)
