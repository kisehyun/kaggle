<img width="982" alt="image" src="https://user-images.githubusercontent.com/49870977/224987483-814f7774-ea91-4b05-bc12-eb5f5e106d24.png">

Lesson Learned
- 다른 submission 파일 중에 더 높은 score가 있었음 -> validation 성능만으로 모델평가를 하다보니 불가피한 문제
- NN도 시도해보았지만 CatBoost, LightGBM, XGBoost를 weighted ensemble한 예측값이 성능이 제일 좋았음
- 다른 데이터셋을 같이 사용하거나 train, test를 concat한 후 전처리한 코드가 많이 보임 -> data leakage를 고려안하는듯?, 물론 정규 대회면 다들 고려했을 것 같음
