
# 지하철 노선도 미션
[ATDD 강의](https://edu.nextstep.camp/c/R89PYi5H) 실습을 위한 지하철 노선도 애플리케이션

## Step 2. 지하철 노선 구간 조회
1. 노선 조회시 해당 노선에 속한 역 목록을 조회
* 노선 조회 시 역 목록을 함께 응답할 수 있도록 변경
* 노선에 등록된 구간을 순서대로 정렬하여 상행 종점부터 하행 종점까지 목록을 응답하기

## Step 3. 지하철 노선 구간 등록
* 지하철 구간 등록 인수 테스트 작성
* 지하철 구간 등록 기능 구현
* 구간 등록 예외 케이스 인수 테스트 작성


## Step 4. 지하철 구간 제거
* 지하철 구간 제거 기능 인수 테스트 작성
* 종점이 제거될 경우 다음으로 오던 역이 종점이 됨
* 중간역이 제거될 경우 재배치를 함
* 등록 테스트 케이스
    * 가운데에 있는 역을 제거
    * 상행 종점을 제거
    * 하행 종점을 제거
* 예외 케이스
    * 노선에 등록되있지 않은 역은 제거 불가능
    * 노선에 구간이 하나뿐이라면 제거 불가능
* 구간 등록 예외 케이스 처리 기능 구현

