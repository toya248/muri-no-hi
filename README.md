# 無理な日の手順書

精神的に無理な日に、上から順に読むための1ページ。慰めではなく、過去の自分が確かめたことと、やる順番だけを置く。

- `index.html` 1ファイルのみ。ビルド不要
- 手順3（確認済みのこと）・5（決めたこと）・6（連絡先）・7（記録）は自分で書き足す欄。内容はブラウザの localStorage にだけ保存され、サーバーには送られない
- フッターからテキスト書き出し／全消去ができる

## GitHub Pages に置く

1. 新しいリポジトリを作る（公開でも非公開でもよい。Pages は無料プランでは公開リポジトリのみ）
2. `index.html` と `README.md` をルートに置いて push
3. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `/ (root)` にして Save
4. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で表示される

カスタムドメインを使う場合は同じ画面の Custom domain に入力し、DNS に CNAME を追加する。
