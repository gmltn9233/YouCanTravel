# 🏖YouCanTravel
2023-1학기 세종대 데이터베이스 수업 프로젝트

## 💡 Background

* 장애인들이 여행을 보다 쉽고 편안하게 즐길 수 있는 환경 제공
* 장애인들의 문화생활 증진 및 교류 활성화
* 장애인 관광산업 활성화 및 시장규모 확장

## 📊 E-R Diagram

<p align = "left">
  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/8700817f-2e3b-4def-ac13-85b3cd5933d0" width="80%" height="80%">
</p>

## 🛠️ Relational schema
<p float="left">

  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/5cb2066b-acc2-4c04-a12b-7577608f3e1d">
</p>

## 🔗 Link

|개체|데이터 수집 방안|출처|
|------|---|---|
|회원|가상데이터 제작||
|리뷰|가상데이터 제작 + 파이썬을 통해 리뷰입력기능 구현||
|여행사|공공데이터 가공|[공공데이터 포털](https://www.data.go.kr/tcs/dss/selectDataSetList.do?dType=TOTAL&keyword=%EC%84%9C%EC%9A%B8%EC%8B%9C+%EC%97%AC%ED%96%89%EC%82%AC&operator=AND&detailKeyword=&publicDataPk=&recmSe=N&detailText=&relatedKeyword=&commaNotInData=&commaAndData=&commaOrData=&must_not=&tabId=&dataSetCoreTf=&coreDataNm=&sort=&relRadio=&orgFullName=&orgFilter=&org=&orgSearch=&currentPage=1&perPage=10&brm=&instt=&svcType=&kwrdArray=&extsn=&coreDataNmArray=&pblonsipScopeCode=)|
|가이드|가상데이터 제작||
|여행상품|공공데이터 가공|[서울특별시 마을관광상품 한눈에 보기](https://news.seoul.go.kr/culture/tour-products-view)|
|여행지역|공공데이터를 통해 존재하는 지역 추출||
|시설|공공데이터 가공|[공공데이터 포털](https://www.data.go.kr/tcs/dss/selectDataSetList.do?dType=FILE&keyword=%EC%84%9C%EC%9A%B8%EC%8B%9C+%EC%9E%A5%EC%95%A0%EC%9D%B8&operator=AND&detailKeyword=&publicDataPk=&recmSe=&detailText=&relatedKeyword=&commaNotInData=&commaAndData=&commaOrData=&must_not=&tabId=&dataSetCoreTf=&coreDataNm=&sort=_score&relRadio=&orgFullName=&orgFilter=&org=&orgSearch=&currentPage=1&perPage=10&brm=&instt=&svcType=&kwrdArray=&extsn=&coreDataNmArray=&pblonsipScopeCode=)|

## 🎞️ Service UI
![image](https://github.com/gmltn9233/YouCanTravel/assets/63588364/d5276ff1-f34e-499b-ac1b-48f5e14d5dde)


## 👩‍💻 Project Features
### 1. 지역별 편의시설 제공 기능
공공 데이터 포털에서 가져온 장애인 편의시설의 주소, 위치, 전화번호, 시설명을 제공합니다.
각 시설의 주출입구 접근로 여부, 장애인용 승강기 여부, 장애인 화장실 여부등의 정보를 제공합니다.

### 2. 여행상품 예약 기능
여행 지역별 여행상품의 가격,계획,예약 상태를 제공합니다.

### 3. 여행사 및 가이드 정보 제공 기능
여행상품 별 여행사 및 가이드의 연락처를 제공합니다.

### 4. 리뷰 작성 및 리뷰 정보 제공 기능
각 회원은 리뷰를 작성하고, 다른 회원의 리뷰를 열람할 수 있습니다.

### 5. 가까운 병원 찾기 기능
여행지의 숙소나 시설에서 가장 가까운 병원을 찾아 응급상황에 대비할 수 있습니다.


## ⏳DB Query Example
<p float="left">
  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/d2668bde-054b-46e1-950b-c33b7d2a45f0" width="45%" height="230px">
  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/d9bdda3e-a659-47bc-87db-a5f81dcb30f2" width="45%" height="230px">
</p>
<p float="left">
  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/defd444b-6462-44f3-bb7a-1dace1f3a575" width="45%" height="230px">
  <img src = "https://github.com/gmltn9233/YouCanTravel/assets/63588364/46748ee5-9c70-4b92-b653-186ffcd4fab7" width="45%" height="230px">
</p>

## 💭 I Learned
* 공공데이터와 PostgresSQL를 활용하여 데이터베이스를 설계 및 구축하였습니다.
* Dbeaver를 활용하여 보다 효율적으로 DB를 관리하였습니다.
* Python의 Faker 라이브러리를 활용하여 부족한 데이터를 보충하였습니다.
* Python의 Geopy 라이브러리를 활용하여 가까운 병원찾기 기능을 구현하였습니다.
* Python을 활용하여 리뷰 작성 및 검색, 간단한 UI프로그램을 구현하였습니다.
