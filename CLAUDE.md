# hono-drizzle-starter

ユーザーから

## プロジェクト概要

TypeScript製バックエンドAPIのスターターテンプレート。
Hono + Drizzle ORM + PostgreSQL + Zod で構成されている。

## 技術スタック

- **Runtime**: Node.js
- **Framework**: Hono
- **ORM**: Drizzle ORM
- **DB**: PostgreSQL
- **Validation**: Zod
- **Language**: TypeScript

## ディレクトリ構成

```
src/
index.ts # エントリポイント
routes/ # ルーティング
db/
schema.ts # Drizzleスキーマ
client.ts # DBクライアント
```

## 開発ルール

- スキーマ変更は必ずマイグレーションを通す
- バリデーションはZodで行う
- 環境変数は.envで管理する（.env.exampleを参照）
