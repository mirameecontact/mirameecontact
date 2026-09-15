# Miramee corporate site

GitHub Pages用の統合サイトです。

- `/index.html`: Mirameeコーポレートサイト
- `/toremee/index.html`: Toremeeプロダクトサイト
- `CNAME`: カスタムドメイン `miramee.me`

GitHubへは、この`dist`フォルダの「中身」をリポジトリのルートへアップロードしてください。

## 公開後のURL

- Miramee: `https://miramee.me/`
- Toremee: `https://miramee.me/toremee/`

## GitHub Pages設定

1. リポジトリの `Settings` → `Pages` を開く
2. `Deploy from a branch`、`main`、`/(root)` を選ぶ
3. `Custom domain` に `miramee.me` を入力して保存する
4. DNS側で `miramee.me` のAレコードをGitHub Pagesへ向ける
5. 証明書の準備完了後に `Enforce HTTPS` を有効にする

このパッケージにはルート用の `CNAME` ファイルを同梱しています。
