# Exchange Document

1. 기술스택
2. 구성도



## 1. 기술스택

```
사용자 페이지: react
관리자: django
API 서버: nest.js
socket 서버: socket.io
coin 서버: express.js
매칭서버: python
```

```
메시지 큐: kafka
디비: mariadb
캐싱디비: redis
```

```
코인데몬: bitcoind, geth(paity), eosio 등
```



## 2. 구성도

* 전체 시스템 구성

![system_architecture](https://raw.githubusercontent.com/Exchange-M/oss-exchange-document/master/resource/system_architecture.png)

* 매칭 시스템 구성

![match_architecture](https://github.com/Exchange-M/oss-exchange-document/blob/master/resource/match_architecture.png?raw=true)



