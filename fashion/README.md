# 패션 계정 자동 게시

## 사용법
1. 게시물 하나당 폴더를 만들어 `fashion/inbox/` 안에 넣는다. 예: `fashion/inbox/1005_grey-cargo/`
   - 사진들을 그 안에 넣는다.
   - 아이템 정보가 있으면 `items.txt`를 같이 둔다.
     ```
     CAP / New Era / 9FIFTY 스냅백 / FREE
     TOP / Fruit of the Loom / 워싱 그래픽 티 / XL
     PANTS / Carhartt WIP / 더블니 와이드 팬츠 / 34
     SHOES / Dr. Martens / 1460 부츠 / 280
     ```
2. Claude 데스크톱 앱에서 이 레포를 열고 "fashion 폴더 올려줘"라고 말한다.
3. 캡션, 게시 순서, 사이즈 카드를 만들어 Buffer 대기열에 예약하고, 결과를 보고한다.

계정 정보와 요일·시간은 `profile.json`, 말투는 `voice.md`에서 바꾼다.
자세한 작업 순서는 `CLAUDE.md`에 있다.
