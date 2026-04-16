# Data Analysis Portfolio

데이터 분석 프로젝트 모음입니다.

---

## 📁 프로젝트 목록

### 🛒 E-Commerce — RFM 고객 세그먼테이션 분석

> 신규 고객 유입 둔화 상황에서 재구매율 향상을 목표로,  
> RFM 세그먼테이션 기반 고객 등급 분류 및 등급별 행동 패턴 분석

| 항목 | 내용 |
|------|------|
| 분석 기간 | 2023-12-29 ~ 2024-12-29 |
| 분석 고객 수 | 16,479명 |
| 기술 스택 | Python, MySQL, Pandas, Plotly, KMeans, PCA |

#### 파일 구조

```
E-Commerce/
├── data_pipeline/
│   └── Amazon_ETL.ipynb          # 데이터 수집 및 MySQL 적재
├── eda/
│   └── eda_analysis.ipynb        # 탐색적 데이터 분석
├── segmentation/
│   ├── RFM_segmentation.ipynb    # RFM 점수화 및 등급 분류
│   ├── platinum_gold.ipynb       # Platinum vs Gold 객단가·구매빈도 분석
│   ├── silver_bronze.ipynb       # Silver + Bronze 재구매 유도 분석
│   └── diamond_platinum.ipynb    # Diamond + Platinum 충성 고객 분석
└── retention_analysis/
    ├── Validate_hypothesis_Discount.ipynb      # 할인율과 재구매 관계
    ├── Validate_hypothesis_Category.ipynb      # 카테고리와 재구매 관계
    ├── Validate_hypothesis_PaymentMethod.ipynb # 결제수단과 재구매 관계
    └── range_retention_analysis.ipynb          # 기간별 리텐션 분석
```

---

*분석 인사이트 및 솔루션은 Notion 포트폴리오 페이지에서 확인할 수 있습니다.*
