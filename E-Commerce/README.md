# E-Commerce — RFM 고객 세그먼테이션 분석

## 기술 스택

`Python` `SQL`

---

## 파일 구조

```
E-Commerce/
├── data_pipeline/
│   └── Amazon_ETL.ipynb          # 데이터 수집 및 MySQL 적재
├── eda/
│   └── eda_analysis.ipynb        # 탐색적 데이터 분석
├── segmentation/
│   ├── RFM_segmentation.ipynb    # RFM 점수화 및 등급 분류
│   ├── platinum_gold.ipynb       # Platinum vs Gold 분석
│   ├── silver_bronze.ipynb       # Silver + Bronze 분석
│   └── diamond_platinum.ipynb    # Diamond + Platinum 분석
└── retention_analysis/
    ├── Validate_hypothesis_Discount.ipynb      # 할인율과 재구매 관계 검증
    ├── Validate_hypothesis_Category.ipynb      # 카테고리와 재구매 관계 검증
    ├── Validate_hypothesis_PaymentMethod.ipynb # 결제수단과 재구매 관계 검증
    └── range_retention_analysis.ipynb          # 기간별 리텐션 분석
```
