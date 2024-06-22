# MLOps

과거 kubeflow를 통해 배포가능한 BigQuery ML을 활용하는 MLOps 파이프라인 입니다.
위 파이프라인은 현재 Google Cloud의 VertexAI 이전에 존재했던 AI Platform Pipeline 에서 배포 가능한 파이프라인입니다.
위 소스 코드를 바탕으로 사용자의 다양한 데이터를 기반으로 BigQuery ML을 활용한 자동화된 MLOps 파이프라인을 만들수 있습니다.

현재는 Google CLoud의 VertexAI Pipeline으로 수정해서 구성해야합니다.

위 소스코드의 MLOps의 과정은 간단히 아래와 같이 구성되어있습니다.

1. GCS 버킷생성
2. BigQuery 데이터세트 생성
3. 데이터 준비 (정제가 끝난 데이터)
4. 모델 생성
5. 모델 버전 관리
6. 모델 gcs Export
7. 모델 배포

상세한 설명은 아래 URL참고 가능합니다.
- https://medium.com/google-cloud/how-to-build-an-end-to-end-propensity-to-purchase-solution-using-bigquery-ml-and-kubeflow-pipelines-cd4161f734d9
- https://github.com/GoogleCloudPlatform/analytics-componentized-patterns/blob/master/retail/propensity-model/bqml/README.md
