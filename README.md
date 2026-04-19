# takuro-sekiguchi.com

個人開発アプリのポートフォリオサイト。静的HTMLで構成され、GitHub Pages で `https://takuro-sekiguchi.com` に公開される。

## 構成

```
/                                    ← ポートフォリオHub（全アプリ一覧）
/app-ads.txt                         ← AdMob 認証（全アプリ共通）
/english-learning-app/               ← 英語学習アプリ専用
  ├── index.html                     ← LP
  ├── privacy.html                   ← プライバシーポリシー
  └── terms.html                     ← 利用規約
/assets/css/style.css                ← 共通スタイル
```

## 新しいアプリを追加するとき

1. `english-learning-app/` を丸ごとコピーして新フォルダにリネーム
2. テキストを書き換え
3. `index.html`（ホーム）にカードを追加
4. `git push` → 自動デプロイ
