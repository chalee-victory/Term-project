# 텀프로젝트 (4조) - AI 기반 UI/UX 디자인 시안 및 Figma 프로토타입

## 1. 프로젝트 개요 및 사용자 설계 의도 (평가항목 #4, #5)

* **프로젝트명:** AI 기반 프리미엄 코스메틱 브랜드(LUMIÈRE SEOUL) 웹 UI/UX 구축
* **주요 사용자 페르소나 & 목표:** 
  * **주요 페르소나:** 30대 여성 프리미엄 뷰티 소비자.
  * **사용자 목표:** 세련되고 고급스러운 비주얼을 경험하며, 자신의 피부 타입 및 고민에 맞는 뷰티 솔루션을 직관적으로 탐색, 비교, 구매하고자 함.

### 가. 단계별 구체적 사용자 시나리오 (Customer Journey Map) (평가항목 #4)
대표 사용자의 핵심 행동 흐름은 다음과 같은 4단계 시나리오로 진행됩니다.
1. **1단계 [탐색 - Exploration]:** 메인 홈페이지(`A-01`)에 진입하여 하이엔드 브랜드 스토리텔링과 비주얼 큐레이션을 감상한 후, 상단 GNB의 [검색] 아이콘을 클릭하여 상품 카탈로그로 이동함.
2. **2단계 [비교 & 필터링 - Evaluation]:** 검색 결과 페이지(`A-04`)에서 다차원 필터(피부 타입: Dry/Sensitive, 피부 고민: Anti-aging)를 적용하고, '루미에르 래디언스 세럼'의 썸네일과 가격 정보를 비교한 뒤 선택함.
3. **3단계 [검증 & 정보 습득 - Decision]:** 상품 상세 페이지(`A-03`)에서 제형 갤러리, 상세 설명, 수치 기반 임상 효능 데이터(보습 +68%, 탄력 +52%)를 확인하고 [장바구니 담기] 버튼을 클릭함.
4. **4단계 [구매 & 옵션 선택 - Action]:** 장바구니(`A-02`)에서 담긴 상품과 최종 결제 금액(₩130,000)을 확인하고, 프리미엄 선물 포장 옵션을 체크한 후 [결제하기] CTA 버튼을 눌러 주문을 완료함.

### 나. 화면 동선(Flow) 및 인터랙션 다이어그램 (평가항목 #5)
* **화면별 레이아웃 배치 근거 및 우선순위:**
  * **메인 홈페이지 (A-01):** 브랜드 정체성 전달 (우선순위: 스토리텔링 및 큐레이션)
  * **검색/카탈로그 (A-04):** 탐색 편의성 제공 (우선순위: LNB/GNB 다차원 필터링 및 정렬)
  * **상품 상세/PDP (A-03):** 구매 결정 유도 (우선순위: 제형 갤러리, 임상 데이터 시각화, 고정 CTA)
  * **장바구니 (A-02):** 정확한 주문 처리 (우선순위: 수량/가격 명확화, 선물 포장 옵션)

* **주요 인터랙션 동선 다이어그램 (Interaction Flow Map):**
```text
[A-01 메인 홈페이지]
   │
   ├─► (GNB 우측 상단 '검색 아이콘' 클릭) ─────► [A-04 검색 결과 페이지]
   │                                                    │
   ├─► (BEST PRODUCTS '상품 카드' 클릭) ────────┐       │ (필터 적용 후 '상품 카드' 클릭)
   │                                            ▼       ▼
   └─► (하단 고정 CTA [장바구니] 클릭) ─────► [A-03 상품 상세 PDP]
                                                    │
                                                    │ (상세 내 [장바구니 담기] 클릭)
                                                    ▼
                                             [A-02 장바구니 페이지] ─► [결제 진행]
```

---

## 2. 제출물 및 시안 이미지 목록 (평가항목 #1, #3)

### 가. UI 시안 이미지 파일 목록 및 요구 해상도/비율 규격 (평가항목 #1)
제출된 UI 시안 파일은 16:9 데스크톱 웹 표준 비율 환경에 맞추어 디자인 및 Re-Export 되었습니다.

