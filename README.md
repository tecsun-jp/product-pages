# 徳勝商店 Product Pages

複数の商品ページを1つのGitHub Pagesサイトで管理するためのリポジトリです。

## 公開URL

- 商品一覧：`https://tecsun-jp.github.io/product-pages/`
- 興宜和KOGIWA とうもろこし麺：`https://tecsun-jp.github.io/product-pages/kogiwa-corn-noodles/`

## GitHub Pagesの設定

1. GitHubのリポジトリで **Settings → Pages** を開きます。
2. **Build and deployment** の Source で **Deploy from a branch** を選びます。
3. Branch は **main**、フォルダーは **/(root)** を選択します。
4. **Save** を押し、公開完了まで数分待ちます。

## 商品を追加する場合

新しい商品ごとに英数字のフォルダーを追加し、その中に `index.html`、`style.css`、`assets/` を置きます。ルートの `index.html` に商品カードを追加すると、商品一覧にも表示できます。
