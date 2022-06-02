# Analytics-on-AWS
 AWS 분석 플랫폼 구축 - AWS Glue, Amazon Athena, Amazon EMR, Amazon QuickSight, AWS Lambda 및 Amazon Redshift와 같은 여러 분석 서비스를 사용하여 데이터를 수집, 저장, 변환, 서빙

<img width="996" alt="image" src="https://user-images.githubusercontent.com/15190903/171544423-3803ac48-c147-4b35-9f0f-600c99ced5c8.png">
출처: https://catalog.us-east-1.prod.workshops.aws/workshops/44c91c21-a6a4-4b56-bd95-56bd443aa449/ko-KR

# 학습결과
- 서버리스 데이터 레이크 아키텍처 설계
- Amazon S3를 스토리지를 사용하여 데이터를 Data Lake로 수집하는 데이터 처리 파이프라인 구축
- 실시간 스트리밍 데이터에 Amazon Kinesis 사용
- AWS Glue를 사용하여 데이터세트 자동 분류
- AWS Glue 개발 엔드포인트에 연결된 Amazon SageMaker Jupyter 노트북에서 대화형 ETL 스크립트 실행
- EMR을 사용하여 Spark 변환 작업 실행
- Glue에서 Amazon Redshift로 데이터 적재
- Amazon Redshift 모범 설계 사례 소개
- Amazon Athena를 사용하여 데이터를 쿼리하고 Amazon QuickSight를 사용하여 시각화

# 작업순서
1. Kinesis firehose를 사용하여 데이터를 수집 S3에 저장
2. AWS Glue 데이터 카탈로그에 테이블을 카탈로그화
3. Glue ETL/EMR을 사용하여 데이터를 변환 
4. Athena와 Quicksight를 사용하여 데이터를 쿼리 및 시각화

-> 서버리스 분석 배포 모델에서 소스와 비즈니스 대시보드 사이의 end to end 아키텍처 제공
