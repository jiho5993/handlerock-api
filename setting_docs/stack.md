# 사용 기술과 선정 이유

## JPA
JPA는 자바 스프링에서 사용되는 ORM 도구임</br>
ORM은 객체와 관계형 데이터베이스의 데이터를 자동으로 매핑해줌</br>
즉, DB에 들어있는 데이터(row)를 클래스로 표현 가능

### JPA 사용 이유
- 일부 기능을 제외하고는 SQL을 직접 작성하지 않아도 됨
- 직관적인 코드 작성 가능
- 유지보수 용이

---

## Flyway
Flyway는 데이터베이스 마이그레이션 도구임</br>
서비스를 만드는 동안 설계의 오류나 추가 기능으로 인해 데이터베이스의 수정이 발생할 수 있음</br>
필요한 경우에만 마이그레이션을 진행하여 데이터베이스 수정

### Flyway 사용 이유
- 데이터베이스의 버전 관리
- 데이터베이스의 변경 사항을 추적
- 데이터베이스의 변경 사항을 팀원들과 공유

참고자료 : [https://sabarada.tistory.com/193](https://sabarada.tistory.com/193)