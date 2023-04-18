## 권현재의 Market


![기능구현](https://user-images.githubusercontent.com/114847858/231937310-65599354-51fe-45d2-a0da-425e28c5e311.gif)


## 📝적용된 기능 

## 반응형 디자인
![반응형](https://user-images.githubusercontent.com/114847858/231937333-43703110-4c61-4676-b732-c90610675de8.gif)

## 1. 로그인 / 회원가입

1. 상품을 등록, 구매하기 위해서는 로그인 먼저되어야합니다. ( 시연을 위해 로그인 페이지에 value값을 지정하였습니다 ) - 상태관리: Recoil 
2. 첫 로그인 진행시 accessToken과 refreshToken을 저장하여 accessToken 만료시 (한시간) 쿠키에 저장된 refreshToken을 활용하여 자동으로 새로운 accessToken이 발급됩니다.
3. 회원가입 및 로그인에 yup을 활용한 검증이 진행됩니다. 

## 2.상품 리스트

1. 상품 리스트는 무한스크롤로 구현하였습니다.
2. 상품을 클릭하면 상세 화면이 보입니다.

## 3. 상품 등록하기

1. 로그인이 완료된 경우 상품 등록이 가능합니다.
2. 상품 정보, 카카오맵, 이미지 등록이 가능합니다.

## 4. 상품 수정

1. 상품을 등록한 사람만 수정 / 삭제가 가능합니다.
2. 수정 내용이 없다면 기본 값으로 다시 등록됩니다. 
3. 상품을 등록한사람만 수정버튼이 보여집니다.

## 5. 상품 구매 / 로그아웃

1. 바로구매 버튼을 누르면 상품이 구매되고, 상단 유저 포인트가 자동으로 차감됩니다. 
2. 판매자가 아닌 사람만 구매하기 버튼이 보여집니다.

## 6. 충전하기 

1. 포트원 결제 솔루션을 사용하여 카카오 결제가 가능합니다.
2. 결제 완료시 상단의 포인트가 자동으로 업데이트 됩니다.

## 7. 댓글 

1. 문의를 희망하는 상품에 댓글을 추가할 수 있습니다. 
2. 삭제가 가능합니다.
3. 본인의 댓글만 삭제하기 버튼이 보여집니다.
4. 대댓글 작성이 가능하며 작성자만 삭제할 수 있습니다.

## 8. 문의하기

1.오픈채팅 연결로 관리자에게 바로 연결 가능합니다.


## 👂프로젝트를 진행하면서 느낀점
 첫번째 프로젝트였던 만큼 많은 자신감을 얻게 되었지만, 그만큼 학습할 것이 무궁무진하다고 생각하였습니다. 이번 프로젝트를 계기로 CRUD 및 기본적인 라이브러리 사용, 그리고 DOCS의 중요성을 알게 되었다고 생각합니다. 또한 사용자가 어떤 행동을 할 지 생각하고 error를 미리 예방하는 습관을 가질 수 있었습니다. ex) 수정시 새로고침시 defalutValue 사라짐 등
또한 React의 큰 장점인 Component를 최대한 활용하며 과도한 props drilling을 방지하고 성능을 최적화 할 수 있었습니다.

  
