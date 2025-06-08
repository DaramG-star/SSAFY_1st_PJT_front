# 🐿️ finMunk

도토리를 모아 도토리 숲을, 티끌을 모아 금융을.
<br>
금융 초보자들을 위한 올인원 금융정보 탐색 · 비교 · 추천 플랫폼입니다.

---

## ✅ 프로젝트 개요

| 항목 | 내용 |
| --- | --- |
| **프로젝트명** | finMunk (핀뭉크) |
| **설명** | 예금·적금 상품 정보 제공 및 사용자 맞춤형 추천 기능을 갖춘 통합 금융 플랫폼 |
| **기간** | 2025-05-17 ~ 2025-05-27 |
| **팀원** | 2명 (Vue3 + Django REST 기반 SPA) |

---

## 👩‍💻 팀원

| 이름 | 역할 |
| --- | --- |
| 희진 | 백엔드, 프론트엔드 컴포넌트 개발 및 통합, 기획 및 전체 구조 설계, UI/UX 설계 |
| 연주 | 프론트엔드, 백엔드, UI/UX 디자인, 컴포넌트 개발 및 통합, 추천 알고리즘, 배포 |

---

## 🧪 기술 스택

### 🔧 Backend
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/Django%20REST%20Framework-FF1709?style=for-the-badge&logo=django&logoColor=white)](https://www.django-rest-framework.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![django-rest-auth](https://img.shields.io/badge/django--rest--auth-003545?style=for-the-badge&logo=python&logoColor=white)](https://dj-rest-auth.readthedocs.io/en/latest/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://www.sqlite.org/index.html)

### 🎨 Frontend
[![Vue 3](https://img.shields.io/badge/Vue%203-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://v3.vuejs.org/)
[![Pinia](https://img.shields.io/badge/Pinia-FADA5E?style=for-the-badge&logo=pinia&logoColor=black)](https://pinia.vuejs.org/)
[![Vue Router](https://img.shields.io/badge/Vue%20Router-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white)](https://router.vuejs.org/)
[![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)](https://axios-http.com/kr/docs/intro)

### 🌐 API
- 금융감독원 오픈 API (정기예금/적금)
- 한국금거래소 API (금/은 시세)
- 유튜브 API
- 카카오맵 API
- OpenAI GPT API

### 🛠️ 개발환경 & 협업 도구
<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" width="90" alt="Node.js"/>
  <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white" width="70" alt="npm"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white" width="70" alt="Vite"/>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" width="70" alt="Figma"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" width="80" alt="Notion"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" width="80" alt="GitHub"/>
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" width="80" alt="GitLab"/>
</p>

---

## 🎨 주요 기능 소개

### 홈페이지 디자인
친근한 다람쥐 캐릭터를 중심으로 사용하기 쉽고 직관적인 인터페이스로 홈페이지를 디자인했습니다.

<p align="center">
  <img src="images/homepage1.PNG" width="400" alt="홈페이지 메인" />
  <img src="images/homepage2.PNG" width="400" alt="홈페이지 기능 소개" />
</p>
<p align="center">
  <img src="images/home.gif" width="400" alt="홈페이지 기능 동작 GIF" /><br>
  <em>홈페이지 디자인 모습</em>
</p>

### 회원가입
회원가입 시 개인 정보와 함께 사용할 아이디 및 비밀번호를 설정해야 합니다.

<p align="center">
  <img src="images/signup.png" width="300" alt="회원가입" />
</p>

### 1. AI 기반 금융 상품 추천
머신러닝 모델이 사용자 입력 정보를 분석하여 최적의 예·적금 상품 가입 기간과 예상 금액을 제시하고, 맞춤형 TOP 5 상품을 추천합니다.

<p align="center">
  <img src="images/recommend1.PNG" width="500" alt="AI 분석 결과" /><br>
  <em>AI 분석 결과 및 추천 상품</em>
</p>
<p align="center">
  <img src="images/recommend3.PNG" width="350" alt="추천 상품 상세 정보2" />
</p>
<p align="center">
  <img src="images/consult.PNG" width="350" alt="상담신청" /><br>
  <em>상세 정보 확인 및 상담 신청 기능</em>
</p>
<p align="center">
  <img src="images/recommend4.gif" width="400" alt="AI 추천 기능 동작 GIF" /><br>
  <em>AI 추천 기능 동작 모습</em>
</p>

---

### 2. 예·적금 비교 및 검색
다양한 조건으로 필터링하여 원하는 예·적금 상품을 쉽게 비교하고 검색할 수 있습니다.

<p align="center">
  <img src="images/deposit_compare.png" width="500" alt="예적금 상품 비교 페이지" />
</p>
<p align="center">
  <img src="images/compare2.PNG" width="500" alt="상품 상세 정보 모달" /><br>
  <em>상품 상세 정보 확인</em>
</p>

---

### 3. 실시간 금융 정보 및 뉴스
주요 금융 지표, 환율, 금/은 시세를 실시간으로 제공하고 최신 금융 뉴스를 확인할 수 있습니다.

<p align="center">
  <img src="images/exchange_calc.png" width="400" alt="실시간 금융 지표" />
  <img src="images/exchange_calc2.png" width="400" alt="금/은 시세 차트" />
  <img src="images/exchange_calc3.PNG" width="600" alt="뉴스" />
</p>

---

### 4. 소통하는 금융 커뮤니티
금융 팁과 정보를 자유롭게 나누는 소통 공간입니다. 게시글 작성부터 댓글, 좋아요, 다른 사용자 언급(@) 및 팔로우에 이르는 다양한 소셜 기능을 통해 활발한 상호작용이 가능합니다.

<p align="center">
  <img src="images/community.png" width="750" alt="커뮤니티 메인 화면" /><br>
  <em>전체 게시글을 한눈에 볼 수 있는 커뮤니티 메인 화면입니다.</em>
</p>

<p align="center">
  <img src="images/write1.PNG" width="700" alt="새 글 작성" /><br>
  <em>카테고리 선택, 제목 및 내용 작성, 이미지 첨부가 가능한 글쓰기 페이지입니다.</em>
</p>

<p align="center">
  <img src="images/community1.png" width="750" alt="게시글 상세" /><br>
  <em>게시글을 읽고 좋아요를 누르거나 댓글을 작성하며 소통할 수 있습니다.</em>
</p>

<p align="center">
  <img src="images/comment.PNG" width="600" alt="댓글 작성 및 언급" />
  <img src="images/profile2.PNG" width="450" alt="사용자 프로필" /><br>
  <em>댓글에서 다른 사용자를 @언급하여 알림을 보내거나, 프로필 보기를 통해 서로 팔로우할 수 있습니다.</em>
</p>
---

### 5. 유튜브 영상 검색 및 AI 요약
금융 관련 유튜브 영상을 검색하고 저장하여 나만의 학습 리스트를 만들 수 있으며, AI(ChatGPT)를 통해 영상 내용을 요약하여 효율적인 학습을 돕습니다.

<p align="center">
  <img src="images/video_search1.png" width="500" alt="유튜브 영상 검색" />
  <img src="images/video_search3.png" width="500" alt="영상 상세 및 ChatGPT 요약" />
</p>

---

### 6. 마이페이지 및 실시간 알림
나의 금융 활동 내역을 확인하고, 실시간 알림을 통해 중요한 정보를 놓치지 않도록 지원합니다.

<p align="center">
  <img src="images/mypage.png" width="400" alt="마이페이지" />
</p>
<p align="center">
  <img src="images/noti.PNG" width="200" alt="실시간 알림창" />
  <img src="images/noti1.PNG" width="200" alt="실시간 알림창1" />
  <img src="images/noti2.PNG" width="200" alt="실시간 알림창2" />
</p>
<p align="center">
  <img src="images/mypageg.gif" width="400" alt="알람 기능 동작 GIF" /><br>
  <em>마이페이지 동작 모습</em>
</p>
<p align="center">
  <img src="images/notifi.gif" width="400" alt="알람 기능 동작 GIF" /><br>
  <em>알림 기능 동작 모습</em>
</p>

---

### 7. 24시간 AI 챗봇 상담
AI 챗봇 '람쥐봇'을 통해 금융 관련 질문에 대한 답변과 필요한 기능 안내를 받을 수 있습니다.

<p align="center">
  <img src="images/chatbot.png" width="300" alt="챗봇 대화 예시" />
  <img src="images/chatbot2.png" width="300" alt="챗봇 대화 예시2" />
</p>

---

## 🧠 추천 알고리즘 요약

- **사용자 입력**: 나이, 직업 여부, 소득, 자산
- **머신러닝 예측**: 사전 학습된 모델이 사용자 정보 기반으로 최적 `추천 개월 수` & `추천 금액` 예측
- **유사도 계산**: 예측된 값과 DB 내 전체 상품의 (개월 수, 금액)을 `유클리드 거리`로 계산
- **최종 추천**: 거리가 가장 가까운 상위 5개 상품을 추천
- **기록 저장**: 추천 결과는 `RecommendationLog`에 저장하여 추천 이력 관리

---

## 📊 ERD Diagram

<p align="center">
  <img src="images/erd.png" width="600" alt="ERD" />
</p>

- 사용자(User), 금융상품(Deposit/Saving), 추천기록, 커뮤니티(Article, Comment), 저장영상, 알림(Notification) 등으로 구성
- `liked_by`는 Article, Comment, DepositProduct, SavingProduct 모두 ManyToMany 관계로 설계됨

---

## 📆 개발 일정 요약

| 날짜 | 진행 내용 |
| --- | --- |
| 5/17 | 기획 및 DB 모델 설계 |
| 5/17~20 | Django/DRF, Vue3 구조 세팅 / 상품 데이터 저장 |
| 5/21~23 | 금리 비교, 추천 알고리즘 구현 / 컴포넌트 UI 제작 |
| 5/23~25 | 영상 검색, 커뮤니티 기능 완성 / 마이페이지 연결 |
| 5/26 | 통합 테스트 및 디자인 마무리 |
| 5/27 | 발표 및 마무리 제출 |

---

## 🥲 개인 회고

### 희진
> 프로젝트 초기에는 단순히 "기능만 구현하면 되겠지"라는 마음으로 시작했지만,
> 실제로 추천 알고리즘을 설계하고 학습시킨 모델을 API로 연결한 뒤,
> 프론트에서 결과를 받아 렌더링하기까지의 흐름을 구현하면서
> 하나의 서비스가 완성되기까지 필요한 단계들을 실전으로 체감할 수 있었습니다. ... (이하 생략)

### 연주
> 처음 Vue3를 접했을 땐 낯선 구조와 문법에 적응하는 것부터 쉽지 않았습니다.
> 특히 Composition API 방식의 데이터 흐름이나 `ref`, `computed`, `watch` 같은 개념이 처음엔 익숙하지 않아 헤맸지만,
> 실제로 컴포넌트를 하나하나 만들어가며 구조가 어떻게 작동하는지를 체득할 수 있었습니다. ... (이하 생략)