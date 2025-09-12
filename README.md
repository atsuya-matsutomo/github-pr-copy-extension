# GitHubPRコピーくん

GitHub PR（Pull Request）のタイトルをリンク付きでコピーするChrome拡張機能です。

## 機能

- GitHub PRページでタイトルの横にコピーボタンを表示
- クリックするとPRタイトルがリンク付きでクリップボードにコピー
- Slack、Discord、Google Docsなどにペーストすると自動的にリンク付きテキストとして表示

## 対応ブラウザ

- Google Chrome
- Arc
- その他Chromium系ブラウザ

## インストール方法

### 方法1: ZIPファイルをダウンロードする場合

1. このリポジトリの「Code」ボタンから「Download ZIP」を選択
2. ダウンロードしたZIPファイルを任意の場所に解凍

### 方法2: Gitでクローンする場合

```bash
git clone https://github.com/YOUR_USERNAME/github-pr-copy-extension.git
```

### ブラウザへの導入手順

1. ブラウザで拡張機能管理ページを開く
   - **Google Chrome**: `chrome://extensions/`
   - **Arc**: `arc://extensions/`

2. 右上の「デベロッパーモード」または「開発者モード」をONにする

3. 「パッケージ化されていない拡張機能を読み込む」をクリック

4. 解凍した `github-pr-copy-extension` フォルダを選択

5. 拡張機能一覧に「GitHubPRコピーくん」が表示されれば導入完了

## 使い方

1. GitHubのPRページを開く
2. PRタイトルの左横に表示されるコピーボタンをクリック
3. お好きな場所にペースト

## ライセンス

The Unlicense（パブリックドメイン）

## 開発

この拡張機能は[Claude Code](https://claude.ai/code)を使用して作成されました。

## 貢献

Issue報告やPull Requestは大歓迎です！