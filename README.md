# corporate-info

合同会社andITの会社情報Webサイト

## ローカルで確認する方法

### 必要なもの
- Ruby (3.0以上推奨)
- Bundler

### セットアップ

```bash
# 依存関係のインストール
bundle install

# ローカルサーバー起動
bundle exec jekyll serve
```

ブラウザで http://localhost:4000/corporate-info/ を開いて確認できます。

### ホットリロード
ファイルを編集すると自動で再ビルドされます（ブラウザの更新は手動）。

## GitHub Pagesへのデプロイ

1. GitHubにプッシュ
2. Settings → Pages → Source: **GitHub Actions** を選択
3. 自動でビルド＆デプロイされます

## ファイル構成

```
├── _config.yml      # サイト設定
├── _includes/       # テンプレートパーツ
├── _layouts/        # レイアウト
├── _sass/           # スタイルシート
├── assets/          # 画像・JS・CSS
├── index.md         # ホームページ
├── services.md      # 事業内容
├── company.md       # 会社情報
├── contact.md       # お問い合わせ
└── Gemfile          # Ruby依存関係
```

## テーマ

[Forty Jekyll Theme](https://github.com/andrewbanchich/forty-jekyll-theme) を使用
