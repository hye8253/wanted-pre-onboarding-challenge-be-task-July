# :: 원티드 프리온보딩 챌린지 백엔드 코스 사전과제 안내
## 1-1) 사전과제 진행 가이드
- 아래 총 5 문제에 대한 해설을 해당 레포지토리를 fork 한 후 각 문제에 해당하는 파일에 작성해주세요.
- 문제 해설에 대한 정해진 양식은 없으며, 최대한 자세히 해설해주시면 더욱 좋습니다.
- 문제 유형은 해당 코스와 무관하게 면접을 준비한다면 알고 있으면 좋은 주제들을 몇 가지 선정하였습니다.

<br>

## 1-2) 사전 과제 
- (1) 동시에 같은 `DB Table row` 를 업데이트 하는 상황을 방어하기 위해 어떻게 개발하실 건지 설명해주세요.
- 트랜잭션을 사용한다. 테이블에 트랜잭션을 부여하고 데이터베이스 작업의 원자성, 일관성, 독립성, 지속성을 보장한다.

- (2) `TCP` 와 `UDP` 의 차이를 작성해주세요.
- TCP는 연결지향성이고 UDP 비연결성이다. (여기까지만 기억해서 더 찾아봄)
- TCP 는 신뢰성과 순서 보장이 필요한 경우에 적합하며 통신하기 전에 먼저 연결을 설정하고 데이터를 주고 받는다.
- UDP 는 연결 설정 과정 없이 데이터를 주고 받으며 신속성과 간결성이 중요한 경우에 적합하다.
- TCP 는 데이터의 신뢰성을 보장하기 위해 오버헤드 발생, 전송 속도가 상대적으로 느릴 수 있다.
- UDP 는 데이터의 빠른 전송을 위해 추가적인 오버헤드가 없어 전송 속도가 빠르다.
- TCP 는 스트림 지향적, UDP는 데이터그램 지향적.

- (3) 웹 브라우저에 `네이버` 를 검색하고 화면에 네이버 화면이 출력이 될 때 까지 내부적으로 어떤 동작들이 수행이 되는지 설명해주세요.
- 구체적으로 설명을 못해서 검색 후 정리해보았다.
- DNS 조회. 입력한 주소인 '네이버'를 IP 주소로 변환하기 위해 DNS 조회 수행 (DNS는 도메인 이름을 해당 도메인의 IP 주소로 매핑해주는 역할을 한다.)
- 서버 연결. 웹 브라우저는 얻어낸 "네이버"의 IP 주소를 사용하여 해당 서버와 TCP/IP 연결을 수행한다.
- HTTP 요청 전송. 서버와 연결이 성공하면, 웹 브아루저는 HTTP 요청 메시지를 생성하여 서버로 전송한다. 요청 메세지에는 (GET,POST등 ) URL 등 정보가 포함된다.
- 서버 응답. HTTP 요청을 처리하고 요청에 따라 필요한 데이터를 생성하여 응답을 생성한다. HTTP 응답 메시지로 패키징하여 클라이언트(브라우저)에게 전송
- 응답 처리 및 렌더링. HTTP 응답 수신 후, 웹 페이지 렌더링한다. HTML, CSS, JavaScript 코드를 해석하고, 웹 페이지의 구조와 디자인을 생성, 웹 페이지의 렌더링이 완료되면, 브라우저는 화면에 네이버 홈페이지를 출력

- (4) 본인이 주력으로 사용하는 언어에서 설계적 결함 한 가지를 작성해주세요.
- 다시 찾아서 쓰기 

- (5) 본인이 주력으로 사용하는 언어에서 자료구조와 관련 된 클래스가 내부적으로 어떻게 동작하는지 한 가지 사례를 정하여 작성해주세요. ex) `ArrayList`, `HashMap` 등등
- 
