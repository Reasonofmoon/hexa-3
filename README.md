# 🛒 hexa-3: 소매/유통 AX 마스터클래스

> "상품 설명이 자동 생성된다" — 소매/유통 중소기업을 위한 AI 자동화 실습 과정

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Reasonofmoon/hexa-3/blob/main/notebooks/M7_RETAIL_copy_lab.ipynb)

---

## 🎯 이 과정은?

**대상**: 온라인 쇼핑몰, 오프라인 매장, 프랜차이즈, 도소매 유통 사업자  
**목표**: 상품 카피 자동 생성·재고 예측·상품 분석 3가지 핵심 자동화  
**시간**: 6시간 (강의 3h + 실습 3h)

---

## 🎯 수준별 활용 가이드

### 🟢 Starter — "5분 안에 상품 카피 초안"
1. `labs/M7-RETAIL/README.md` 열기
2. 프롬프트 복사 → ChatGPT/뤼튼에 붙여넣기
3. 상품명·특징·타겟만 수정 후 Enter
4. 상품 설명 즉시 출력 ✅ (코딩 0줄)

### 🔵 Professional — Colab 자동화
```python
# Colab Secret에 저장 (이름: GEMINI_API_KEY)
from google.colab import userdata
api_key = userdata.get('GEMINI_API_KEY')
```
1. Colab 뱃지 클릭 → 노트북 오픈
2. 런타임 → 모두 실행
3. 상품 정보 셀만 수정
4. 상품 카피 + 재고 예측 CSV 자동 다운로드

### 🟣 Enterprise — 멀티 에이전트 파이프라인
- OMC `/team 3:executor`로 분석→카피→재고→마케팅 자동화
- `AGENTS.md` 기반 브랜드 보이스 내재화
- `scripts/agents_config_validator.py` 셀프 검증

---

## ⚙️ 3모듈 커리큘럼

| 모듈 | 제목 | Colab | Labs |
|---|---|---|---|
| M1 | AX 진단 & 유통 벤치마킹 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M1_AX_diagnosis.ipynb) | [labs/M1](labs/M1-diagnosis/) |
| M7-RETAIL | 상품 카피 생성 & 재고 예측 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M7_RETAIL_copy_lab.ipynb) | [labs/M7-RETAIL](labs/M7-RETAIL/) |
| M9 | 마켓플레이스 연동 & 자동 상품 등록 | [![Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebooks/M9_marketplace_auto.ipynb) | [labs/M9](labs/M9-deploy/) |

---

## 📂 프로젝트 구조

```
hexa-3/
├── notebooks/
│   ├── M1_AX_diagnosis.ipynb         ← AX 진단 자동화
│   ├── M7_RETAIL_copy_lab.ipynb      ← 상품 카피 생성 ★
│   └── M9_marketplace_auto.ipynb     ← 마켓플레이스 자동 등록
├── labs/
│   ├── M1-diagnosis/README.md         ← 진단 프롬프트 모음
│   ├── M7-RETAIL/README.md           ← 소매/유통 실습 가이드
│   └── M9-deploy/README.md           ← 배포 체크리스트
├── scripts/
│   ├── product_copy_generator.py      ← 상품 카피 생성 (실행 가능)
│   ├── inventory_forecaster.py        ← 재고 수요 예측
│   └── agents_config_validator.py     ← AGENTS.md 검증
└── shared/
    └── retail_products_sample.csv     ← 샘플 상품 데이터 (50행)
```

---

## 🌐 hexa 시리즈
- [hexa-1](https://github.com/Reasonofmoon/hexa-1): 🏭 제조업
- [hexa-2](https://github.com/Reasonofmoon/hexa-2): 🍽️ 외식/F&B
- **hexa-3** (현재): 🛒 소매/유통
- [hexa-4](https://github.com/Reasonofmoon/hexa-4): 📚 교육/에드테크
- [hexa-5](https://github.com/Reasonofmoon/hexa-5): 🏗️ 건설/부동산
- [hexa-6](https://github.com/Reasonofmoon/hexa-6): 💼 전문서비스/IT

Made with ❤️ by [Reasonofmoon × Antigravity](https://github.com/Reasonofmoon)  
중소기업 AX 전환을 위한 실전 교육