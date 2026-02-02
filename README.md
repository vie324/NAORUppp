# 整体院 経営総合ダッシュボード

Google Spreadsheetと連携した整体院の経営分析ダッシュボードです。

## 機能

- 📊 KPI表示（売上、新規数、入会率、退会率など）
- 👥 スタッフ別パフォーマンスランキング
- 🏢 店舗別売上構成比
- 💰 福利厚生・手当支給状況
- 📋 詳細マスターデータテーブル
- 🔍 店舗・スタッフ名での絞り込み検索

## 使用方法

### ローカル環境で開く

1. ブラウザで `index.html` を開く
2. データが自動的にGoogle Spreadsheetから読み込まれます

### GitHub Pagesで公開

1. GitHubリポジトリにプッシュ
2. Settings > Pages > Source で `main` ブランチを選択
3. 公開されたURLにアクセス

例: https://vie324.github.io/NAORUppp/

## 技術スタック

- **React 18** - UIフレームワーク
- **Tailwind CSS** - スタイリング
- **Lucide React** - アイコン
- **Google Apps Script** - データ取得API

## ファイル構成

```
NAORUppp/
├── index.html    # メインHTMLファイル
├── App.js        # Reactアプリケーション本体
├── package.json  # プロジェクト設定
└── README.md     # このファイル
```

## データソース

Google Apps Scriptを通じてSpreadsheetからデータを取得します。
API URL: `https://script.google.com/macros/s/AKfycbzVslBpl0zqDx0m6DWgvl_uvDTD2ROXyAQOJvTSVnT0RtDeGA5H65vJWdywaGgcyN8_/exec`

## ブラウザサポート

- Chrome (推奨)
- Firefox
- Safari
- Edge

---

© 2025 整体院ダッシュボード
