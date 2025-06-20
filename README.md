# 私の経験と成長 - My Portfolio

このリポジトリは、GitHub Pagesを使用したポートフォリオサイトです。多様な経験から学んだ価値と成長の軌跡を紹介しています。

## 🎨 テーマ設定

このサイトでは、GitHub Pagesでサポートされている複数のJekyllテーマを簡単に切り替えることができます。

### テーマの変更方法

1. `_config.yml` ファイルを開く
2. 「Theme Selection」セクションで好きなテーマのコメントアウトを外す
3. 他のテーマをコメントアウトする
4. 変更をコミット・プッシュする

### 利用可能なテーマ

- **Cayman** (現在のテーマ): クリーンで現代的なデザイン
- **Minima**: シンプルで最小限のデザイン
- **Architect**: モダンなデザイン
- **Leap Day**: 緑を基調とした現代的なテーマ
- **Midnight**: ダークテーマ
- **Modernist**: クリーンで最小限のデザイン
- **Slate**: サイドバー付きのダークテーマ
- **Tactile**: ナビゲーション付きのクリーンなテーマ
- **Time Machine**: レトロスタイル

### テーマ変更例

```yaml
# 現在のテーマをコメントアウト
# remote_theme: pages-themes/cayman@v0.2.0

# 新しいテーマを有効化
remote_theme: pages-themes/midnight@v0.2.0
```

## 📁 ファイル構成

```
git-pages/
├── _config.yml                    # Jekyll設定ファイル
├── index.html                     # メインページ
├── style.css                      # カスタムスタイル
├── animal_chara_radio_penguin.png # 画像ファイル
└── README.md                      # このファイル
```

## 🚀 使用方法

1. このリポジトリをフォークまたはクローン
2. GitHub Pagesを有効化
3. `_config.yml` でサイト情報を更新
4. 好きなテーマを選択
5. 内容をカスタマイズ

## 🛠️ カスタマイズ

### サイト情報の変更

`_config.yml` ファイルで以下の項目を編集：

```yaml
title: あなたのサイトタイトル
description: あなたのサイト説明文
author:
  name: あなたの名前
  email: your-email@example.com
```

### コンテンツの変更

- `index.html`: メインページの内容
- `style.css`: カスタムスタイルの追加・変更

## 📱 レスポンシブデザイン

このサイトはモバイルフレンドリーで、以下のデバイスに対応：
- デスクトップ
- タブレット
- スマートフォン

## 🔧 技術仕様

- **Framework**: Jekyll
- **Hosting**: GitHub Pages
- **CSS**: カスタムCSS with グラスモーフィズムデザイン
- **JavaScript**: 必要に応じて追加可能

## 📈 SEO最適化

`_config.yml` には以下のSEO設定が含まれています：

- Jekyll SEO Tag プラグイン
- サイトマップ自動生成
- RSS フィード
- Google Analytics 対応（オプション）

---

✨ **注意**: テーマを変更した後は、GitHub Pagesの反映に数分かかる場合があります。