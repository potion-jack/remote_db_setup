# DB_Mirgration and able remote connection

> ## WHY : AWS 요금 폭탄 맞음
> 1. 상용 DB 덤프 따서
> 2. LOCAL DB에 넣고
> 3. 원격 접속 허용 해서
> 4. 데이터 팀에 제공한다.

## 크게 3가지 과정이 있음

### 1. mysql에서 외부접속 가능한 유저를 만든다
### 2. mysql config 에서 bind-address가 있다면 제거한다
### 3. 포트 포워딩을 설정한다


:wq
