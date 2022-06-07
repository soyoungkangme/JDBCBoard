# JDBCBoard
h2 database connection description

<br><br>

## Model
### 1. JDBCUtil
- h2 객체 다운, 로딩, 연결
- 연결 해제

### 2. DAO, VO
- h2에 SQL 전송
- 반환값 VO에 세팅 

<br>

## Controller
### 3. Manager
- DAO 메서드 호출
- 반환값 화면에 뿌리는 메서드, 유효성검사 메서드 
- => _proc.jsp => DispatcherServlet.java

<br>

## View
### 4. Main
- 메인화면, Manager 메서드 호출 

