# Detecting Anomalies in Wafer Manufacturing

[캐글 링크](https://www.kaggle.com/datasets/arbazkhan971/anomaly-detection/data)

## About Dataset

해당 데이터는 인도의 주요 웨이퍼(반도체) 제조업체 중 하나의 데이터셋이다. 

수집된 데이터셋에서 feature는 보안으로 인해 이름이 익명으로 처리되었으며, 이를 이해하려면 깊은 도메인 지식이 필요하다. 그리고 이는 1558가지 features들이 존재한다. 

본 캐글 해커톤에서 AUC를 평가지표로 사용하여 anomalies를 올바르게 분류하는 ML/DL 모델 생성을 추구한다. 

### Dataset Description:

- Train.csv - 1763 rows x 1559 columns
- Test.csv - 756 rows x 1558 columns
- Sample Submission.csv - Please check the Evaluation section for more details on how to generate a valid submission

### Attribute Description:

__Feature_1 ~ Feature_1558__ : 제조 기계에서 수집된 다양한 속성을 나타냅니다.

__Class - (0 or 1)__ : 양품과 불량품 클래스 라벨을 나타냅니다. 

### Skills:

High Dimensionality Data, Overfitting-vs-Underfitting

Advanced Classification Techniques, Gradient Boosting, Neural Nets, etc

Feature engineering, Feature Selection Techniques

Optimizing Area under the curve(AUC) to generalize well on unseen data