<div align="center">

# 🛒 hexa-3: 소매 AX 마스터클래스

### *AI로 소매 비즈니스를 혁신하는 12주 실전 과정*

**상품카피부터 SEO 최적화까지 — 판매 데이터로 직접 검증하는 AX 커리큘럼**

[![Version](https://img.shields.io/badge/version-1.0.0-6366f1?style=for-the-badge)](https://github.com/Reasonofmoon/hexa-3)
[![Colab](https://img.shields.io/badge/Google_Colab-12개_노트북-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)](https://github.com/Reasonofmoon/hexa-3/tree/main/notebooks)
[![Sector](https://img.shields.io/badge/Sector-Retail-2563eb?style=for-the-badge&logo=shopping-cart&logoColor=white)](https://github.com/Reasonofmoon/hexa-3)
[![License](https://img.shields.io/badge/License-MIT-a78bfa?style=for-the-badge)](LICENSE)
[![Scripts](https://img.shields.io/badge/CLI_Scripts-8개-22d3ee?style=for-the-badge&logo=python)](scripts/)

> **"소매업 현장에서 AI 도구를 사용할 수 있는 인력은 전체의 7% 미만이다."**  
> hexa-3은 코딩 경험이 없는 점주·마케터도 Colab 노트북으로  
> 바로 실전 결과를 내도록 설계된 **12주 실무 중심 AX 커리큘럼**입니다.

[📗 커리큘럼 시작](notebooks/) · [🔧 스크립트 도구](scripts/) · [📂 실습 데이터](shared/) · [🐛 이슈](../../issues)

</div>

---

## 🧠 Philosophy — "왜 소매 AX인가"

기존 소매업 AI 교육의 문제: **판매 데이터가 없이 이론만 있다**.

| 기준 | 기존 AI 교육 | hexa-3 AX 커리큘럼 |
|------|-------------|-------------------|
| 데이터 | 가상의 상품 데이터 | **실제 상품 CSV** (쿠팡, 스마트스토어) |
| 결과물 | 모델 정확도 숫자 | **SEO 최적화 + 이메일 마케팅 + CRM** |
| 난이도 | Python 필수 | **Colab 실행만으로 완성** |
| 기간 | 3개월+ 이론 | **Week 1부터 실전 결과** |
| 연결성 | 개별 실습 | **W1→W12 파이프라인으로 연결** |

```mermaid
graph LR
    A[📋 W1-2 상품분석] --> B[📝 W3-4 카피생성]
    B --> C[📊 W5-6 재고예측]
    C --> D[📨 W7-8 CRM자동화]
    D --> E[🔮 W9-10 이메일마케팅]
    E --> F[🎛️ W11-12 통합대시보드]
    
    style A fill:#6366f1,color:#fff
    style F fill:#22d3ee,color:#fff
```

---

## ⚙️ 시스템 레이어

### Layer 1 · Foundation (W1~W4) — AI 기초 도구화
> **Wow**: 100개 상품의 카피를 AI가 **5초 안에** 자동 생성

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W1 | M1_AX_diagnosis.ipynb | Gemini API, 자가진단 |
| W2 | W02_product_copy.ipynb | 상품 카피, 키워드 최적화 |
| W3 | W03_seo_optimization.ipynb | SEO 최적화, 메타태그 |
| W4 | W04_channel_branch.ipynb | 채널별 카피 분기 |

### Layer 2 · Analytics (W5~W8) — 데이터 기반 의사결정
> **Wow**: 판매량·재고·경쟁사 가격을 **클릭 한 번**에 경영진 차트로 변환

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W5 | W05_sales_analysis.ipynb | pandas, matplotlib, 판매 트렌드 |
| W6 | W06_inventory_forecast.ipynb | 재고 예측, 자동 발주 |
| W7 | W07_review_sentiment.ipynb | 리뷰 감성 분석 |
| W8 | W08_email_marketing.ipynb | 이메일 마케팅 자동화 |

### Layer 3 · Intelligence (W9~W12) — 자동화 운영 시스템
> **Wow**: 재고 부족 시 **자동 발주 → 가격 조정 → 이메일 알림** 파이프라인

| 주차 | 노트북 | 핵심 도구 |
|------|--------|-----------|
| W9 | W09_crm_automation.ipynb | CRM 자동화, 고객 세분화 |
| W10 | W10_batch_processing.ipynb | 배치 처리, 스케줄링 |
| W11 | W11_retail_dashboard.ipynb | 종합 소매 대시보드 |
| W12 | W12_integrated_operation.ipynb | 통합 운영 시스템 발표 |

---

## 🎯 수준별 활용 가이드

### 🟢 Starter — "5분 안에 첫 결과"
1. [W2 노트북](https://colab.research.google.com/github.com/Reasonofmoon/hexa-3/blob/main/notebooks/W02_product_copy.ipynb) 클릭 → Colab에서 열기
2. `STORE_INFO`에 상품명·특징만 입력 (`✏️` 표시 찾기)
3. `Shift+Enter`로 위에서 아래로 실행
4. 상품 카피 + SEO 태그 자동 다운로드

> ⚠️ API 키 발급: [Google AI Studio](https://aistudio.google.com/apikey) → GEMINI_API_KEY

### 🔵 Professional — "내 상품 데이터로 실전 분석"
1. `shared/retail_products_sample.csv` 구조 확인
2. 내 상품 데이터를 같은 형식으로 준비
3. W5~W6 노트북에서 CSV 업로드 → 판매량·재고 자동 분석
4. W8 노트북에서 이메일 API 연결 → 마케팅 자동 발송

```bash
# CLI 스크립트 직접 사용
python scripts/product_copy_generator.py --input shared/retail_products_sample.csv
python scripts/inventory_forecaster.py --input data.csv --output results.csv
python scripts/email_marketer.py --input data.csv --smtp [SMTP_CONFIG]
```

### 🟣 Enterprise — "팀 표준화 & 파이프라인"
1. `scripts/M9_demo_runner.py` 실행 → 전체 파이프라인 원클릭 시연
2. GitHub Actions로 매일 자동 가격 모니터링 스케줄링
3. W11~W12를 내부 대시보드로 배포 (Flask/Streamlit)
4. hexa-1, hexa-2와 연계해서 업종 간 벤치마킹

---

## 📂 디렉토리 구조

```
hexa-3/
├── notebooks/          ← 12주 Colab 노트북 (W01~W12)
│   ├── W02_product_copy.ipynb          # 상품 카피 생성기
│   ├── W03_seo_optimization.ipynb      # SEO 최적화
│   ├── W04_channel_branch.ipynb         # 채널별 카피
│   ├── W05_sales_analysis.ipynb         # 판매량 분석
│   ├── W06_inventory_forecast.ipynb      # 재고 예측
│   ├── W07_review_sentiment.ipynb       # 리뷰 감성 분석
│   ├── W08_email_marketing.ipynb        # 이메일 마케팅
│   └── W09_crm_automation.ipynb        # CRM 자동화
├── scripts/            ← CLI 실행 가능 Python 스크립트
│   ├── product_copy_generator.py         # 상품 카피 생성기
│   ├── seo_optimizer.py                 # SEO 최적화
│   ├── inventory_forecaster.py          # 재고 예측
│   ├── email_marketer.py                # 이메일 마케팅
│   ├── crm_automator.py                # CRM 자동화
│   ├── batch_processor.py               # 배치 처리
│   ├── review_analyzer.py               # 리뷰 분석
│   └── M9_demo_runner.py               # 원클릭 데모 런처
├── shared/             ← 실습 데이터
│   ├── retail_products_sample.csv       # 상품 데이터 샘플
│   └── sales_history_sample.csv        # 판매 이력 샘플
└── labs/               ← 실습 가이드 (M2~M7)
    ├── M2-product/README.md
    ├── M3-seo/README.md
    ├── M4-channel/README.md
    └── M7-retail/README.md
```

---

## 🔧 확장 가이드

| 우선순위 | 커스터마이징 | 난이도 | 영향 범위 |
|----------|--------------|--------|-----------|
| **1st** | `STORE_INFO` 딕셔너리 수정 | ⭐ | 상품명·카테고리·날짜 |
| **2nd** | 샘플 CSV를 실제 데이터로 교체 | ⭐⭐ | 분석 결과 전체 |
| **3rd** | 이메일 SMTP 연결 | ⭐⭐ | 마케팅 자동화 |
| **4th** | 쿠팡/스마트스토어 API 인증 설정 | ⭐⭐⭐ | 상품 자동 등록 |
| **5th** | W11~W12 대시보드 서버 배포 | ⭐⭐⭐ | 팀 공유 시스템 |

---

## 🚀 빠른 시작

```bash
# 1. 레포 클론
git clone https://github.com/Reasonofmoon/hexa-3.git
cd hexa-3

# 2. 환경 설정 (로컬 실행 시)
pip install google-generativeai pandas matplotlib gspread requests

# 3. 데모 실행
python scripts/M9_demo_runner.py

# 4. 상품 카피 생성 바로 실행
python scripts/product_copy_generator.py --input shared/retail_products_sample.csv
```

또는 **Colab에서 바로 실행** (설치 불필요):  
[![W2 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-3/blob/main/notebooks/W02_product_copy.ipynb)
[![W6 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-3/blob/main/notebooks/W06_inventory_forecast.ipynb)
[![W9 열기](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/Reasonofmoon/hexa-3/blob/main/notebooks/W09_crm_automation.ipynb)

---

## 🔗 전체 AX 시리즈

| 레포 | 섹터 | 핵심 모듈 |
|------|------|-----------|
| [hexa-1](https://github.com/Reasonofmoon/hexa-1) | 🏭 제조업 | OEE, 불량분류, 예지보전 |
| [hexa-2](https://github.com/Reasonofmoon/hexa-2) | 🍽️ F&B | 리뷰분석, 메뉴카피, 재고예측 |
| **hexa-3** (현재) | 🛒 소매/유통 | 상품카피, CRM, SEO |
| [hexa-4](https://github.com/Reasonofmoon/hexa-4) | 📚 교육 | 교안자동화, 성적분석, 챗봇 |
| [hexa-5](https://github.com/Reasonofmoon/hexa-5) | 🏗️ 건설 | 계약서분석, 공정관리 |
| [hexa-6](https://github.com/Reasonofmoon/hexa-6) | 💼 IT/서비스 | 제안서, 코드리뷰, KPI |

---

## 🌐 다국어 지원

| 항목 | 현황 |
|------|------|
| 노트북 UI | 한국어 |
| 스크립트 출력 | 한국어 (컬럼 자동감지: 한/영) |
| 샘플 데이터 | 한국어 컬럼명 |
| README | 한국어 / English (예정) |

---

*AX Consulting Curriculum © 2026 | Powered by Google Gemini*