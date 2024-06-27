# shoeshop
react 를 사용해 온라인 신발 쇼핑몰 입니다

기능 
1. 상품 목록
  상품데이터 컴포넌트화시켜 출하는방법<br>
  .map 함수를 이용해 원하는 만큼의 상품을 반복 출력시키는 방법<br>
   서버에서 axios 를 이용해 추가 상품을 출력<br>
2. 상품/details
   상품 클릭시 해당하는 데이터를 자세히 보여주는 페이지 입니다<br>
   해당 페이지마다 내용을 등록할 수  있으며 이는 한 상품당 한개의 데이터를 가지고있습니다<br>
3. 장바구니 (Cart)
   상품/details 페이지에서 주문하기 버튼 클릭시 cart 에 추가됩니다<br>
   장바구니 페이지에서 상품조회, 상품 수량을 변경할 수 있습니다<br>
4. 최근 본 상품 목록
   최근 본 상품을 localstorge 에 최대 3개 저장됩니다<br>
   가장 최근에 본 상품을 가장 우측에 진열합니다<br>
   localstorge 가 비어있다면 "배열이 없음" 문구가 출력됩니다<br>
   
사용 라이브러리 
├── @reduxjs/toolkit@2.2.5
├── @testing-library/jest-dom@5.17.0
├── @testing-library/react@13.4.0
├── @testing-library/user-event@13.5.0
├── axios@1.7.2
├── bootstrap@5.3.3
├── react-bootstrap@2.10.2
├── react-dom@18.3.1
├── react-query@3.39.3
├── react-redux@9.1.2
├── react-router-dom@6.23.1
├── react-scripts@5.0.1
├── react@18.3.1
├── styled-components@6.1.11
└── web-vitals@2.1.4
