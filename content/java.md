# http

**:Contents**
1. [REST_API란](#REST_API란)
2. [HTTP_METHOD](#HTTP_METHOD)
3. [API 개발을 하면서 주의하는거나 신경쓰는 부분은](#API_개발을_하면서_주의하는거나_신경쓰는_부분은)
4. [HTTP_status_code](#HTTP_status_code)
5. [HTTP의_약점](#HTTP의_약점)
6. [HTTPS](#HTTPS)
7. [SSL계층](#SSL계층)

### REST_API란
* REST API(REpresentational State Transfer)는 웹상에서 사용되는 여러 리소스를 HTTP URI로 표현하고, 
* 해당 리소스에 대한 행위를 HTTP Method로 정의하는 방식을 말합니다.
* rest full 규약을 지켜서 개발하는 것을 rest api라고 합니다.
  * 대표적으로  self-descriptive 와 hateos등이 있습니다.
  * rest-api 설계를 할때 url에 동사를 사용하지 않고 명사를 사용하는 등에 rest api 디자인 가이드가 있습니다.