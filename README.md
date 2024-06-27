<h2>능동적으로 일하는 개발자 김동혁입니다!</h2>

**호기심이 많고, 새로운 기술을 배우는 데 거부감이 없으며, 모르는 것이 있으면 꼭 알아가려고 합니다.
<br/>
목표를 달성하기 위해 포기하지않고 동료들과 함께 성장하는 개발자가 되고싶습니다.**

### 기술스택

<img src="https://img.shields.io/badge/Java-9F1D20?style=for-the-badge&logo=Java&logoColor=white"> <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=Oracle&logoColor=white"> <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white"> <img src="https://img.shields.io/badge/NodeJS-F7DF1E?style=for-the-badge&logo=NodeJS&logoColor=white"> <img src="https://img.shields.io/badge/Express-4479A1?style=for-the-badge&logo=Express&logoColor=white">


<h2>📝Projects</h2>

### <a href="https://github.com/anhyunji494/pet-project">PetWave
기간 : 2024.03.22 ~ 2024.04.05
<br/>
주제 : 반려인을 위한 SNS
<br/>
사용기술 : React, SpringBoot

### 👨기능 구현 
<details>
	<summary>게시글 저장 및 불러오기</summary>
  
  게시글 업로드시 이미지 경로 db에 저장, 사진이 여러장인 게시글은 경로를 콤마로 구분해서 꺼내오기
</details>

<details>
	<summary>댓글 작성 및 불러오기</summary>
  
  댓글 작성 및 로딩시 axios 비동기 통신을 사용
</details>
<details>
	<summary>게시글 랭킹 기능 구현</summary>

   메인페이지 상단에 댓글이 많은 순서대로 5개 대표이미지 설정
</details>
<details>
	<summary>키워드 포함된 게시글 가져오기</summary>
	게시글 내용에 특정 키워드가 포함되면 최근 순으로 정렬후 보여주기
</details>

#### 트러블슈팅
1. React와 SpringBoot를 연동해서 사용했기때문에 초기에 cors 에러가 발생했는데 
   react부분에서 proxy설정에서 포트번호를 고정으로 해주었고 모든 팀원들에게 잘 작동되는걸 확인

3. 이미지를 저장할때 로컬 서버에 저장하게되면 다른 컴퓨터에서는 접근할수 없었기때문에 aws s3를 사용해서
외부 서버에 이미지를 저장하고 실제 db에는 이미지 경로 저장



### <a href="https://github.com/anhyunji494/kdt-ad-dashboard">Hexacore
기간 : 2024.05.23 ~ 2024.06.20
<br/>
주제 : MOT를 활용한 시설 관리용 모니터링 서비스
<br/>
사용기술 : React, Express

### 👨기능 구현 
<details>
	<summary>API문서 작성</summary>
  
<a href="https://animated-hisser-394.notion.site/API-5208301cdb2e4209958eecff255ae492?pvs=4">API
</details>

<details>
	<summary>DB 설계 및 구현</summary>
  
</details>
<details>
	<summary>요약 페이지, 분석 정보 페이지 API 구현 </summary>

   
</details>

#### 트러블슈팅

1. 실시간 데이터를 가져오기 위해 DB에 현재 시간으로 조회 시,
카메라에서 DB로 데이터가 입력되는 시간과 조회 시간에 시간적 불일치가 있어서 데이터를 조회하지 못했습니다.
원활한 시각화를 위해 현재 시간이 아닌 1분 전 조회로 해결하였습니다.
더미 데이터로 테스트 했을때는 문제가 없는줄 알았지만, 실제로 카메라를 연결 후 테스트 해보니 위 문제를 해결하기 위해서 생각보다 많은 시간을 소비해서 힘들었던 기억이 있습니다.
작은 부분도 다양한 경우의 수를 생각해볼 수 있는 좋은 경험이 됐습니다.


## 교육사항

훈련과정
+ 2023.12.29 ~ 인공지능 융합서비스 개발자 과정

기술자격/취득일
+ SQLD /2024.06.21
+ 정보처리기사(필기) / 2024/05.09
+ 리눅스마스터 2급 / 2024.03.29
+ 정보처리산업기사 / 2021.11.26

학력
+ 2017~2019 Borough of Manhattan CC 휴학
