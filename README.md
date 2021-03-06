# Skylove (스카이러브)

스카이러브는 웹 서비스 기반의 실시간 랜덤채팅 사이트입니다.

> #### 데모 URL: http://49.50.160.97:3000/



## 진행 상황

- #### [1 주차 - 기획](./1주차_기획서.md)

- #### [2 주차 - 자연어 처리](./2주차_자연어처리.md)

- #### [3 주차 - 비전](./3주차_비전.md)




## 시나리오

- [ ] 0. 회원가입을 합니다. (선택)

- [x] 1. ID, PW를 입력하여 로그인을 합니다. (필수 - 기능 A)

- [x] 2. 왼쪽에 프로필 사진을 추가합니다. (필수 - 기능 B)

  - [ ] 2-2. 프로필 설정을 수정할 수도 있어요. (필수 - 기능 C)

- [x] 3. 가운데 공간에서 스카이러브가 상대를 추천해줍니다. (필수 - 기능 A, C)

- [ ] 4. 왼쪽의 사람(리스트)를 클릭하면, 오른쪽에 상대방의 프로필이 나옵니다. (필수 - 기능 A, C / 선택 - 기능 B, 프로필 이미지 가리기 기능)

- [ ] 5. 상대방의 프로필 설명에는 스카이러브의 추천 이유가 포함됩니다. (선택 - 기능 C)

- [x] 6. *추천 리스트에 있는 상대를 클릭하고*, 들어가기 버튼(Match Room)을 누르면 채팅방으로 입장합니다.  (필수 - 기능 A) -> **Match Room을 통해 자동 입장으로 변경**

- [x] 7. 채팅이 이루어지고 나면, 언행점수가 변화합니다. (필수 - 기능 A) 채팅을 통해 얻은 자연어를 기반으로 단어 파싱을 진행하여 & 긍정/부정을 인식을 통해 사용자의 성향을 파악합니다.  -> **사용자 점수만 현재 추출(NLP), 추후 DB에 추가 필요**

- [x] 8. 채팅에서 나가려면 나가기 버튼을 클릭합니다. (필수 - 기능 A)



## Contributing

네이버 커넥트재단 부스트캠프에 참여하신 모든 분들의 참여 기다립니다.

#### 3주차

- Back-end

  조준형 신준수 김하균 이기훈 이승표 이소연 이상준

- Front-end

  정수원 김병국 황석영 김혜지

## License

[MIT](https://choosealicense.com/licenses/mit/)
