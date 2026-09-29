---
template_id: metabuild_project_guide
category: brand
summary: 메타빌드(주) 사내 프로젝트 수행 가이드 스타일 — 오렌지 헤더 밴드와 레드 포인트를 쓰는 실무형 기업 문서 톤
keywords: [기업보고서, 프로젝트가이드, 오렌지브랜드, 문서형, IT/SI]
primary_color: "#ED7D31"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1280
source_canvas_height: 720
source_viewbox: "0 0 1280 720"
replication_mode: fidelity
native_structure_mode: structured
placeholders:
  01_cover: ["{{TITLE}}", "{{SUBTITLE}}", "{{DATE}}", "{{AUTHOR}}"]
  02_chapter: ["{{CHAPTER_NUM}}", "{{CHAPTER_TITLE}}", "{{CHAPTER_DESC}}"]
  02_toc: ["{{TITLE}}", "{{TOC_ITEM_1_TITLE}}", "{{TOC_ITEM_1_DESC}}", "{{TOC_ITEM_2_TITLE}}", "{{TOC_ITEM_2_DESC}}", "{{TOC_ITEM_3_TITLE}}", "{{TOC_ITEM_3_DESC}}", "{{TOC_ITEM_4_TITLE}}", "{{TOC_ITEM_4_DESC}}"]
  03_content: ["{{PAGE_TITLE}}", "{{CONTENT_AREA}}"]
  03a_content_info_card: ["{{PAGE_TITLE}}", "{{KEY_NOTE_1}}", "{{KEY_NOTE_2}}", "{{KEY_NOTE_3}}", "{{CONTENT_AREA}}"]
  03b_content_table: ["{{PAGE_TITLE}}", "{{TABLE_R1_C1}}", "{{TABLE_R1_C2}}", "{{TABLE_R1_C3}}", "{{TABLE_R1_C4}}", "{{TABLE_R2_C1}}", "{{TABLE_R2_C2}}", "{{TABLE_R2_C3}}", "{{TABLE_R2_C4}}", "{{CONTENT_AREA}}"]
  03c_content_dual_image: ["{{PAGE_TITLE}}", "{{IMAGE_LEFT_CAPTION}}", "{{IMAGE_RIGHT_CAPTION}}"]
  04_ending: ["{{THANK_YOU}}", "{{CLOSING_MESSAGE}}", "{{CONTACT_INFO}}"]
---

# 메타빌드 프로젝트 수행 가이드 — Design Specification

## I. Template Overview

메타빌드(주) 사내 IT/SI 프로젝트 수행 가이드 문서에서 뽑은 스타일. 용도는 프로젝트 수행 가이드, 사내 기술 문서, 버전관리형 보고서. 톤은 실무적·문서형이며, 화려한 장식보다 오렌지 헤더 밴드 + 레드 라벨 텍스트로 구획을 명확히 나누는 것이 핵심이다. 테마 모드는 light.

한눈에 이 템플릿을 알아보게 하는 요소: 페이지 상단을 가로지르는 오렌지 그라디언트 헤더 밴드(다이아몬드 패턴 + 레드 언더라인)와, 그 아래 흰 배경 위에 놓이는 절제된 정보 블록들이다.

## II. Color Scheme

| 역할 | HEX | 용도 |
|---|---|---|
| Primary (오렌지) | `#ED7D31` | 헤더 밴드, TOC 번호 배지, "Key notes" 탭, 엔딩 배경 |
| Secondary (블루) | `#4472C4` | 정보 카드/강조 텍스트 보조색 |
| Accent (레드) | `#C00000` | 밴드 하단 언더라인, § 불릿 라벨, 노트 텍스트 |
| 배경 | `#FFFFFF` | 본문 배경 기본값 |
| 본문 텍스트 | `#262626` | 일반 본문 |
| 보조 텍스트 | `#595959` / `#8C8C8C` | 캡션, 페이지 번호, 플레이스홀더 안내문 |
| 표 헤더 배경 | `#DEEBF7` | 표 헤더 행 |

## III. Typography

기본 스택 `Pretendard, "Malgun Gothic", sans-serif` 그대로 사용(레포 폰트 정책). 원본 소스는 맑은 고딕/Calibri였으나 이 저장소에서 SVG로 저작되는 모든 덱은 Pretendard로 고정된다. 위계는 폰트 교체가 아니라 크기·굵기로만 구성한다.

## IV. Signature Design Elements

