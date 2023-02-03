# commerce-service

# 개요
간단한 커머스 프로젝트

Use : Spring, Jpa, Mysql, Redis, Docker, AWS

셀러와 구매자 사이를 중개해 주는 커머스 서버를 구축한다.

----

### 회원
- [ ] 이메일을 통해서 인증번호를 통한 회원가입

### 고객
- [ ] 회원 가입
- [ ] 인증(이메일)
- [ ] 로그인 토큰
- [ ] 로그인 토큰을 통한 제어 확인 (JWT, Filter을 사용)
- [ ] 결제 하기위한 수단(돈에 관련된 것)
- [ ] 예치금 관리

### 셀러
- [ ] 상품 CRUD
- [ ] 매출 조회
- [ ] 잔액 추가 (정산 전용)

### 주문 서버

- [ ] 상품 등록, 수정, 삭제 

### 구매자

- [ ] 장바구니를 위한 Redis 연동
- [ ] 상품 검색 & 상세 페이지 
- [ ] 장바구니에 물건 추가
- [ ] 장바구니 확인
- [ ] 주문하기
- [ ] 주문내역 이메일로 발송