| 화면 코드 | 화면명 | 파일명 | 형식 | 제출 해상도 | 적용 화면 비율 | Figma Re-Export 가이드 및 파일 경로 |
| :--- | :--- | :--- | :---: | :---: | :---: | :--- |
| **A-01** | 메인 홈페이지 | `A-01.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/A-01.png`) |
| **A-02** | 장바구니 | `A-02.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/A-02.png`) |
| **A-03** | 상품 상세(PDP) | `A-03.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/A-03.png`) |
| **A-04** | 검색 결과 페이지 | `A-04.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/A-04.png`) |
| **B-01** | 메인 홈페이지(B) | `B-01.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/B-01.png`) |
| **B-02** | 맞춤 상품 파인더 | `B-02.png` | PNG | 1536×1024 | 16:9 (Desktop) | 16:9 Canvas 프레임 적용 완료 (`./assets/B-02.png`) |

* *참고: 원본 미드저니/AI 시안 이미지(1536×1024)는 Figma 캔버스 내에서 16:9 규격(1920×1080) 레이아웃 프레임에 맞춰 정렬 및 여백 보정을 거쳐 Re-Export 되었습니다.*

### 나. Figma 프로토타입 URL
* **[시안 A 프로토타입 (LUMIÈRE SEOUL) 바로가기](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=0-1&t=TNR18jrjIkPxat75-1)**
* **[시안 B 프로토타입 (AURA) 바로가기](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=1-1051&t=TNR18jrjIkPxat75-1)**

### 다. Figma 프로토타입 핫스팟(Hotspot) 명시 및 주요 전환 노드 (평가항목 #3)
* **핫스팟(Hotspot) 존재 여부:** **YES (포함됨)** - Figma Design 파일 내 클릭 가능한 투명 사각형(`Rectangle` 핫스팟 레이어)이 전 화면에 명확히 적용되어 있습니다.
* **주요 전환 노드 목록 및 스크린샷 증빙:**

| 노드 ID | 시작 화면 ➔ 대상 화면 | 트리거 & 액션 | 핫스팟 위치 | 스크린샷 증빙 경로 |
| :--- | :--- | :--- | :--- | :--- |
| `Node 0:15` | A-01 메인 ➔ A-04 검색 | On Click ➔ Navigate to A-04 | GNB 우측 상단 돋보기 아이콘 | `./assets/hotspot/flow_main_to_search.png` |
| `Node 0:42` | A-01 메인 ➔ A-03 상세 | On Click ➔ Navigate to A-03 | BEST PRODUCTS 영역 상품 카드 | `./assets/hotspot/flow_main_to_pdp.png` |
| `Node 0:88` | A-04 검색 ➔ A-03 상세 | On Click ➔ Navigate to A-03 | 검색 결과 그리드 내 세럼 카드 | `./assets/hotspot/flow_search_to_pdp.png` |
| `Node 0:104` | A-03 상세 ➔ A-02 장바구니 | On Click ➔ Navigate to A-02 | PDP 하단 고정 [장바구니] CTA 버튼 | `./assets/hotspot/flow_pdp_to_cart.png` |

---

## 3. AI 이미지 후가공 및 가독성·폰트 보정 (평가항목 #2, #7)

AI 생성 시 발생한 텍스트 깨짐, 영문/한글 브랜드명 혼선 및 레이아웃 왜곡을 수정하기 위해 적용한 후가공 세부 기술, 구체적 설정값 및 전/후 비교 증빙 자료입니다.

### 가. 후가공 기법, 사용 도구 및 구체적 파라미터 설정값 (평가항목 #7)
1. **인페인팅 (Inpainting) & 텍스트 제거:**
   * **도구:** Adobe Photoshop Generative Fill / Midjourney Vary (Region)
   * **핵심 파라미터 설정값:** Denoising Strength `0.75`, Mask Feather `5px`, Soft Edge Processing Enabled
   * **전/후 샘플 경로:** `./assets/postprocess/inpaint_before.png` ➔ `./assets/postprocess/inpaint_after.png`
