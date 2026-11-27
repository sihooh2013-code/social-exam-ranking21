# 사회 모의고사 랭킹 서버

중학교 1학년 사회 모의고사 온라인 랭킹 서버입니다.

## 실행 방법

Node.js 20 이상이 필요합니다.

```bash
npm install
npm start
```

## 서버 상태 확인

`/api/health`

정상 작동 시 다음 결과가 표시됩니다.

```json
{"ok":true}
```

## API 목록

- GET /api/health
- GET /api/leaderboard
- POST /api/scores

## 기술

- Node.js
- Express
- SQLite
