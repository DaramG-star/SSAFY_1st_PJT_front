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
| **희진** | <ul><li>기획 및 전체 구조 설계</li><li>로그인/회원가입 기능 구현 (Full-Stack)</li><li>커뮤니티 기능 기본 골조 설계</li></ul> |
| **연주** | <ul><li>**Front-End & UI/UX 총괄**</li><li>**대부분의 핵심 기능 구현** (AI 추천, 상품 비교, 커뮤니티 완성 등)</li><li>추천 알고리즘 설계 및 구현</li><li>기획 및 배포</li></ul> 

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
  <img src="images/comment.PNG" width="600" alt="댓글 작성 및 언급" />
  <img src="images/profile2.PNG" width="450" alt="사용자 프로필" /><br>
  <em>댓글에서 다른 사용자를 @언급하여 알림을 보내거나, 프로필 보기를 통해 서로 팔로우할 수 있습니다.</em>
</p>

<p align="center">
  <img src="images/profileg.gif" width="500" alt="알람 기능 동작 GIF" /><br>
  <em>프로필 기능 동작 모습</em>
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
  <img src="images/mypageg.gif" width="500" alt="알람 기능 동작 GIF" /><br>
  <em>마이페이지 동작 모습</em>
</p>
<p align="center">
  <img src="images/notifi.gif" width="500" alt="알람 기능 동작 GIF" /><br>
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

#### 🧠 AI 추천 시스템 설계 및 구축 (End-to-End)

금융 초보자는 수많은 상품 중 자신에게 맞는 것을 직접 찾기 어렵다는 문제에서 출발했습니다. 이 문제를 해결하기 위해, 사용자의 재무 상태와 특성을 정밀하게 분석하여 **최적의 금융 상품을 개인화 추천**하는 AI 시스템을 설계하고 구축했습니다.

- **1. 데이터 생성 및 확보 (Data Generation & Acquisition)**
  - 실제 금융 시장의 예/적금 가입 데이터를 모방하여, 다양한 사용자 프로필(나이, 직업, 소득, 자산 등)을 포괄하는 **약 5만 건의 가상 데이터셋을 생성**했습니다. 이를 통해 모델이 다양한 엣지 케이스(Edge Case)에 대응하고 일반화 성능을 확보하는 기반이 되었습니다.

- **2. 모델링 및 성능 검증 (Modeling & Validation)**
  - 단순히 하나의 모델에 의존하지 않고, 선형 모델부터 `Random Forest`, `XGBoost`, `LightGBM` 등 여러 머신러닝 알고리즘의 성능을 교차 검증을 통해 종합적으로 비교 분석했습니다.
  - 다양한 평가지표를 기준으로 검토한 결과, **`Gradient Boosting` 모델이 가장 안정적이고 높은 예측 정확도**를 보여 최종 모델로 채택했습니다.

- **3. 모델 최적화 및 설명 가능성 확보 (Optimization & Explainability)**
  - `GridSearchCV`를 활용하여 `n_estimators`, `learning_rate` 등 모델의 성능에 결정적인 영향을 미치는 주요 하이퍼파라미터를 체계적으로 탐색하고 최적화했습니다.
  - 모델의 예측을 '블랙박스'로 두지 않고, **`SHAP(SHapley Additive exPlanations)` 라이브러리를 도입하여 '왜' 이런 상품이 추천되었는지 해석**할 수 있는 기반을 마련했습니다. 이를 통해 '소득'이나 '자산' 같은 특정 사용자 정보가 추천 결과에 얼마나, 그리고 어떻게 기여했는지를 시각적으로 분석하며 모델의 투명성과 신뢰도를 확보했습니다.

- **4. 최종 추천 로직 (Inference Logic)**
  1.  사용자로부터 나이, 소득 등의 정보를 입력받습니다.
  2.  최적화된 **`Gradient Boosting` 모델**이 최적의 `(추천 개월 수, 추천 금액)`을 예측합니다.
  3.  예측된 값과 DB에 저장된 실제 금융 상품들의 벡터 간 **`유클리드 거리(Euclidean Distance)`를 계산**합니다.
  4.  거리가 가장 짧은, 즉 가장 유사한 **상위 5개의 상품을 최종 추천** 결과로 제공하며, 추천 이력은 DB에 기록됩니다.

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

### 연주
처음 Vue3와 Composition API를 접했을 땐 낯선 구조에 적응하는 것부터가 도전이었습니다. 하지만 프론트엔드와 UI/UX 전반을 책임지는 역할을 맡게 되면서, 단순히 기술을 배우는 것을 넘어 사용자가 마주할 모든 화면을 직접 그려나가야 한다는 책임감을 가졌습니다. Figma로 와이어프레임과 디자인을 구성하고, 이를 실제 코드로 구현하며 '사용자 친화적인 인터페이스란 무엇인가'를 깊이 고민하는 시간을 보냈습니다.

이번 프로젝트에서 저는 로그인/회원가입을 제외한 대부분의 핵심 기능을 직접 구현했습니다. 특히 가장 큰 도전은 AI 추천 알고리즘을 프론트엔드에 녹여내는 과정이었습니다. 백엔드에서 전달된 추천 데이터를 사용자에게 가장 직관적이고 설득력 있게 보여주기 위해 데이터 시각화와 컴포넌트 구조를 수없이 고민했습니다. 또한, 조건별 예/적금 비교 기능과 같이 복잡한 상태 관리가 필요한 페이지는 Pinia를 활용하여 전역 상태를 효율적으로 관리하며 개발 생산성을 높일 수 있었습니다.

단순히 기능을 만드는 것을 넘어, 하나의 서비스를 완성하는 전체 과정을 경험한 것이 가장 큰 수확입니다. 팀원과 함께 아이디어를 내는 기획 단계부터, Figma로 디자인을 구체화하고, AI 추천, 상품 비교, 커뮤니티 등 핵심 기능들을 완성한 뒤, 마지막으로 ngrok을 이용해 프론트엔드를 배포하며 개발의 시작부터 끝까지를 직접 책임지고 완수하는 소중한 경험을 했습니다.

물론 일정이 촉박하여 아쉬운 점도 있지만, 처음 Vue를 마주했을 때의 막막함에서 벗어나 이제는 서비스의 전체 구조를 설계하고 구현할 수 있다는 자신감을 얻었습니다. finMunk는 제게 단순한 개발 과제가 아니라, 기획, 디자인, 핵심 로직 구현, 배포까지 '풀 사이클' 개발 경험을 쌓게 해준, 개발자로서의 성장을 증명하는 프로젝트입니다.
