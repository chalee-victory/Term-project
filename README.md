# 텀프로젝트 (4조) - AI 기반 UI/UX 디자인 시안 및 Figma 프로토타입

## 1. 프로젝트 개요 및 사용자 설계 의도 (평가항목 #4, #5)

* **프로젝트명:** AI 기반 프리미엄 코스메틱 브랜드(LUMIÈRE SEOUL) 웹 UI/UX 구축
* **주요 사용자 페르소나 & 목표:** 
  * 30대 여성 프리미엄 뷰티 소비자로, 세련된 비주얼을 원하고 자신의 피부 고민에 맞는 제품을 직관적으로 탐색 및 구매하고자 함.
* **화면 동선(Flow) 및 레이아웃 배치 근거:**
  * **메인 홈페이지 (A-01):** 브랜드 스토리텔링 및 큐레이션을 통해 흥미 유발 (우선순위: 브랜드 정체성 전달)
  * **검색/카탈로그 (A-04):** 다차원 필터(피부타입, 연령 등)를 제공하여 빠른 제품 검색 지원 (우선순위: 탐색 편의성)
  * **상품 상세/PDP (A-03):** 제형, 효능 시각화, 임상 데이터 제공으로 구매 결정 강화 (우선순위: 정보 전달 및 결제 유도)
  * **장바구니 (A-02):** 담긴 상품 정보 및 결제금액, 선물 포장 옵션 명확화 (우선순위: 정확한 주문/결제 처리)

---

## 2. 제출물 및 시안 이미지 목록 (평가항목 #1, #3)

### 가. UI 시안 이미지 파일 목록
| 화면 코드 | 화면명 | 파일명 | 형식 | 해상도 | 저장 경로 |
| :--- | :--- | :--- | :---: | :---: | :--- |
| A-01 | 메인 홈페이지 | `A-01.png` | PNG | 1536×1024 | `./assets/A-01.png` |
| A-02 | 장바구니 | `A-02.png` | PNG | 1536×1024 | `./assets/A-02.png` |
| A-03 | 상품 상세(PDP) | `A-03.png` | PNG | 1536×1024 | `./assets/A-03.png` |
| A-04 | 검색 결과 페이지 | `A-04.png` | PNG | 1536×1024 | `./assets/A-04.png` |
| B-01 | 메인 홈페이지(B) | `B-01.png` | PNG | 1536×1024 | `./assets/B-01.png` |
| B-02 | 맞춤 상품 파인더 | `B-02.png` | PNG | 1536×1024 | `./assets/B-02.png` |

### 나. Figma 프로토타입 URL (Direct Link)
* **[시안 A 프로토타입 (LUMIÈRE SEOUL) 바로가기](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=0-1&t=TNR18jrjIkPxat75-1)**
* **[시안 B 프로토타입 (AURA) 바로가기](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=1-1051&t=TNR18jrjIkPxat75-1)**

---

## 3. AI 이미지 후가공 및 가독성·폰트 보정 (평가항목 #2, #7)

AI 생성 시 발생한 텍스트 깨짐 및 레이아웃 왜곡을 수정하기 위해 적용한 후가공 세부 기술 및 폰트 일관성 검토 결과입니다.

### 가. 후가공 기법 및 도구
1. **인페인팅 (Inpainting):** 포포샵 Generative Fill 및 Midjourney Inpaint를 사용하여 텍스트 뭉개짐 영역 제거 및 배경 복원.
2. **벡터 텍스트 재작성:** Illustrator/Figma를 활용하여 브랜드명("LUMIÈRE SEOUL") 및 UI 타이포그래피 재배치.
3. **업스케일링 (Upscaling):** Topaz Gigapixel AI를 사용하여 이미지 해상도를 2K급으로 확대 후 디테일 선명화.

### 나. 가독성 검토 및 적용 폰트
| 위치 | 결함 요소 (Before) | 수정 내용 (After) | 적용 폰트/스타일 |
| :--- | :--- | :--- | :--- |
| **A-01 Hero** | 메인 헤드라인 글자 뭉개짐 | "시간이 빛나는 당신을 위한 프리미엄 뷰티" 재작성 | Playfair Display (Serif) |
| **A-02 Cart** | 영문 브랜드명 혼선 ("AURA") | "루미에르 래디언스 세럼" 한글/정확한 브랜드명으로 교체 | Noto Sans KR (Sans-serif) |
| **A-03 PDP** | 수치 데이터 누락 | 보습 +68%, 탄력 +52% 등 임상 데이터 그래프 삽입 | Arial / Semi-bold |

---

## 4. 프롬프트 변경 로그 및 비교 평가 (평가항목 #6, #8, #11)

### 가. 프롬프트 변경 사례 (전/후)
* **초안:** `Cosmetic brand website UI design, luxury style, gold color`
* **최종:** `High-end editorial style cosmetic brand e-commerce website UI design, minimalist layout with generous whitespace, sophisticated gold and beige color palette, clean typography, luxury aesthetic --ar 16:9`
* **차이점:** 초안은 스타일이 모호하여 왜곡된 텍스트와 산만한 배치가 발생했으나, 최종 프롬프트는 'editorial style', 'generous whitespace', 'color palette'를 정교하게 지정하여 고급스러운 비주얼을 확보함.

### 나. 품질 측정 체크포인트 및 일관성 개선 지표
| 평가 체크포인트 | 변경 전 (Initial) | 변경 후 (Final) | 개선 효과 |
| :--- | :---: | :---: | :--- |
| **브랜드명 일관성** | LUMIÈRE / AURA 혼재 | LUMIÈRE SEOUL로 일괄 통일 | 브랜드 정체성 확보 |
| **상품 데이터 정합성** | 에센스 가격 12만/13만 불일치 | ₩130,000으로 전 화면 통일 | 데이터 신뢰성 확보 |
| **카피 문법 완결성** | "시간을 빛나는..." 문법 오류 | "시간이 빛나는..." 교정 완료 | 완성도 향상 |

---

## 5. 이미지 일관성 유지 규칙 및 재발 방지 전략 (평가항목 #9, #10)

### 가. 일관성 유지를 위한 규칙 (Style Guide)
1. **시드 고정 & 레퍼런스:** 동일 세트 작업 시 시드(Seed) 번호 고정 및 이미지-투-이미지(Image-to-Image) 참조 비율 0.3 유지.
2. **공통 키워드 세트:** `High-end editorial`, `minimalist layout`, `gold and beige (#C5A880)`, `Sans-serif text` 필수 포함.
3. **파일명 네이밍 규칙:** `[세트]-[화면번호]_[화면명].png` (예: `A-01_Main.png`)

### 나. 왜곡 진단 원인 분석 & 재발 방지 체크리스트
* **원인 분석:** AI 특성상 작은 텍스트 및 영문/한글 혼용 시 글자 왜곡 현상 다발.
* **재발 방지 체크리스트:**
  - [x] 생성 단계에서 글자가 포함된 프롬프트 작성을 최소화하고 레이아웃 위주 도출
  - [x] 도출된 이미지의 글자는 인페인팅으로 제거 후 Figma/Photoshop으로 텍스트 입히기
  - [x] 화면 간 상품명, 가격, 폰트 스타일 데이터의 정합성 사후 검증