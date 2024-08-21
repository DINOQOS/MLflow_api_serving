# MLflow 기반 모델 관리 및 서빙 프로젝트

## 프로젝트 개요
이 프로젝트는 MLflow를 활용하여 최적의 모델을 만들고, FastAPI를 통해 모델을 서빙하는 과정을 다룹니다. Docker, Minio, Postgresql, Tensorflow, Keras, Pandas, RDS와 같은 기술을 사용하여 모델의 실험 추적, 튜닝, 저장 및 서빙을 체계적으로 관리합니다.

## 사용 기술
![image](https://github.com/user-attachments/assets/53b66853-c9be-44bd-8b54-e6f65ca277be)

- **MLflow**: 모델의 하이퍼파라미터 최적화, 로깅, 저장 등을 관리.
- **FastAPI**: 모델을 API 형태로 서빙.
- **Docker**: 컨테이너화를 통해 환경을 관리 및 배포.
- **Minio**: S3 호환 오브젝트 스토리지로 모델 아티팩트 관리.
- **Postgresql**: 실험 데이터 및 메타데이터 저장.
- **Tensorflow/Keras**: 딥러닝 모델 생성.
- **Pandas**: 데이터 처리 및 분석.
- **RDS**: AWS RDS를 사용한 데이터베이스 관리.

## 프로젝트 목표
MLflow를 통해 AI 모델의 최적화, 로깅, 저장 등을 체계적으로 관리하고, FastAPI를 활용해 모델을 안정적으로 서빙하는 것이 목표입니다. Docker를 사용하여 이미지를 만들고 배포함으로써 DevOps의 개념도 함께 이해하고자 했습니다.

## 주요 작업
1. **모델 관리**: MLflow를 활용하여 모델의 실험 추적, 하이퍼파라미터 튜닝, 버전 관리.
2. **서빙**: FastAPI를 사용하여 모델을 API 형태로 서빙.
   - Batch Serving  
     ![image](https://github.com/user-attachments/assets/a28923ba-bff1-4090-9de2-d06c5e2eb82f)
   - API Serving  
     ![image](https://github.com/user-attachments/assets/c651ab9a-c1d6-4a8e-ab69-4079049b1e84)
3. **Docker 이미지 생성**: Docker를 통해 모델 서빙 환경을 컨테이너화.
4. **데이터베이스 관리**: Postgresql을 사용하여 실험 데이터와 메타데이터를 저장하고, RDS를 통해 데이터베이스를 관리.
5. **모델 아티팩트 저장**: Minio를 활용하여 모델 파일을 안전하게 저장.

## MLOps 서비스 구성도
![Untitled](https://github.com/user-attachments/assets/dd3ede86-800c-44fc-997d-7729ca930df7)

## 어려웠던 점
- **MLflow 학습 자료 부족**: MLflow 관련 자료가 많지 않아, 외국의 영상과 공식 문서를 참고하여 학습했습니다.
- **Docker 활용의 어려움**: Docker 문법이 복잡했지만, 꾸준한 질문과 학습을 통해 문제를 해결했습니다.

## 느낀점
이제 API 형태로 모델을 서빙할 수 있는 자신감을 얻게 되었습니다. 앞으로는 지금까지 만든 모델들을 꾸준히 적용해보며, 새로운 모델도 시도할 예정입니다.

## 앞으로의 계획
- 기존 모델들의 실험 추적 및 튜닝 작업을 지속할 계획입니다.
- 새로운 AI 모델을 개발하고, 이를 FastAPI를 통해 서빙하여 실용적인 프로젝트로 확장할 계획입니다.

## 참고
https://www.youtube.com/watch?v=8e9CCr9urd4&list=PLQqR_3C2fhUUkoXAcomOxcvfPwRn90U-g 
https://school.programmers.co.kr/learn/courses/18085/18085-%EB%A7%88%ED%82%A4%EB%82%98%EB%9D%BD%EC%8A%A4-%EA%B0%9C%EB%B0%9C%EC%9E%90%EA%B0%80-%EC%95%8C%EB%A0%A4%EC%A3%BC%EB%8A%94-mlops-%ED%95%99%EC%8A%B5%EB%B6%80%ED%84%B0-%EC%84%9C%EB%B9%99%EA%B9%8C%EC%A7%80 


## 자세한 내용
자세한 내용은 다음 블로그에서 확인하실 수 있습니다.  
[MLflow 관련 블로그 포스트](https://dinoqos.tistory.com/category/Tech%20Stack/MLflow)
