# Voice Narrator Text-to-speech ウェブサイト

このリポジトリは「Voice Narrator Text-to-speech」アプリのウェブサイトのソースコードを管理しています。ウェブサイトはFirebase Hostingを使用して公開されています。

## 概要

このウェブサイトはテキスト読み上げアプリ「Voice Narrator」の公式サイトです。アプリの機能説明、プライバシーポリシー、利用規約などの情報を提供しています。

## ウェブサイトURL

- **公開URL**: [https://voiceyourtext.web.app](https://voiceyourtext.web.app)

## ディレクトリ構造

```
public/
├── index.html         # メインページ
├── privacy_policy.html # プライバシーポリシー
├── terms_of_service.html # 利用規約
├── app-ads.txt        # 広告設定ファイル
└── 404.html           # 404エラーページ
```

## セットアップと開発

### 前提条件

- Node.js と npm がインストールされていること
- Firebase CLI がインストールされていること

### ローカル環境での実行

1. リポジトリをクローン
   ```
   git clone <リポジトリURL>
   cd voiceYourTextAdmob
   ```

2. Firebase CLIのインストール（まだの場合）
   ```
   npm install -g firebase-tools
   ```

3. Firebaseにログイン
   ```
   firebase login
   ```

4. ローカルでサイトを実行
   ```
   firebase serve
   ```
   
   これでローカルホスト（通常 http://localhost:5000）でサイトが表示されます。

### デプロイ方法

Firebaseへのデプロイは以下のコマンドで実行できます：

```
firebase deploy
```

## 最終更新

- プライバシーポリシー: 2025年04月22日
- 利用規約: 2025年04月22日

## ライセンス

© 2025 遠藤拓弥. All rights reserved. 