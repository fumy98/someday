# Someday — 公式 LP

iOS アプリ「Someday - やりたいこと バケットリスト」の紹介ページ。
GitHub Pages で公開: https://fumy98.github.io/someday/

- `index.html`（日本語・英語）・`img/`（スクリーンショット、ja/en 各6枚・552px JPEG）・共有カード用の画像。外部 CDN なし
- `privacy.html`（iOS 版）・`privacy-android.html`（Android 版「100 List」）のプライバシーポリシー
- `ogp.png`(1200x630) は SNS・チャットのリンクカード用。data: URI はクローラーが読めないため実ファイルで置く。作り直すときは LP の意匠に合わせたテンプレートを Chrome の headless で 1200x630 に描画する
- `icon-180.png` / `favicon-32.png` はアプリアイコン(`bucketlist-app` の AppIcon.png)から生成
- App Store: https://apps.apple.com/app/apple-store/id6804606288?pt=129352997&ct=LP&mt=8
- 掲載するのは App Store で公開済みの情報のみ。アプリ本体のソースは別の非公開リポジトリで管理
- 2026-10-05: v1.2 の内容(共有・リアクション・思い出・並び替え)に合わせて全面更新。スクリーンショットは `bucketlist-app/docs/appstore/screenshots/ja/` の素撮りを 560px JPEG にして埋め込み
- 2026-10-08: 料金セクションを請求額主体(月 ¥480 を最大表示・無料期間は補足)に変更、1.2.2 の機能と FAQ を追記。スクリーンショットも 1.2.2 の素撮り(`bucketlist-app/docs/appstore/screenshots/ja/`、2026-10-06 撮影。ヘッダー 使い方/プレミアム/メンバー・写真帯)に差し替え
- 2026-11-13: fumy98.github.io のトップ・HoshoBox の LP と同じ組み立てに全面作り直し（罫線の背景・朱の斜線の見出し・使い方5枚・特長・料金・FAQ・英語版）。スクリーンショットは base64 をやめて `img/` に置いた。プライバシーポリシーもこのリポジトリに置き、広告（AdMob）・共有・課金を追記
