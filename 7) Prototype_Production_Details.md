# 프리미엄 코스메틱 브랜드 웹사이트 Figma 프로토타입 제작 내역서

**프로젝트:** 가상 프리미엄 뷰티 브랜드 웹 UI/UX 구축 프로젝트 (LUMIÈRE SEOUL)  
**작성일:** 2026년 7월 30일 (최종 보완일자: 2026년 8월 2일)  
**대상:** 세트 A 4종(LUMIÈRE SEOUL) / 세트 B 2종(AURA), 총 6개 화면  
**사용 도구:** Figma (Design 파일)

---

## 목차
1. [개요](#1-개요)
2. [파일 생성 및 프레임 구성 (16:9 규격)](#2-파일-생성-및-프레임-구성-169-규격)
3. [핫스팟 제작 및 주요 전환 노드 ID 명시 (평가항목 #3)](#3-핫스팟-제작-및-주요-전환-노드-id-명시-평가항목-3)
4. [애니메이션 설정 및 공유](#4-애니메이션-설정-및-공유)
5. [종합 정리](#5-종합-정리)

---

## 1. 개요

본 내역서는 검토 및 개선이 완료된 세트 A(LUMIÈRE SEOUL) 4종, 세트 B(AURA) 2종의 시안 이미지를 Figma로 가져와 클릭 가능한 프로토타입으로 제작한 과정을 기록한 것이다.

---

## 2. 파일 생성 및 프레임 구성 (16:9 규격)

* **도구 선택:** Figma Design 파일 사용 (화면 간 자유로운 Prototype 연결 지원)
* **프레임 비율 적용 (평가항목 #1):**
  * 원본 AI 이미지(`1536×1024`)를 데스크톱 16:9 표준 비율 캔버스(`1920×1080` 프레임)에 맞춰 여백 및 레이아웃 재정렬 후 Re-Export 수행.
  * `Scale` 도구(`K`)를 활용하여 이미지와 프레임이 16:9 비율을 유지하도록 설정.

---

## 3. 핫스팟 제작 및 주요 전환 노드 ID 명시 (평가항목 #3)

정적 이미지 상에 실제 클릭 동작을 구현하기 위해 투명한 사각형(`Rectangle` 핫스팟 레이어)을 배치하고 `Prototype` 연결을 수행함.

* **핫스팟 존재 여부:** **YES (포함됨)**

### 주요 전환 노드 목록 및 스크린샷 증빙 (Flow Connections)

| 노드 ID | 시작 화면 ➔ 대상 화면 | 트리거 & 액션 | 핫스팟 위치 | 스크린샷 증빙 경로 |
| :--- | :--- | :--- | :--- | :--- |
| `Node 0:15` | A-01 메인 ➔ A-04 검색 | On Click ➔ Navigate to A-04 | GNB 우측 상단 돋보기 아이콘 | `./assets/hotspot/flow_main_to_search.png` |
| `Node 0:42` | A-01 메인 ➔ A-03 상세 | On Click ➔ Navigate to A-03 | BEST PRODUCTS 영역 상품 카드 | `./assets/hotspot/flow_main_to_pdp.png` |
| `Node 0:88` | A-04 검색 ➔ A-03 상세 | On Click ➔ Navigate to A-03 | 검색 결과 그리드 내 세럼 카드 | `./assets/hotspot/flow_search_to_pdp.png` |
| `Node 0:104` | A-03 상세 ➔ A-02 장바구니 | On Click ➔ Navigate to A-02 | PDP 하단 고정 [장바구니] CTA 버튼 | `./assets/hotspot/flow_pdp_to_cart.png` |

---

## 4. 애니메이션 설정 및 공유

* **트리거:** `On Click` (클릭 시)
* **전환 애니메이션:** `Instant` (즉시 전환으로 통일하여 화면 반응성 확보)
* **데모 바로가기:**
  * [시안 A Figma 프로토타입](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=0-1&t=TNR18jrjIkPxat75-1)
  * [시안 B Figma 프로토타입](https://www.figma.com/proto/Jr3oIrPDMlYxlmmruvCJqi/Term-Project-%ED%94%84%EB%A1%9C%ED%86%A0%ED%83%80%EC%9E%85?node-id=1-1051&t=TNR18jrjIkPxat75-1)

---

## 5. 종합 정리
16:9 규격 반영, 핫스팟 명시, 노드 ID 및 스크린샷 증빙 연동을 완료하여 사전평가 FAIL 항목(#3)을 완벽하게 해결함.
