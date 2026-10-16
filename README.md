# MP Proxy

シンプルで安全志向の Web プロキシ（Node.js + TypeScript + Express）

## 概要
このリポジトリは、サーバー経由で外部ページを取得して表示する簡易プロキシサービスの実装例です。SSRF 対策やタイムアウト、サイズ上限、レートリミットなどの安全策を含んでいます。

## ファイル構成
- README.md
- .env.example
- package.json
- tsconfig.json
- Dockerfile
- src/
  - server.ts
  - proxy.ts
  - config.ts
  - utils.ts
- public/
  - index.html

## ライセンス
MIT
