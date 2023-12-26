<div align= "left">
    <img src="https://capsule-render.vercel.app/api?type=cylinder&color=39436f&height=120&text=HR%20Project&animation=&fontColor=e1e0e0&fontSize=70" 
</div>
    
<div style="text-align: left;">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2>
    <div style="margin-top: 10px; text-align: left;" "text-align: left;"> <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=CSS3&logoColor=white">
          <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=HTML5&logoColor=white">
          <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=Java&logoColor=white">
          <img src="https://img.shields.io/badge/Javascript-F7DF1E?style=flat-square&logo=Javascript&logoColor=white">
          <img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=Oracle&logoColor=white">
          <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=Spring&logoColor=white">
    </div>
</div>
    
    
## 📃Contents

1. 프로젝트 개요
2. 프로젝트 내용
3. 화면 별 기능 설명
4. 소감
   

## 📌프로젝트 개요

Oracle DB TABLE을 활용하여 인사 관리를 할 수 있는 웹사이트를 제작했습니다.

- 프로젝트 명: HR Project
- 일정: 2023-10-31 ~ 2023-11-10
- 개발 환경
    - Server: Apache-tomcat-9.0.0
    - Java EE: Eclipse (version 2023-06)
    - Database: Oracle SQL developer
    - Language: Java, jsp/Servlet, HTML, CSS, JavaScript, SQL
    - Framework: Spring Tool suite 3.9.1
      

## 🔎프로젝트 내용

- DB ERD 설계
<img src="https://github.com/SuinShin/HR-Project/assets/148019115/555a8052-838c-48af-a791-d2cffa1892b8" width="800" height="auto">


**🔑 공지사항 게시판 CRUD**

- 사내 시스템을 열람하는 사원들을 위한 공지사항 게시판을 구현.

- 글 작성과 수정은 관리자 권한을 가진 사원만 가능하며, 사원은 열람만 가능.

**🔑 DB의 HR_LOGIN TABLE과 연동하여 권한 별 로그인 기능 구현**

- 사번을 기본키로 받아, 사원의 권한과 사원명을 식별.

**🔑 관리자 - 공지사항 게시판, 사원, 부서, 업무 관련 TABLE CRUD 권한**

- C- 각 테이블에서 새로운 튜플을 삽입.

- R- 각 테이블에서 키워드 검색을 통해 해당 정보를 조회.

- U- 각 테이블에서 정보를 업데이트.

- D- 각 테이블에서 원하는 행을 삭제.

**🔑 사원 - 공지사항 게시판, 사원, 부서, 업무 관련 정보 READ 권한**

- DB의 무결성을 위해, 관리자 권한이 아닌 일반 사원은 테이블 정보 열람만 가능하도록 설계.



## 🖥화면 별 기능 설명


## 📓소감

아무래도 첫 프로젝트이다 보니, 전체적으로 미숙한 부분이 많이 보였던 프로젝트였다. 

**💡 유지보수 부분**

- CSS나 JS코드를 분리해서 작성했으면 유지보수가 용이하고 가독성이 좀 더 향상되었을 것이다.
- 모델-뷰-컨트롤러의 역할 별로 분리를 확실하게 했어야 했다고 생각된다. (로그인 기능)

**💡 공지사항**

- 페이징 기능을 구현했는데, 검색 기능은 제외하였다. 검색 창을 함께 구현했어야 했다.
- 파일 첨부 기능을 추가했으면 좋았을 것 같다.

**💡 느낀 점**

1. **Spring MVC를 통한 웹 개발:** Spring MVC 아키텍처를 활용하여 모델-뷰-컨트롤러를 구분하여 개발했다.<br>
   이를 통해 개발 효율과 유지보수성을 향상시킬 수 있었다.
2. **JDBC로 데이터베이스 처리:** JDBC 드라이버를 활용하여 데이터베이스의 CRUD 작업을 다뤘다. <br>
   데이터베이스 연결, 쿼리 실행 및 결과 처리 등을 통해 데이터 관리에 대한 이해도를 높일 수 있었다. 
