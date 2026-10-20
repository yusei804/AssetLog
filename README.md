# AssetLog

試験対策の学習時間を記録・集計するPWA（ホーム画面に追加して使えます）。

## GitHub Pages で公開する手順
1. GitHubで新しいリポジトリを作成し、このフォルダの中身（index.html / manifest.json / sw.js / icons）をリポジトリ直下にアップロード
2. Settings → Pages → Branch を `main` / `(root)` にして Save
3. 発行されたURL（https://ユーザー名.github.io/リポジトリ名/）をスマホで開く
4. iPhone: 共有 → ホーム画面に追加 / Android: メニュー → アプリをインストール

## 補足
- データは端末のブラウザ（localStorage）に保存されます。端末間の同期は含まれません。
- 更新するときは `index.html` を差し替え、`sw.js` の `CACHE` 名（現在 assetlog-v2）を v2 などに変更してください。
