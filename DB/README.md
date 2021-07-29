## DB Study

### DML 종류

- Select 데이터를 조회할 때 사용한다.
- Insert 데이터를 입력할 때 사용한다.
- Update 데이터 내용 변경 할 때 사용한다.
- Delete 데이터 내용 삭제할 때 사용한다.

### DDL 종류

- Create 테이블 생성
- Drop 테이블 삭제
- Alter 테이블 수정
- Truncate 테이블에 있는 모든 데이터 삭제

### SELECT 구문 수행 순서

- From – Where – Group By – Having – Select – Order By

### JOIN ?

조인 – 둘 이상의 테이블을 연결해 데이터를 검색하는 방법, 연결하려면 테이블들이 적어도 하나의 칼럼을 공유하고 있어야 함. 이 공유하고 있는 컬럼을 PK 또는 FK값으로 사용

### JOIN 을 왜 사용 ?

정규화 ( 불필요한 데이터의 정합성을 확보하고, 이상현상 발생을 피하기 위해, 테이블을 분할해서 생성하는 것을 말함 )

### inner join & outer join

> > inner join

```sql

SELECT A.ID , A.ENAME, A.KNAME
FROM A INNER JOIN B
ON A.ID = B.ID;

```

> > outer join

```sql


```

### equal join & non-equal join

### outer join 종류

### natural join ?

### self join ?

### self join 을 왜 사용 ?

### Union || Join

### subQuery ?

### 오라클 사용 객체 종류 ?

### 제약 조건 이란 ??

#### 제약조건의 사용 이유

#### 제약조건의 종류 및 간단한 설명

#### 테이블에 왜 PK 설정 ?

#### FK 제약 조건은 무엇, 왜 사용 ?

#### 트랜젝션 ?

하나의 논리적 기능을 수행하기 위한 작업의 단위로, DB의 일관된 상태로 변환시키는 기능을 수행한다. 트랜잭션은 전체가 수행되거나 또는 전혀 수행되지 않아야 한다.

#### 트랜젝션 || 쓰레드

#### View ? & 사용하는 목적

#### index ? & 장점과 단점 & 종류

#### 프로시져란 ? 함수란 ? 패키지란 ?

#### 트리거란 ?