- **헤더 밴드**: 모든 본문형 레이아웃 상단에 반복되는 오렌지 다이아몬드 패턴 이미지(`header_band.png`) + 4px 레드 언더라인. 표지는 밴드를 페이지 중단(붉은 띠 형태)에 배치해 타이틀을 강조한다.
- **로고 배치**: 본문형 페이지는 우하단에 소형 로고 마크(`logo_mark.png`), 표지·엔딩 페이지는 워드마크(`logo_wordmark.png`)를 더 크게 배치한다.
- **TOC 번호 배지**: 오렌지 원형 배지(01~04) + 연결선으로 챕터 목록을 표현한다.
- **Key notes 패널**: 좌측에 오렌지 탭이 달린 회색 패널을 두고 그 안에 레드 "§" 불릿으로 핵심 노트를 나열한다 — 정보 카드형 본문 페이지의 시그니처 구성.
- **표 스타일**: 헤더 행은 옅은 블루(`#DEEBF7`) 배경, 본문 행은 흰 배경에 회색(`#808080`) 테두리 — 개정이력표 등 문서관리형 표에 사용.
- **엔딩 페이지**: 유일하게 배경 전체를 오렌지로 채우는 페이지 — 다른 모든 페이지는 흰 배경 위에 밴드만 사용한다.
- **밀도 리듬**: 본문 페이지는 상단 밴드(92px) + 여백 있는 콘텐츠 영역으로 구성되는 "breathing" 리듬. 정보카드/표 변형만 좌측 패널·표 헤더로 약간 더 조밀해진다.

## V. Page Roster

| # | 파일 | 페이지 유형 | Master/Layout | 설명 |
|---|---|---|---|---|
| 1 | `01_cover.svg` | 표지 | `master-default` / `cover` | 중단 오렌지 밴드 위 중앙 타이틀·서브타이틀, 좌하단 작성일/작성자 미니 정보, 우하단 워드마크 |
| 2 | `02_chapter.svg` | 챕터 구분 | `master-default` / `chapter` | 상단 대형 오렌지 밴드(160px)에 챕터 번호+제목, 본문 없는 심플 구분 페이지 |
| 3 | `02_toc.svg` | 목차 | `master-default` / `toc` | 오렌지 원형 번호 배지 4개 + 연결선, 우측에 항목 제목/설명 텍스트 |
| 4 | `03_content.svg` | 본문(기본) | `master-default` / `content` | 상단 밴드 + 자유 본문 영역, 가장 유연한 기본형 |
| 5 | `03a_content_info_card.svg` | 본문(노트 패널) | `master-default` / `content_info_card` | 좌측 "Key notes" 오렌지 탭 패널 + 우측 자유 본문 |
| 6 | `03b_content_table.svg` | 본문(표) | `master-default` / `content` | `03_content`과 동일 Layout을 공유하며, 개정이력형 표 예시를 슬라이드 로컬 장식으로 포함 |
| 7 | `03c_content_dual_image.svg` | 본문(좌우 비교) | `master-default` / `content_dual_image` | 좌우 이미지 슬롯 2개 + 캡션, 화면 비교/전후 비교용 |
| 8 | `04_ending.svg` | 마무리 | `master-default` / `ending` | 전면 오렌지 배경, 중앙 감사 인사 + 연락처 (원본 소스에는 없던 페이지로, 동일 톤으로 신규 저작) |

## VI. Assets

| 파일 | 원본 | 크기(대략) | 용도 |
|---|---|---|---|
| `images/header_band.png` | 소스 `image1.png` | 1280×92~160(스트레치) | 상단 헤더 밴드 |
| `images/bg_texture.jpeg` | 소스 `image3.jpeg` | 1280×720 | 배경 텍스처(엔딩 외에는 좌우비교 페이지의 사진 자리표시자로 재사용) |
| `images/logo_mark.png` | 소스 `image4.png` | 89.56×22.94 | 본문 페이지 우하단 소형 로고 |
| `images/logo_wordmark.png` | 소스 `image2.png` | 138.17×40 | 표지·엔딩 페이지 대형 로고 |

원본 소스의 `image5~30`(ESB 제품 화면 캡처 등 프로젝트 전용 샘플)은 재사용 가능한 템플릿 장식이 아니므로 제외했다.

## VII. Placeholder Overrides

각 페이지 프론트매터의 `placeholders:` 블록 참고. `03a`/`03b`/`03c`는 이 템플릿 고유의 노트·표·캡션 구성 때문에 표준 어휘 대신 `{{KEY_NOTE_n}}`, `{{TABLE_Rn_Cn}}`, `{{IMAGE_LEFT_CAPTION}}` / `{{IMAGE_RIGHT_CAPTION}}`을 사용한다. TOC는 표준 인덱스 규칙(`{{TOC_ITEM_n_TITLE}}` / `{{TOC_ITEM_n_DESC}}`)을 그대로 따른다.
