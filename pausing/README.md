# 트윕의 일시정지 모양을 바꿔주는 CSS

트윕 알림박스의 '일시정지' 아이콘을 바꿔주는 CSS입니다.

![](https://cdn.discordapp.com/attachments/362948388217683971/745984020537540718/unknown.png) ==>> ![](https://cdn.discordapp.com/attachments/362948388217683971/745958650098483200/TREDECEMBERCHORUS_THIS_GAME_ANIMATION-WORKSPACE_2020-08-20_19.53.03.png)

직사각형 아이콘 대신에 템플릿 이미지나 사용자 이미지를 넣을 수 있도록 해 줍니다.

=

# 적용 예시

![](https://cdn.discordapp.com/attachments/362948388217683971/745987982338555954/unknown.png)
![](https://cdn.discordapp.com/attachments/362948388217683971/745989022714691654/unknown.png)

=

# 적용법

- [여기](https://github.com/Pindang2/Twitch-Experiences/blob/master/pausing/pausing-changer01.css)로 가서, CSS 내용을 복사합니다.
- [Twip 대시보드 -> Alert Box](http://twip.kr/dashboard/alertbox)로 접속합니다.
- 아래쪽에 '커스텀 CSS'를 입력할 수 있는 공간이 있습니다. 이 곳 맨 아래에 붙여넣기합니다! ![](https://cdn.discordapp.com/attachments/362948388217683971/745990709093466152/unknown.png)

- `background:url(링크)`의 링크 부분을 수정하여 스스로 만든 이미지를 적용할 수 있습니다.
  디스코드에 이미지를 올린 후, 그 이미지의 원본 버전을 브라우저에서 연 뒤, 주소를 복사해 바꿔치기하면 됩니다.
- `width: ~~px;`, `height: ~~px;` 부분을 수정해 직접 바꾼 이미지의 크기로 맞춰주거나,
  직접 사이즈를 더 크게 수정해 더 크게 보이도록 할 수 있습니다.
- `filter: hue-rotate(0deg);`의 `0deg` 숫자를 바꿔 색상을 변경할 수 있습니다.
 (0deg, 10deg, 30deg, 180deg... 359까지 가능합니다.)
  ![](https://cdn.discordapp.com/attachments/362948388217683971/745991550080647188/unknown.png)

- **직접 설정을 차근차근 적용해보면서, 본인에게 맞는 스타일을 찾으시기 바랍니다.**
- **Twip 대시보드에서 코드를 붙여넣은 다음, 입력창 밖으로 마우스를 한 번 클릭해주면 저장하기 버튼이 생깁니다. 이 버튼까지 눌러야 적용이 됩니다. 만약 적용하기 버튼이 생기지 않는다면, 코드줄 맨 끝 아무데나 스페이스바를 한 번 먹여주고 코드창 밖을 클릭해보세요.**
