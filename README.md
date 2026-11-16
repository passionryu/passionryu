# 류성열 <sub>Product Engineer</sub>

안녕하세요, POD E-commerce 서비스 회사에서 Creative Tool 파트를 개발하는 <b>Product Engineer(C#/.NET) 류성열</b>입니다.

Claude 기반의 AI-Native를 지향하는 팀에서, 새 AI 기술을 도전·공유하며 <b>팀 AI 전환(AX)</b>에 기여합니다.<br>
Notion을 통해 Second Brain을 구축한 후, Agent를 연동한 Kanban Board를 기반으로 <b>여러 티켓을 병렬 오케스트레이션</b>하고 <b>2차 QA 프로세스(AI E2E QA → Human QA)</b>를 적용하여 작업의 속도와 품질을 보장합니다.

과거 컴퓨터 공학을 전공하며, 다음 경험을 통해 Back-End 중심의 개발 역량을 쌓았습니다.
- AI 서비스 개발 학과 프로젝트를 <b>9개월간 TL</b> 역할 수행
- 교내 웹/앱 개발 동아리 <b>백엔드 개발 팀장</b> 직무 1년간 수행

졸업 후, 3개월간 백엔드 단기 심화 부트캠프를 통해 심화 지식·경험을 습득했습니다.<br>
이후, 핀테크 스타트업 모바일 금융 서비스 개발팀에서 <b>백엔드 개발자(Kotlin·Spring Boot)</b>로 합류하여 <b>MVP 개발(카드 서비스) → Alpha Test(그룹사 임직원 70명 대상) → 런칭 및 운영</b>한 업무 경험을 보유하며 회사의 핀테크 비즈니스를 수평 확장하고, 선불 사업자 라이선스 취득 조건을 충족하는 데 기여했습니다.

---

<details>
<summary><b>🏢 Sweetbook Co., Ltd.</b> · Product Engineer (풀스택) · 2026.08 ~</summary>
<br>

포토북·책 제작 플랫폼(POD형 이커머스)에서 Creative Tool 파트(포토북·달력 편집기)를 개발하는 Product Engineer로, 레거시 개선과 신규 기능 개발을 맡고 있습니다.

<a href="https://www.sweetbook.com/"><img src="https://img.shields.io/badge/Website-sweetbook.com-414141?style=flat-square&logo=googlechrome&logoColor=white" alt="스위트북 웹사이트"></a>

**[달력 PNG 생성 Creative Tool 레거시 개선]**
- 중요 로직을 Code-Driven에서 SSOT 개념을 적용한 Data-Driven 구조로 전환하여 불필요한 Build&Deploy를 제거했습니다. 레거시 PNG 대비 간격 오차를 1px 미만으로 유지하며 마이그레이션을 완료(총 336건의 PNG)했습니다.

**[사내 디자인팀 지원 툴 개발]**
- 디자이너가 파일을 일일이 찾아 JSON을 수정하고 결과물을 폴더에서 확인하던 작업을, 수정·미리보기·저장을 한 화면에서 처리하는 One Page Product(C# WPF)로 바꿨습니다. 기존 그리기 엔진을 화면 안에서 바로 호출하도록 해 결과 확인 시간을 5초에서 0.54초로 89% 단축했습니다.

**[PowerShell, WinRM을 통한 달력 PNG 배포 자동화] **
- 7대의 샤딩 서버에 원격 접속해 명령 49번을 반복하던 수동 배포를 명령 1번으로 자동화해, 배포 시간을 2시간 25분에서 28분으로 81% 줄였습니다. 권한 관리·인수인계 비용 같은 현실 제약 안에서 바로 적용하고 추후 개선할 수 있는 방안을 골라 빠르게 구현·적용했습니다.

**[AI-First 개발]**
- 업무 내용을 Second Brain으로 관리해 AI Agent가 참고하게 하고, Kanban Board에 AI Agent를 연동해 여러 티켓을 병렬로 오케스트레이션하며 일합니다. 정기 기술 공유 세션에서 AI 실험 사례를 발표해 팀의 AI 전환(AX)에도 기여하고 있습니다.

</details>

<details>
<summary><b>💳 Bix Payments Co., Ltd.</b> · Backend Developer · 2025.12 ~ 2026.06</summary>
<br>

핀테크 스타트업 B2C 모바일 금융 서비스팀에서 초기 개발~Alpha 기간 유일한 백엔드 개발자로, 카드 서비스 MVP 개발 → Alpha Test(그룹사 임직원 70명) → 출시·운영(출시 전 사전 예약 35,000명)을 경험했습니다. 4개 조직(정산 시스템 개발팀, 협력사 개발팀, QA팀, 운영팀)과 협업해 카드 결제/관리 시스템을 구축했고, 비즈니스 수평 확장과 선불 사업자 라이선스 취득 조건 충족에 기여했습니다.

<a href="https://play.google.com/store/apps/details?id=bz.bix.biscuit"><img src="https://img.shields.io/badge/Google_Play-Biscuit_Card-414141?style=flat-square&logo=googleplay&logoColor=white" alt="Google Play"></a> <a href="https://apps.apple.com/kr/app/biscuit-card/id6758941646"><img src="https://img.shields.io/badge/App_Store-Biscuit_Card-0D96F6?style=flat-square&logo=apple&logoColor=white" alt="App Store"></a>

**[카드 결제]**
- 협력사의 결제 통보가 중복·지연·누락될 수 있어 카드 잔액이 어긋나는 문제가 있었습니다. 멱등성을 적용하고 협력사 원장을 원천 데이터(SoT)로 정의해, 3개월 운영 동안 정합성 관련 CS 0건을 유지했습니다.

**[결제 장애 대응]**
- 협력사의 예고 없는 API 변경으로 카드 결제 장애가 발생했을 때, 모니터링과 약식 E2E 테스트로 상황을 확인하고 긴급 대응해 1시간 안에 결제를 정상화했습니다. 이후 양쪽 DB를 대사해 누락된 결제 15건을 모두 복구했고, 협력사 개발팀과 함께 자동 대응 시스템을 구축했습니다.

**[포인트 충전]**
- 정산금 차감과 포인트 충전이 서로 다른 시스템에서 일어나는 분산 트랜잭션 환경이라, 한쪽만 반영되는 부분 성공·실패 문제가 있었습니다. 정산 시스템 개발자와 함께 TCC 패턴과 보상 트랜잭션을 적용해 부분 성공·실패를 방지했습니다.

**[개발 환경 개선]**
- 연동 대상 환경을 바꿀 때마다 설정을 고치고 재배포해야 해서 테스트 환경 세팅에 10분이 걸렸습니다. DB 기반 Endpoint 동적 라우팅 구조로 외부 연동 대상을 런타임에 바꿀 수 있게 해 세팅 시간을 10초로 단축했습니다.

**[포인트 충전 UX 개선]**
- 충전할 때마다 외부 결제창을 거쳐야 해서 클릭이 10회 필요했습니다. 간편 결제 기능을 연동해 충전에 필요한 클릭 수를 4회로 줄였습니다.

</details>

<details>
<summary><b>🌱 Before</b> · 가천대 컴퓨터공학과 · 멋쟁이사자처럼 · BehindCon 발표</summary>
<br>

- **가천대 컴퓨터공학과** · 9개월간 학과 AI 서비스 프로젝트의 개발자 겸 팀장으로 11명의 학우들과 AI 모델 6개를 fine-tuning해 서비스 3개를 만들었고, 세 프로젝트 모두 A+를 받으며 28팀 중 1등(장학금)을 했습니다.
- **멋쟁이사자처럼 백엔드 5기** · 우수 훈련생으로 선정됐고, 두 팀 프로젝트의 발표를 모두 맡아 최종 프로젝트에서 최우수상(6팀 중 1등)을 받았습니다.
- **BehindCon 초청 발표** · 명지대 학생들이 주최한 컨퍼런스에서 ["AI를 쓰지 않으면 뒤처지고, AI만 의존하면 대체된다"](https://www.youtube.com/watch?v=Po1S4HBXo6w)를 주제로 발표했습니다(2026.07).

</details>

<kbd>C# · .NET</kbd> <kbd>Kotlin</kbd> <kbd>Java</kbd> <kbd>Spring Boot</kbd> <kbd>SQL Server</kbd> <kbd>MariaDB</kbd> <kbd>Redis</kbd> <kbd>Docker</kbd> <kbd>AWS · GCP</kbd> <kbd>Claude Code · Codex</kbd>
