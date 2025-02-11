#
# 🗒  e-commerce

간단히 사용자들과 소통할 수 있는 게시판 서비스입니다. 

## 프로젝트 기능 및 설계
- 회원가입 기능
  - 사용자는 회원가입을 할 수 있다. 일반적으로 모든 사용자는 회원가입시 USER 권한 (일반 권한)을 지닌다. 
  - 회원가입시 아이디와 패스워드를 입력받으며, 아이디는 unique 해야한다. 

- 로그인 기능
  - 사용자는 로그인을 할 수 있다. 로그인시 회원가입때 사용한 아이디와 패스워드가 일치해야한다. 

- 상품 담기 기능 
  - 로그인한 사용자는 특정 상품을 담을 수 있다.  

- 장바구니 조회 기능
  -로그인 한 사용자는 본인의 장바구니를 조회할 수 있다.
  - 로그인하지 않은 사용자를 포함한 모든 사용자는 게시글을 조회할 수 있다. 
  - 장바구니는 최신순으로 기본 정렬
  - 장바구니 상 종류가 많을수 있으므로 paging 처리를 한다. 

- 장바구니 상품 삭제
  -로그인 한 사용자는 본인의 장바구니 중 상품 목록을 삭제할 수 있다. 

- 상품명 검색 기능
  - 로그인 비로그인 여부 상관 없이 상품명을 검색 할 수 있다.

## ERD 
![ERD](doc/img/erd.png)

## Trouble Shooting
[go to the trouble shooting section](doc/TROUBLE_SHOOTING.md)

### Tech Stack
<div align=center> 
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> 
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>
