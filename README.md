# shell script를 이용한 배포 전처리 자동화
## Klounge업무 처리중 진행중 반복되는 작업을 자동화 처리하는 첫번째 간단한 프로젝트
0. 자동화를 위한 연습용 테스트 파일들도 같이 업로드 

1. makebuildFile에 연습한것들을 조합하여 업무 자동화 

2. makebuildFile을 만들기위한 practice 모음집

3. makeBuildFile에 주석처리로 작동 설명 진행

## 사용자와의 대화형식 shell script형식은 지양한다
- 대화형식이 아닌 선택형식으로 shell script를 구성해야한다.
- 최대한 간단하게 shell script를 구성한다.

## 이후 목표 
- 다국어파일 병합 후 배포 과정 자동화 (사람의 손을 거치는 경우 오류의 확률 증가)
- makeBuildFile 처리과정에 또다른 shell script 파일을 생성하여 해당 파일을 업로드 하는 곳에서 실행하면 한번에 모든것을 처리해주는 환경 구현
