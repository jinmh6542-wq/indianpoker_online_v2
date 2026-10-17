# Indian Poker 온라인 서버

Node.js 18 이상 필요. `npm install` 후 `npm start` 실행, 브라우저에서 `http://localhost:3000` 접속.

서로 다른 네트워크의 친구와 플레이하려면 Node.js WebSocket을 지원하는 HTTPS 호스팅(Render/Railway 등)에 이 폴더를 배포하고 같은 HTTPS 주소로 접속하세요. HTTPS에서는 자동으로 WSS를 사용합니다.

방장이 6자리 코드를 만들고 친구가 참가한 뒤 게임 시작을 누릅니다. 카드는 서버에서 생성하며 본인 카드의 값은 라운드 종료 전까지 전송하지 않습니다. 서버 재시작 시 방은 삭제됩니다. 로그인/재접속 복구/장기 저장은 제공되지 않습니다.
