[참고](https://www.daleseo.com/graphql-apollo-server/)

# Apollo Server를 이용한 초간단 GraphQL 서버 개발

### 서버구동

```shell
$ node .
Listening at http://localhost:4000/
```

### 서버 테스트

- `http://localhost:4000` -> 웹 기반 툴 접속됨
- 좌측 섹션 `Operation` 에서 아래와 같이 입력하고 `Submit Operation(Ctrl + Enter)` 클릭

  ```
  query TestQuery {
    ping
  }
  ```

- 아래와 같은 결과를 확인할 수 있음

  ```json
  {
    "data": {
      "ping": "ping"
    }
  }
  ```
