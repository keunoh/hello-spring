understanding how spring works

- h2 서버 접속
  - .h2/sh로 접속해야함 해당 폴더 위치에서
  - uesrs/(사용자명)/test.mv.db
- h2 웹에서 접속
  - jdbc:h2:tcp://localhost/~/test 로 입력한뒤 접속 버튼
- 프로젝트 내 sql 관리
  - 프로젝트 바로 하위에 sql 폴더 생성
  - ddl.sql 파일 생성 후 그 안에다 쿼리문 작성(관리 목적)
