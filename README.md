# Todo App Handson

シンプルで使いやすいタスク管理アプリケーションです。

## 📋 概要

Todo App Handsonは、日常のタスク管理を効率的に行うためのWebアプリケーションです。
ブラウザに組み込まれたLocalStorageを使用してデータを保存するため、
サーバーの構築やデータベース接続が不要で、すぐに使い始められます。

## 🛠️ 技術スタック

このプロジェクトは以下の技術で構成されています：

| 技術 | 用途 |
|------|------|
| **HTML** | ページ構造の定義 |
| **CSS** | スタイリング・レイアウト |
| **JavaScript** | アプリケーション機能の実装 |
| **LocalStorage** | データの永続化・保存 |

### 特徴

- 🚀 **フロントエンドのみ**: バックエンドなしで動作
- 💾 **ローカル保存**: ブラウザのLocalStorageにデータ保存
- 📱 **レスポンシブ**: スマートフォン・タブレットに対応
- ⚡ **高速**: キャッシュなしで素早く動作
- 🔒 **プライバシー重視**: 全データはクライアント側で管理

## 🚀 セットアップ

```bash
# リポジトリをクローン
git clone https://github.com/kobayashi-toshihiko/todo-app-handson.git

# ディレクトリに移動
cd todo-app-handson

# ブラウザで index.html を開く
open index.html
# または
start index.html  # Windows
```

## 📖 使い方

1. タスクを入力してEnterキーを押すか、追加ボタンをクリック
2. 完了したタスクにチェックマークを付ける
3. 不要なタスクは削除ボタンで削除
4. すべてのデータはブラウザに自動保存されます

## 🏗️ プロジェクト構成

```
todo-app-handson/
├── README.md           # このファイル
├── index.html          # HTMLファイル
├── css/
│   └── style.css       # スタイルシート
└── js/
    └── app.js          # アプリケーション機能
```

## 🔧 開発

### 前提条件

- 最新のWebブラウザ（Chrome、Firefox、Safari、Edge）
- テキストエディタまたはIDE

### 開発サーバーの起動

簡易サーバーで実行する場合：

```bash
# Python 3 の場合
python -m http.server 8000

# Node.js の場合
npx http-server

# その後、ブラウザで http://localhost:8000 にアクセス
```

## 📝 ライセンス

このプロジェクトはMITライセンスの下で公開されています。

## 🤝 貢献

バグ報告や機能提案は、GitHubのIssuesで気軽にお知らせください。
プルリクエストも歓迎します！

## 📧 お問い合わせ

ご質問や提案がありましたら、Issuesで教えてください。