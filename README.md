# Pictana サポートサイト

Pictana iOSアプリの日本語サポートページとプライバシーポリシーを配信する、アプリ本体とは別のGitHub Pages用公開リポジトリです。

HTML/CSS/JavaScriptのみで動作し、独自のアクセス解析、広告タグ、Cookie、ビルドサービスは使いません。

## 公開URL

- サポート: `https://m5t21k.github.io/pictana-pages/support/`
- プライバシーポリシー: `https://m5t21k.github.io/pictana-pages/privacy/`
- 利用規約: Apple標準EULAを使用

## 公開情報の更新

`config.js`で共通表示を管理します。

- `supportEmail`: 問い合わせ先メールアドレス
- `operatorName`: 運営者表示名
- `effectiveDate`: ポリシー発効日

アプリのデータフロー、広告SDK、クラウド解析、同意画面、App Store ConnectのApp Privacy回答を変更するときは、提出するアプリビルドと本ポリシーを照合して更新してください。

`main`へのpushでGitHub ActionsがGitHub Pagesへ公開します。

