# Step04

## Cold / Hot Observable, Subject

### Cold / Hot Observable
#### 차가운 Observable
- 게으른 접근법
- subscribe() 를 실행해야 데이터를 발행  
  > ex> 
  > - 웹 요청, 데이터베이스 쿼리와 읽기 등
  > - 내가 원하는 URL이나 데이터를 지정하면 그때부터 서버나 데이터베이스에 요청을 보내고 결과를 받아오는 경우 
- 준비된 데이터를 처음부터 발행함

#### 뜨거운 Observable
- 
- 만들어지는 즉시 데이터를 발행
- 여러 구독자를 고려 가능하나, 모든 데이터에 대한 신뢰성 보장 불가능
  > ex> 
  > - UI 이벤트 (마우스 클릭, 화면 클릭 등)
  > - 주식 데이터 등
  > - 
- 


### 참고
> - []()
> - []()
> - []()
> - []()

