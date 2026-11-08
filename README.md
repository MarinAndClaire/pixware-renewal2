# PIXWARE OFFICIAL SITE リニューアル版

株式会社 Pixware 公式サイト（https://pixware.co.jp/）のリニューアル版です。現行サイトの情報をすべて引き継いだうえで、デザインと構成を整え、PCとスマートフォンの両方で見やすくしています。

公開URL（GitHub Pages）：https://marinandclaire.github.io/pixware-renewal2/

## ページ構成

URLは現行サイトと同じにしているので、本番に移すときにリンク切れが起きません。

| ページ | ファイル |
|---|---|
| ホーム | `index.html` |
| エルミオン・バックライト | `lmion-backright/index.html` |
| クリスタル・エルミオン® | `crystal-lmion/index.html` |
| 会社概要 | `profile/index.html` |
| お問い合わせ | `contact-form/index.html` |
| 個人情報保護方針 | `pixware-privacy/index.html` |
| 特定商取引法に基づく表記 | `pixware-law/index.html` |
| デザイン・動き | `assets/style.css` / `assets/main.js` |

## 注意点

- **画像・動画**：現行サイト（`https://pixware.co.jp/wp-content/uploads/…`）のファイルを直接読み込んでいます。本番に移すときは画像をこのリポジトリの `assets/img/` などにコピーし、パスを差し替えてください。
- **お問い合わせフォーム**：GitHub Pages ではフォームを送信できないため、送信ボタンを押すと現行フォームへの案内を表示します。本番ではメール送信の仕組み（WordPressのContact Form 7、Formspreeなど）につなぎます。
- **Instagram / YouTube**：現行サイトと同じく各サービスのトップページにリンクしています。自社アカウントのURLに差し替えてください。

## 現行サイトから修正した点

- 「株式会社 Pioxware」の誤字を「Pixware」に修正
- 所在地のビル名「ガーデニアコート都島 8F」をすべてのページに記載
- 「クリスタル・エルミオン® とは」の重複見出しを1つに整理
- トップの製品紹介から各製品の詳細ページへのリンクを追加
- 画像の代替テキスト（alt）を「サンプル画像」から内容がわかる説明に変更
- 各ページに検索結果用の説明文と、SNS共有用の画像（OGP）を設定