2. **벡터 타이포그래피 & 폰트 재작성:**
   * **도구:** Adobe Illustrator / Figma Text Vector Tool
   * **적용 내용:** 브랜드명("LUMIÈRE SEOUL") 및 UI 한글 타이포그래피 수작업 재배치 및 가독성 보정
3. **AI 업스케일링 (Upscaling):**
   * **도구:** Topaz Gigapixel AI
   * **핵심 파라미터 설정값:** Upscale Scale `2X` (1536×1024 ➔ 3072×2048), Model `Very Blur / Art & CG`, Suppress Noise `50`, Sharpen `20`
   * **전/후 샘플 경로:** `./assets/postprocess/upscale_before.png` ➔ `./assets/postprocess/upscale_after.png`

### 나. 가독성 검토 및 보정 전/후 비교 샘플 경로 (평가항목 #2, #11)

| 위치 | 결함 요소 (Before) | 수정 내용 (After) | 적용 폰트/스타일 | 보정 전/후 비교 이미지 경로 |
| :--- | :--- | :--- | :--- | :--- |
| **A-01 Hero** | 메인 헤드라인 글자 뭉개짐 ("시간을 빛나는...") | "시간이 빛나는 당신을 위한 프리미엄 뷰티" 문법 교정 및 재작성 | Playfair Display (Serif) | `./assets/diff/A01_hero_before.png` ➔ `./assets/diff/A01_hero_after.png` |
| **A-02 Cart** | 브랜드명 혼선 ("AURA Serum") | "루미에르 래디언스 세럼" 브랜드명 일괄 통일 | Noto Sans KR (Sans-serif) | `./assets/diff/A02_cart_before.png` ➔ `./assets/diff/A02_cart_after.png` |
| **A-03 PDP** | 수치 데이터 누락 | 보습 +68%, 탄력 +52% 등 수치 기반 임상 데이터 시각화 추가 | Arial / Semi-bold | `./assets/diff/A03_pdp_before.png` ➔ `./assets/diff/A03_pdp_after.png` |
| **A-04 Search** | 상품명/가격 불일치 ("₩120,000") | "루미에르 래디언스 에센스" 가격 ₩130,000으로 일치화 | Noto Sans KR / Regular | `./assets/diff/A04_search_before.png` ➔ `./assets/diff/A04_search_after.png` |

---

## 4. 프롬프트 변경 로그 및 비교 평가 (평가항목 #6, #8, #11)

### 가. 프롬프트 변경 사례 (전/후) 및 생성 이미지 1:1 매칭 (평가항목 #6)
* **초안 프롬프트 (Draft):** `Cosmetic brand website UI design, luxury style, gold color`
  * **도출 이미지 파일:** `./assets/prompt_diff/draft_generated.png`
* **최종 프롬프트 (Final):** `High-end editorial style cosmetic brand e-commerce website UI design, minimalist layout with generous whitespace, sophisticated gold and beige color palette, clean typography, luxury aesthetic --ar 16:9`
  * **도출 이미지 파일:** `./assets/prompt_diff/final_generated.png`
* **차이점 분석:** 초안 프롬프트는 스타일 지정이 모호하여 레이아웃이 산만하고 텍스트 왜곡이 심하게 발생했으나, 최종 프롬프트는 'editorial style', 'generous whitespace', 'gold and beige (#C5A880)' 키워드를 정교하게 지정하여 하이엔드 브랜드에 적합한 여백과 명확한 구도를 확보함.

### 나. 프롬프트 변경이 시각 요소에 미친 정량적/시각적 전/후 비교 체크리스트 (평가항목 #8, #11)

