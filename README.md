# 木芽─Muya─ サイトスターター

このフォルダをそのまま GitHub にアップすると、GitHub Pages で公開できます。

## 手順（超かんたん）
1. GitHub にログインし、新規リポジトリを **muya-site** などの名前で作成（Public 推奨）。
2. 「Add file」→「Upload files」でこのフォルダ内のファイルをドラッグ＆ドロップ。
3. 下の方で **Commit**（=保存）します。
4. 右上の **Settings** → 左メニューの **Pages** →
   - Source: **Deploy from a branch**
   - Branch: **main / (root)** を選んで **Save**。
5. しばらくすると表示用の URL が出ます。`https://ユーザー名.github.io/リポジトリ名/`

## 独自ドメインを使う場合（任意）
- ドメイン側の DNS で CNAME を `ユーザー名.github.io.` に向ける
- Settings → Pages → Custom domain に自分のドメインを入力し **Save**
- 下の **Enforce HTTPS** にチェック

## 画像を差し替える
- `images` 配下の `product-*.jpg` を入れ替え
- OG 画像はリポジトリ直下に `og-image.jpg` を置く（推奨 1200×630）

## よくあるつまずき
- ファイル名は必ず **index.html**（小文字）
- 画像パスの先頭 `/images/...` がズレる場合は `images/...` に変更
- 変更後は **Commit** しないと公開に反映されません

Enjoy! 🌱
