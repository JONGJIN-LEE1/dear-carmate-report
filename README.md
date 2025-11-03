
# [Dear-Carmate 프로젝트 개발 보고서]  


프로젝트명 : [Dear-Carmate 프로젝트  

팀명: 3팀  

작성자: 이종진  

작성일: 2025-08-13

---


# 1. 📝 프로젝트 개요

 
### 1.1 목적 

 
🚗 중고차 계약 관리 서비스 DearCarmate<br/>
     중고차 계약, 간편하고 스마트하게
     복잡한 계약 관리, 이젠 한 곳에서 해결하세요.

 
### 1.2 주요 기능

 
- 인증 API
- 유저 API
- 차량 API
- 고객 API
 
- 회사 API
- 계약 API
- 계약서 API
  
- 대시보드 API
- 이미지 API 
---
 
# 2. ⚙️ 기술 스택 및 협업 도구
 
 
<h3 align="center"><b>📚 Languages 📚</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /> 
<img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white" /> </p>

<h3 align="center"><b>⚙️ Frameworks & Libraries</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white" /><br/>  <img src="https://img.shields.io/badge/Passport-34E27A?style=for-the-badge&logo=passport&logoColor=white" /> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black" /> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" /> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black" /> </p>

<h3 align="center"><b>🗄️ Database & Hosting</b></h3>

<p align="center"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" /> <img src="https://img.shields.io/badge/Render-0099E5?style=for-the-badge&logo=render&logoColor=white" /> </p>

<h3 align="center"><b>🔧 Development Tools </b></h3>

<p align="center"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /> <img src="https://img.shields.io/badge/Nodemon-76D04B?style=for-the-badge&logo=nodemon&logoColor=white" /> <img src="https://img.shields.io/badge/TS Node-3178C6?style=for-the-badge&logo=ts-node&logoColor=white" /> <img src="https://img.shields.io/badge/Dotenv-ECD53F?style=for-the-badge&logo=dotenv&logoColor=black" /> </p>


<h3 align="center"><b>🔐 Authentication & Utility Libraries </b></h3>
<p align="center">
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white" alt="JWT" />
  <img src="https://img.shields.io/badge/Nodemailer-009966?style=for-the-badge&logo=gmail&logoColor=white" alt="Nodemailer" />
  <img src="https://img.shields.io/badge/Multer-1E90FF?style=for-the-badge&logo=files&logoColor=white" alt="Multer" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
</p>

<h3 align="center"><b> 🤝 Collaboration Tools </b></h3>
<p align="center"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white" alt="Notion" /> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /> <img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /> </p>

---

## 2.1 ERD 다이어그램
<img width="889" height="500" alt="image" src="https://github.com/user-attachments/assets/723b73e6-60a0-4eb4-9ead-8fca5fc8663d" />


---
 
# 3. 📌 담당한 작업 

 
### 3.1 고객 등록

- 고객명, 성별, 연락처, 연령대, 지역, 이메일, 메모를 입력하여 고객 등록이 가능합니다.
- 연령대, 지역, 이메일, 메모는 선택 사항입니다.

---
### 3.2 고객 수정  

- 유저의 회사에 등록된 고객 정보의 수정이 가능합니다

---
### 3.3 고객 삭제

- 유저의 회사에 등록된 고객 정보의 삭제가 가능합니다.

---
### 3.4 고객 목록 조회
- 등록된 고객 정보 목록을 확인할 수 있습니다.
- 고객명, 계약 횟수, 성별, 연락처, 연령대, 지역, 이메일이 표시됩니다.
- 페이지네이션이 가능합니다.
- 고객명, 이메일로 검색이 가능합니다.
---  

### 3.5 계약서 등록  
- 거래를 선택하고 계약서 파일을 추가하여 등록합니다.
- 유효한 확장자의 파일만 업로드 가능합니다.
- 업로드 파일 개수, 용량 제한이 있습니다.
- 계약서가 등록될 경우 고객에게 자동으로 계약서가 첨부된 이메일이 발송됩니다.
---  


### 3.6 계약서 다운로드
- 업로드 된 계약서 일부 혹은 전체를 다운로드 할 수 있습니다.
---

### 3.7 계약서 수정
- 등록된 계약서의 일부 혹은 전체를 삭제할 수 있습니다.
- 계약서를 추가로 등록할 수 있습니다.
- 계약 수정 API를 활용해서 구현해주세요.

---

### 3.8 계약서 목록 조회

- 등록된 계약서 목록을 확인할 수 있습니다.
- 계약서명, 계약체결일, 문서 수, 담당자, 차량번호가 표시됩니다.
- 페이지네이션이 가능합니다.
- 계약서명, 담당자로 검색이 가능합니다.

---

### 3.9 중간 발표 준비
[중간발표 자료.pdf](https://github.com/user-attachments/files/21747907/default.pdf)


# 4. 📌 개발 예시  


### 4.1 고객 등록  

- API URL(POST /customers) & 요청 예시
  
- 응답 예시 (201 Created)
 ```
 {
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```
  
<img width="835" height="641" alt="고객 등록" src="https://github.com/user-attachments/assets/11a3ce6c-ab9e-450e-b127-33500e8c6ab8" />



### 4.2 고객 목록 조회  

- API URL(GET  고객	/customers) & 요청 예시
  
- 응답 예시 (200 OK)
```
{
	"currentPage": 1,
	"totalPages": 5,
	"totalItemCount": 50,
	"data": [
		{
			"id": 1,
			"name": "string",
			"gender": "male | female",
			"phoneNumber": "string",
			"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
			"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
			"email": "string",
			"memo": "string",
			"contractCount": 0
		},
		{
			"id": 2,
			"name": "string",
			"gender": "male | female",
			"phoneNumber": "string",
			"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
			"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
			"email": "string",
			"memo": "string",
			"contractCount": 0
		}
	],
}
```
  
<img width="841" height="683" alt="고객 목록 조회" src="https://github.com/user-attachments/assets/69cd4b86-918d-4c4b-b06e-ec8de73b93b4" />





### 4.3 고객 수정

- API URL(PATCH /customers/{customerId}) & 요청 예시
  
- 응답 예시 (200 OK)

  
```
{
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```


<img width="837" height="655" alt="고객 수정" src="https://github.com/user-attachments/assets/0fbfb5cc-e701-43a6-a949-cb84f2a7c68e" />




### 4.4 고객 삭제

- API URL(DELETE /customers/{customerId}) & 요청 예시
  
- 응답 예시 (200 OK)
  
```
{
  "message": "고객 삭제 성공"
}
```

<img width="843" height="539" alt="고객 삭제" src="https://github.com/user-attachments/assets/c53a6439-9a28-4d72-b57b-684c0e40db1e" />


### 4.5 고객 상세 정보 조회

- API URL(GET /customers/{customerId}) & 요청 예시
```
{
	"id": 123,
	"name": "string",
	"gender": "male | female",
	"phoneNumber": "string",
	"ageGroup": "10대 | 20대 | 30대 | 40대 | 50대 | 60대 | 70대 | 80대",
	"region": "서울 | 경기 | 인천 | 강원 | 충북 | 충남 | 세종 | 대전 | 전북 | 전남 | 광주 | 경북 | 경남 | 대구 | 울산 | 부산 | 제주",
	"email": "string",
	"memo": "string",
	"contractCount": 0
}
```

<img width="853" height="647" alt="고객 상세 조회" src="https://github.com/user-attachments/assets/0cff8054-5c01-401e-b614-bcd1cba68506" />

### 4.6 고객 데이터 대용량 업로드

- API URL(POST /customers/upload) & 요청 예시

```
{
	"message": "성공적으로 등록되었습니다"
}
```
<img width="869" height="517" alt="고객 대용량 업로드" src="https://github.com/user-attachments/assets/fd0237b7-4f7a-4522-8b24-bb7091f25266" />



### 4.7 계약서 업로드 시 계약 목록 조회

- API URL(GET /contractDocuments) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"currentPage": 1,
	"totalPages": 2,
	"totalItemCount": 6,
	"data": [
		{
			"id": 1,
			"contractName": "string",
			"resolutionDate": "2024-02-22T09:00:00.000Z",
			"documentsCount": 2,
			"manager": "string",
			"carNumber": "string",
			"documents": [
				{
					"id": 1,
					"fileName": "string"
				},
				...
			]
		},
		...
	]
}
```
<img width="850" height="605" alt="계약서 업로드 시 목록 조회" src="https://github.com/user-attachments/assets/1942db0d-c07b-4430-ad2e-cf5ab4dcc5c0" />


### 4.8 계약서 추가 시 계약 목록 조회

- API URL(GET /contractDocuments/draft) & 요청 예시

- 응답 예시 (200 OK)
```
[
	{
		"id": 1,
		"data": "그랜저 - 김고객 고객님"
	},
	{
		"id": 2,
		"data": "K3 - 홍길동 고객님"
	},
	...
]

```
<img width="848" height="674" alt="계약서 추가용 계약 목록 조회" src="https://github.com/user-attachments/assets/9ebdb680-e591-49d8-becd-621d5b483622" />


### 4.9 계약서 업로드

- API URL(POST /contractDocuments/upload) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"contractDocumentId": 1
}

```

<img width="873" height="602" alt="계약서 업로드" src="https://github.com/user-attachments/assets/1891f7cb-3713-4ea6-8d41-fa5ea73b4772" />


### 4.10 계약서 다운로드

- API URL(GET /contractDocuments/{contractDocumentId}/download) & 요청 예시

- 응답 예시 (200 OK)
```
{
	"message": "계약서 다운로드 성공"
}


```
<img width="859" height="658" alt="계약서 다운로드 에러 메세지" src="https://github.com/user-attachments/assets/58dc25b7-c90d-4fe4-8ff5-7cf94256fae6" />









# 5. 📌 파일 구조 
 
```
├─ .eslintrc.json
├─ .gitignore
├─ .prettierrc.json
├─ .vscode
│  └─ setting.json
├─ README.md
├─ package-lock.json
├─ package.json
├─ prisma
│  └─ migrations
│  └─ schema.prisma
│  └─ mock.ts
│  └─ seed.ts
├─ src
│  ├─ @types
│  │  └─ express
│  │     └─ index.d.ts
│  ├─ app.ts
│  ├─ auth
│  │  ├─ auth.routes.ts
│  │  ├─ auth.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ login.dto.ts
│  │  ├─ jwt.ts
│  │  ├─ passport.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ cars
│  │  ├─ cars.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ create-car.dto.ts
│  │  │  └─ get-car.dto.ts
│  │  │  └─ update-car.dto.ts
│  │  │  └─ upload-car.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ common
│  │  ├─ constants
│  │  │  └─ constants.ts
│  │  ├─ enums
│  │  │  ├─ age-group.enum.ts
│  │  │  ├─ car-status.enum.ts
│  │  │  ├─ car-type.enum.ts
│  │  │  ├─ contract-status.enum.ts
│  │  │  ├─ gender.enum.ts
│  │  │  └─ region.enum.ts
│  │  ├─ errors
│  │  │  ├─ app-error.ts
│  │  │  ├─ bad-request-error.ts
│  │  │  ├─ conflict-error.ts
│  │  │  ├─ forbidden-error.ts
│  │  │  ├─ not-found-error.ts
│  │  │  └─ unauthorized-error.ts
│  │  ├─ prisma
│  │  │  └─ client.ts
│  │  └─ utils
│  │     ├─ custom-errors.ts
│  │     └─ validate.dto.ts
│  │     └─ car.converter.ts
│  │     └─ contract.converter.ts
│  │     └─ csv-downloader.ts
│  │     └─ customer.converter.ts
│  │     └─ firebase-admin.ts
│  ├─ companies
│  │  ├─ companies.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ create-company.dto.ts
│  │  │  ├─ get-companies.dto.ts
│  │  │  ├─ get-users.dto.ts
│  │  │  └─ update-companies.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ contract-documents
│  │  ├─ contract-documents.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ download-contract-documents.dto.ts
│  │  │  ├─ edit-contract-documents.dto.ts
│  │  │  ├─ get-contract-documents.dto.ts
│  │  │  └─ upload-contract-document.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ contracts
│  │  ├─ contracts.routes.ts
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  ├─ create-contract.dto.ts
│  │  │  ├─ meeting.dto.ts
│  │  │  └─ update-contract.dto.ts
│  │  │  └─ update-meeting.dto.ts
│  │  ├─ contract.mapper.ts
│  │  ├─ repository.ts
│  │  ├─ schema.ts
│  │  └─ service.ts
│  ├─ customers
│  │  ├─ controller.ts
│  │  ├─ customers.routes.ts
│  │  ├─ dto
│  │  │  ├─ create-customer.dto.ts
│  │  │  ├─ customer-list-query.dto.ts
│  │  │  ├─ update-customer.dto.ts
│  │  │  └─ upload-customers.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ dashboard
│  │  ├─ controller.ts
│  │  ├─ dashboard.routes.ts
│  │  ├─ dto
│  │  │  ├─ contract-by-car-type.dto.ts
│  │  │  ├─ sales-by-car-type-raw.dto.ts
│  │  │  ├─ sales-by-car-type.dto.ts
│  │  │  └─ summary-response.dto.ts
│  │  ├─ repository.ts
│  │  └─ service.ts
│  ├─ index.routes.ts
│  ├─ main.ts
│  ├─ middlewares
│  │  ├─ auth.middleware.ts
│  │  └─ error.middleware.ts
│  ├─ uploads
│  │  ├─ controller.ts
│  │  ├─ dto
│  │  │  └─ upload.dto.ts
│  │  ├─ repository.ts
│  │  ├─ service.ts
│  │  └─ uploads.routes.ts
│  └─ users
│     ├─ controller.ts
│     ├─ dto
│     │  ├─ create-user.dto.ts
│     │  └─ update-user.dto.ts
│     ├─ repository.ts
│     ├─ service.ts
│     └─ users.routes.ts
└─ tsconfig.json
```

---  

 

# 6. 📌 문제점 및 해결 과정  

### 6.1 고객 목록이 프론트랑 연동했을 때 빈 칸으로 뜨는 문제 

: API 명세서에는
page,
pageSize,
searchBy,
keyword 순으로 파라미터를 받는데,
파라미터 순서를 안 맞췄음

- > page,
pageSize,
keyword,
searchBy 순으로 되어 있는 걸 명세서대로 순서 바꿈


---  

### 6.2 프론트엔드와 연동했을 때 고객 등록 오류 발생

: Prisma의 @map 디렉티브는 데이터베이스에 저장될 때의 값만 변경하고, TypeScript/JavaScript 코드에서는 여전히 enum 이름(MALE, FEMALE 등)을 사용해야 함. 그래서 API가 한글 입력을 받지 못하는 문제가 발생


- > DTO에 Transform 데코레이터 추가: 한글 입력을 받아서 Prisma enum 값으로 자동 변환
유연한 입력 처리: 한글("남성"), 영어 소문자("male"), 영어 대문자("MALE") 모두 허용하도록 변경



---  


### 6.3 class-validator 와 Joi 차이


: 유효성 검사 관련해서 class-validator 와 Joi 중 어떤 방식인지 팀원들과 토론 및 합의를 진행하지 않아서
각자 다른 방식으로 작성

- > 중간에 데일리스크럼으로 회의 진행 후 class-validator 방식으로 선정

---  


### 6.4 tsconfig에서 [any] 타입을 쓰지 않는 것으로 설정, 그러나 작업하다보면 암시적으로 'any' 형식이 포함되는 경우 발생
: tsconfig 설정을 멘토님이 평소에 실무에서 사용하시는 걸로 받아와서 사용했는데, 생각보다 엄격해서 [any] 타입을 아예 쓰지 않게 설정된 것을 확인

- > 타입을 명확하게 지정하거나 타입 추론을 사용해서 해결, 변수를 선언할 때 가능한 한 초기값을 줘서 타입 추론이 가능하도록 변경
```
// 암시적 any 발생
let count; // ❌

// 타입 추론 (number로 자동 인식)
let count = 0; // ✅
```

--- 


### 6.5 mock 데이터와 seed 데이터를 받아왔는데, seed 파일 내 경로가 mockData라 데이터를 못 받아오는 문제 발생  


- > 경로를 파일명과 일치하게 mock로 변경  

---  


### 6.6 swagger 라우터 주석 달고 로컬에서 테스트할 때 오류 발생 

: swagger 문서 작성하고 각 라우터 별 파일에 주석을 달았는데, 오류 발생

- >  들여쓰기, 띄어쓰기를 제대로 진행하니 해결
---


# 7. 📃 회고록(느낀 점)
 
### 7.1
 
본격적인 프로젝트에 앞서 schema.prisma 모델 정의 합의는 정말 중요한 것 같다. (중간에 모델 정의가 바뀌면 힘들다.)

 ---  
 
### 7.2
 
Prisma 의존성 주입이라는 것을 알게 되었다.
기본 개념은 클래스나 함수가 사용할 객체(의존성)를 스스로 생성하지 않고, 외부에서 주입하는 것으로,
이렇게 하면 코드의 재사용성과 테스트 용이성이 높아진다고 한다.

 ---  
 
### 7.3
 
커밋은 작은 단위로 자주 하자.( 많은 양을 한번에 커밋하려고 하다보면 코드 리뷰도 어려워지고, 충돌이 났을 때 고치기도 힘들다.)

 ---  
 
### 7.4 
 
멘토님이 추천하신 것처럼, 1개의 파일에 1개의 클래스가 담기게 파일 구조를 짜니, 파일의 개수는 늘어나지만, 코드의 길이가 많이 줄어
코드 유지 보수가 편해졌다. 하지만 어쩔 수 없이, 혹은 다른 이유로 1개의 파일에 2개 이상의 클래스가 담기게 짜면 엄격한 규칙으로 인해 오류 발생이 떠서 굉장히 힘들었다. 이럴 땐 빨리 클래스를 다른 파일로 분리하거나, 시간이 없을 땐 규칙을 껐다. 

 ---  
 
### 7.5
 
프론트엔드 코드들을 살펴볼 줄 알아야 한다.
강사님은 백엔드 개발자들이 프론트엔드 코드를 살펴보는 일이 별로 없다고 했지만, 우리는 부트캠프에서 배부한 프론트엔드를 바탕으로 
개발을 하게 된다. 그래서 배우지 않은 프론트엔드를 쉽사리 고치긴 힘들고, 최대한 프론트엔드와 맞춰서 개발을 해야 하는데, 배부한 프론트엔드 코드나 API 명세서가 잘못 기입되거나 잘못 짜여져 있으면 고치기가 굉장히 힘들다. 프론트엔드에서 백엔드와 소통하는 부분을 찾고, 그 부분들이랑 백엔드가 잘 맞는지 확인해야 하는데, 프론트엔드의 어떤 부분이 백엔드를 호출하는지를 모르니까 힘들었다.

 ---  
 
### 7.6
 
의존성이 낮은 기능부터 개발을 했는데, 후반에 개발을 하는 즉, 의존성이 높은 기능을 개발하는 사람은 시간에도 쫒기고, 다른 팀원의 코드
들도 살펴보아야 하는 힘든 상황에 놓이게 된다는 걸 깨달았다.
그리고 관련이 있는 API는 한 사람이 개발하는 것이 훨씬 편하다는 것도 깨달았다.

 ---  
 
### 7.7
 
코드 리뷰가 생각보다 너무 오래걸린다. 이게 각자가 다른 팀원의 코드를 리뷰해줘야 하는데, 아무리 코드 스타일 등을 미리 규칙으로 맞췄어도, 서로 코드 작성하는 스타일이 다른데다가, 아직 한창 배우는 단계라, 어떤 부분이 핵심 부분이고 그래서 그 부분을 중점적으로 봐야한다 뭐 이런 요령이 없어서 초반에 PR 하나 올라오는데, 코드 리뷰하는게 거의 반나절 걸렸다. 게다가 실수로 피드백이 들어가면 어떡하지? 라는 생각도 마음 한 켠에 가득했다.

---  

### 7.8
 
팀원들과의 소통이 굉장히 중요하다.

---  
 
### 7.9
 
공통으로 자주 쓰이는 함수나 변수 같은 경우는 utils 폴더를 만들어서 꺼내 쓰는 방법이 좋을 수 있다.

---  






