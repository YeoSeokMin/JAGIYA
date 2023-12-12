# 자기야 - 연애, 결혼, 재혼을 위한 온라인 중매앱
2020-05-01 ~ 2023-05-29 WEB / APP Front 작업을 하였으며, 그 외 사내 웹페이지을 전반적으로 담당하는 업무를 진행하였습니다.

현재 해당 사이트가 작동하지 않고 저작권은 (주)상현컴퍼니에 있으므로 별도의 코드는 첨부하지 못하는 점 양해부탁드립니다.

### 1. PC 및 Mobile View
- 초기 메인 화면 접속시 디바이스 별 분류(PC/MAC/Mobile 등) 이후 PC or mobile 페이지로 이동하게끔 작업하였습니다.
- 로그인 이후 페이지 이동을 할수있게끔 보안 관련 로직을 작업하였습니다.
- 반응형 웹디자인으로 각 기종별로 대응을 하였습니다.
- 로그인 이후 rest api(json형식)로 받아온 데이터를 토대로 사진 / 이름 / 나이 등으로 정렬하여 회원 리스트를 작업하였습니다.
![pc_main](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/89482acc-ab2f-4fb2-8193-bb70f1d430c4)

![main_popup](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/f0c058a1-fe2e-47bc-9cd2-653efcff45e2)
![main_profile_list](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/73c1fab7-4945-4252-a7cf-8ae8bf1a0e2b)

### 2. 채팅 기능
- rest api(json형식)에서 데이터를 받는 형식으로 채팅을 구현하였습니다.
- 채팅방 클릭시 쿠키값에 room no를 입력하여 rest api로 전송한뒤 값을 받아서 상대방과 맞는 채팅방을 구현하였습니다.
![chat_list](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/e4808c98-3690-4c65-8396-999c0231bd83)
![chat_real](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/1c97a60e-795d-4f77-8c44-453b2d33c295)
![chat_test](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/46329d55-de61-4883-8535-b01e2f36f7d2)

### 3. 프로필 변경 기능
- 중매앱 특성상 프로필 사진을 포함한 회원 본인의 정보를 수정할수 있는 페이지를 구현하였습니다.
- rest api로 회원 넘버를 전송하고 데이터를 다시 받아오고 다시 전송하여 정보를 수정합니다.
- 회원의 정보가 유출될 수 있기에 rest api로 데이터를 주고받는 과정에서 한글 <-> 숫자로 치환하였고, 치환하는 로직 또한 추가하였습니다.
![my_page_main](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/7eda993a-4f39-4c2a-b463-a6ce2fc1e9ed)
![my_page_nick_change](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/edb4be7a-bed7-49c7-8fc6-31ee348e7696)
![my_page_nick_fam_change](https://github.com/YeoSeokMin/JAGIYA/assets/60656477/baf8a375-4459-4c91-b29b-c185a803ef37)
