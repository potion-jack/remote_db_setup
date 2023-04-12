# LocalHost 원격접속 허용
> 1. 본인 공인 ip 확인
> 2. 현재 db의 유저정보 확인
```
select user,host from mysql.user;
```

> 3. 원격 접속 가능한 유저를 하나 생성한다.
```
create user 'admin'@'%' identified by '1234'
-> user 생성
grant all privileges on *.* to 'admin'@'%';

```

> 4.
```
mysql --verbose --help | grep my.cnf
-> my.cnf 파일의 위치를 찾는다
-> 만약 bind-address 가 걸려 있으면 주석체크 하기


```
