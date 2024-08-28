# REST API

REST API(Representational State Transfer Application Programming Interface)는 웹 애플리케이션이 상호 작용하는 데 사용되는 API 디자인의 한 종류이다. REST API는 HTTP를 기반으로 하여 리소스(데이터)를 처리하고, 특정 규칙에 따라 클라이언트와 서버 간의 통신을 효율적으로 수행할 수 있도록 설계되었음

### REST API의 주요 개념

1. 리소스(Resource) : REST에서는 모든것을 리소스로 취급함. 예를 들어, 사용자, 글, 상품 등이 리소스가 됨. 각 리소스는 고유한 UPI(Uniform Resource Identifier)를 통해 식별된다.
2. HTTP 메서드
    - GET : 리소스 조회
    - POST : 리소스 생성
    - PUT : 리소스 업데이트
    - DELETE : 리소스 삭제
    - PATCH : 리소스의 일부 업데이트
3. URI(Uniform Resource Identifier) : 각 리소스는 고유한 URI로 식별됨. 예를 들어 ‘[https://example.com/users/123](https://example.com/users/123)’ 는 ‘id’가 123인 사용자를 가리킬 수 있음.
4. stateless : 각 요청은 독립적이며, 서버는 이전 상태를 기억하지 않음. 모든 정보는 요청에 포함되어야 함
5. 표현 : 서버는 요청된 리소스에 대한데이터를 다양한 포맷으로 클라이언트에 반활할 수 있음. (JSON, XML 등)

### REST API의 장점

- 유연성 : 다양한 클라이언트가 동일한 API를 사용할 수 있음
- 확장성 : 새로운 기능이나 리소스를 추가할 대 기존 시스템에 큰 변경 없이 확장이 가능함
- 웹 표준 기반 : HTTP 프로토콜을 사용해서 방화벽이나 키타 네트워크 인프라와 잘 통합됨