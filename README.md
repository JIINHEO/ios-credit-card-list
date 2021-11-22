# ios-credit-card-list
realtime, firestore를 이용해 데이터를 불러오고, 입력, 수정, 삭제 등의 기능을 구현한 iOS Application  

# 기능
- realtime database 연결
- firstore database 연결
- 데이터 불러오기, 입력, 수정, 삭제

<img width="20%" src="https://user-images.githubusercontent.com/39071796/142806278-63dbac15-c8e5-47d2-b0b0-f35e70a00615.gif"/>

# 활용기술
- Firebase Realtime Database & Firebase Firestore Database
> 비관계형 클라우드 데이터 베이스   
> 실시간 (HTTP 요청이 아닌 SDK(옵저버, 스냅샷)를 통해 클라이언트와 직접 동기화하는 방식)   
> 오프라인 (로컬에 저장 후 네트워크 연결시 동기화)   
> 서버 없이 (데이터베이스와 클라이언 직접 액세스)  

- Firebase Realtime Database   
> JSON 트리로 저장   
> 정렬 또는 필터링을 할 수 있음 (동시에 두 가지 안됨)   
> 깊고 좁은 쿼리 (결과값이 가지는 하위값 모두를 반환)   
> 데이터 세트가 커질수록 쿼리의 성능이 떨어짐   
> 많은 데이터베이스이며 적은양의 데이터가 자주 변경될때 사용

- Firebase Firestore Database   
> 복합적인 고급 쿼리 기능을 제공   
> 구조화된 문서와 컬렉션의 조합을 제공   
> 단일 데이터베이스
> 정렬과 필터를 동시에 진행하는것이 가능   
> 얕고 넓은 쿼리 (특정 컬렉션의 문서만 반환)   
> 단일 데이터베이스이며 대용량 데이터가 자주 읽힐때 사용