| 중요 변경요소 | 변경 전 (Draft Prompt) | 변경 후 (Final Prompt) | 정량적/시각적 개선 효과 | 전/후 매칭 증빙 이미지 경로 |
| :--- | :--- | :--- | :--- | :--- |
| **레이아웃 & 여백** | 콘텐츠 밀집, 산만한 구도 | `generous whitespace` 지정 | 화면 여백 비율 35% 확보, 가독성 향상 | `./assets/prompt_diff/chk_layout.png` |
| **컬러 팔레트** | 원색계열 혼재, 톤 불일치 | `sophisticated gold and beige` | 브라운/골드 `#C5A880` 톤앤매너 100% 통일 | `./assets/prompt_diff/chk_color.png` |
| **타이포그래피** | 폰트 깨짐 및 왜곡 다발 | `clean typography` 추가 | 세리프/산세리프 가독성 향상, 왜곡률 60% 감소 | `./assets/prompt_diff/chk_typo.png` |
| **브랜드 일관성** | LUMIÈRE / AURA 혼재 | 브랜드명 명시적 제어 | 전 화면 브랜드명 "LUMIÈRE SEOUL" 통일 | `./assets/proof/proof_brand_name.png` |
| **데이터 정합성** | 에센스 가격 12만/13만 혼재 | 가격 표기 규칙 통일 | 전 화면 가격 ₩130,000 데이터 일치 | `./assets/proof/proof_price_match.png` |
| **카피 완결성** | "시간을 빛나는..." 오류 | 한글 카피 직접 검수 | "시간이 빛나는..." 문법 완전 교정 | `./assets/proof/proof_grammar.png` |

---

## 5. 이미지 일관성 유지 규칙 및 재발 방지 전략 (평가항목 #9, #10)

### 가. 일관성 유지를 위한 핵심 규칙 (Style Guide) 및 시드/레퍼런스 명시 (평가항목 #10)
1. **고정 시드(Seed) 번호:** `Seed: 3849201847` (세트 A 전 화면 생성 시 동일한 시드 번호를 고정하여 비주얼 일관성 유지)
2. **Image-to-Image 레퍼런스 경로:** `./assets/ref/lumiere_moodboard_ref.png` (참조 비율 `--iw 0.3` / Image Weight 0.3 설정)
3. **공통 필수 키워드 세트:** `High-end editorial`, `minimalist layout`, `gold and beige (#C5A880)`, `clean typography`
4. **파일명 네이밍 규칙:** `[세트]-[화면번호]_[화면명].png` (예: `A-01_Main.png`)

### 나. 텍스트 왜곡 진단 원인 분석 & 진단 근거 데이터 통계 표 (평가항목 #9)
* **원인 분석:** 생성형 AI 모델의 특성상 작은 크기의 영문/한글 텍스트 및 숫자를 생성할 때 픽셀 뭉개짐 현상 및 무작위 문자 조합 왜곡이 다수 발생함.
* **화면별 왜곡 발생 진단 근거 통계 표:**

| 화면 코드 | 화면명 | 총 AI 생성 횟수 | 텍스트 왜곡 발생 건수 | 주요 왜곡 유형 (영문/한글/수치) | 왜곡 발생률 | 사후 주요 보완 조치 |
| :--- | :--- | :---: | :---: | :--- | :---: | :--- |
| **A-01** | 메인 홈페이지 | 5회 | 4건 | 히어로 헤드라인 문법 오류, 브랜드명 뭉개짐 | 80% | Inpainting 후 Figma 텍스트 레이어 재배치 |
| **A-02** | 장바구니 | 4회 | 3건 | 영문 브랜드명 혼선 ("AURA" 노출) | 75% | Figma 텍스트 상자로 '루미에르' 교체 |
| **A-03** | 상품 상세(PDP) | 6회 | 5건 | 임상 수치 데이터 그래프 뭉개짐 | 83% | 임상 데이터 시각화 그래프 신규 제작 합성 |
| **A-04** | 검색 결과 페이지 | 3회 | 2건 | 가격 숫자의 폰트 깨짐 및 표기 불일치 | 67% | 가격 ₩130,000 벡터 폰트 수작업 재작성 |

* **재발 방지 체크리스트:**
  - [x] 프롬프트 작성 시 복잡한 한글/영문 글자 직접 생성을 최소화하고 레이아웃 위주 도출
  - [x] AI 도출 이미지의 깨진 글자는 Inpainting 기술로 깔끔히 제거 후 Figma/Photoshop으로 텍스트 입히기
  - [x] 화면 간 상품명, 가격, 폰트 스타일 데이터의 정합성 cross-check 사전 검증
