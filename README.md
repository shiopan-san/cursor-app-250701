# cursor-app-250701

cursor スマホアプリ検証用

## 概要

このプロジェクトは、Next.js 14 (App Router) を使用したWebアプリケーションです。

## 技術スタック

- **Next.js 14** (App Router)
- **React 18**
- **TypeScript**
- **Tailwind CSS**
- **ESLint**

## 開発環境のセットアップ

### 必要な環境

- Node.js 18以降
- npm または yarn

### インストール

```bash
npm install
```

### 開発サーバーの起動

```bash
npm run dev
```

開発サーバーは [http://localhost:3000](http://localhost:3000) で起動します。

### その他のコマンド

```bash
# ビルド
npm run build

# 本番環境での起動
npm run start

# ESLintチェック
npm run lint
```

## プロジェクト構成

```
├── src/
│   └── app/
│       ├── globals.css
│       ├── layout.tsx
│       └── page.tsx
├── public/
├── tailwind.config.js
├── tsconfig.json
├── next.config.js
├── postcss.config.js
└── .eslintrc.json
```