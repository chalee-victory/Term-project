# 프리미엄 코스메틱 웹사이트 UI/UX 기획 결과물

## 세트 A (LUMIÈRE SEOUL) 와이어프레임 디자인 명세서 및 AI 생성 프롬프트

* **프로젝트:** 가상 프리미엄 뷰티 브랜드 웹 UI/UX 구축
* **디자인 콘셉트:** 하이엔드 에디토리얼 & 절제된 여백
* **대상 화면:** 세트 A 4종 (메인, 장바구니, 상세, 검색)
* **작성일자:** 2026년 7월 31일

---

## 1. 와이어프레임 구조 (Wireframe Structure)
웹사이트의 핵심 4개 화면(메인, 장바구니, 상세 페이지, 검색 결과)의 구조적 레이아웃입니다.

### A-01. 메인 홈페이지 (Main Homepage)
* **Header (GNB):** 로고(LUMIÈRE), 메뉴(BRAND, PRODUCTS, ROUTINE, GIFTS, EVENT), 유틸리티 아이콘(검색, 마이페이지, 장바구니)
* **Hero Section:** 풀스크린 이미지 슬라이더, 브랜드 메인 캠페인 캐치프레이즈("시간이 빛나는 당신을 위한 프리미엄 뷰티"), 콜투액션(CTA) 버튼
* **Brand Story Section:** 브랜드 철학과 원료/제형 스토리를 전달하는 에디토리얼 레이아웃
* **Best Products Section:** 시즌 베스트셀러 제품 카드 그리드 (상품 썸네일, 제품명, 가격, 간편 장바구니 버튼)
* **Personalization Section:** "나에게 꼭 맞는 뷰티 루틴 찾기" 맞춤형 큐레이션 유도 배너

### A-02. 장바구니 (Cart)
* **Page Title:** Cart (장바구니에 담긴 상품 확인 안내)
* **Table / List Area (3단 구성):**
  * 상품 정보 (썸네일, 상품명: 루미에르 래디언스 세럼, 루미에르 리바이탈 크림, 용량)
  * 수량 조절 버튼 (`-`/`+`) 및 선물 포장 옵션 체크박스
  * 가격 및 총 합계 금액
* **Order Summary Area:** 상품 금액 합계, 배송비 안내(무료배송), 최종 결제금액 및 [결제하기] CTA 버튼

### A-03. 상품 상세 페이지 / PDP (Product Detail Page)
* **Gallery Section:** 제품 패키지, 텍스처 드리퍼, 사용 컷 등 멀티 썸네일 갤러리
* **Product Info Section:** 카테고리(SERUM), 제품명(루미에르 래디언스 세럼), 평점(4.9/128건), 가격
* **Accordion Sections:**
  * 제품 설명 (풍부한 보습과 영양을 담은 포뮬러 안내)
  * 효능 및 임상 데이터 시각화 (보습 증가율 +68%, 탄력 개선율 +52%, 시점별 개선 그래프)
  * 사용 방법 (아침/저녁 루틴 가이드)
* **Fixed CTA Area:** [장바구니], [구매하기], [위시리스트] 버튼

### A-04. 검색 결과 페이지 (Search Results)
* **Search Bar & Count:** 검색어 입력 필드 및 총 검색 결과 수 (48개)
* **Filter Area (LNB):** 다차원 필터 (제품 종류 [스킨케어, 파운데이션 등], 연령대, 성별, 피부톤) 및 초기화 버튼
* **Product Grid:** 4열 상품 카드 리스트 (썸네일, 제품명: 루미에르 래디언스 에센스 ₩130,000 등, 평점, 위시리스트 아이콘)
* **Sorting & View Control:** 추천순 정렬 드롭다운, 그리드/리스트 보기 전환 아이콘

---

## 2. 디자인 명세서 (Design Specification)

| 구분 | 내용 |
| :--- | :--- |
| **브랜드 명칭** | LUMIÈRE SEOUL (루미에르 서울) |
| **디자인 콘셉트** | 절제된 여백과 차분한 컬러 시스템을 기반으로 한 하이엔드 에디토리얼 스타일 |
| **컬러 팔레트** | • **Primary:** 골드 및 차분한 베이지 톤 (`#C5A880` 계열 포인트)<br>• **Background:** 화이트 (`#FFFFFF`) 및 미세한 오프화이트 여백<br>• **Text:** 다크 그레이 / 블랙 계열을 사용하여 가독성 확보 |
| **타이포그래피** | 세련된 세리프(Serif)체 타이틀과 가독성이 높은 산세리프(Sans-serif) 본문 조합 |
| **인터랙션 및 규칙** | • **버튼 및 CTA:** 직관적인 박스 형태의 골드/브라운 톤 버튼, 마우스 오버 시 미세한 톤 변화<br>• **아코디언 및 필터:** 사용자 탐색 편의성을 높인 접이식 메뉴 및 다차원 체크박스 구조 |

---

## 3. AI 이미지 생성용 프롬프트 (Prompt Specification)
검토 및 개선 과정을 거쳐 완성도 높은 시안을 도출하기 위해 사용된 UI 생성용 프롬프트 구조입니다.

### 스타일 및 톤앤매너 프롬프트
```text
High-end editorial style cosmetic brand e-commerce website UI design, minimalist layout with generous whitespace, sophisticated gold and beige color palette, clean typography, luxury aesthetic, professional UI/UX designar --ar 16:9
```

### 메인 홈페이지 (A-01) 생성 프롬프트
```text
Desktop web UI design for a luxury cosmetics brand homepage, top navigation bar with clean text links, full-width hero banner featuring a premium serum bottle on a beige stone with soft natural lighting, elegant product grid section below with minimalist cards.
```

### 상품 상세 페이지 (A-03) 생성 프롬프트
```text
E-commerce product detail page UI layout, left side vertical thumbnail gallery and high-resolution drop bottle image, right side product title, price, star rating, accordion sections for product description, clinical efficacy data graphs with percentage metrics, and clear CTA buttons.
```
