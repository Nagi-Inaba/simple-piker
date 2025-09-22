# シンプル抽選（GitHub Pages 用）

1ファイル（`index.html`）だけのランダム抽選アプリです。入力はブラウザの `localStorage` に自動保存され、スマホ/PC両対応です。

## 使い方（スマホからGitHubへ）
1. GitHub を開く → **New repository**
2. リポジトリ名を入力（例: `simple-picker`）→ **Public** を選択 → 作成
3. リポジトリ画面で **Add file → Upload files** をタップし、`index.html` をアップロード
4. Settings → **Pages** → Branch を `main` と `/ (root)` に設定 → **Save**
5. 数十秒後、`https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます

> ルートに置くファイルは **index.html** にしてください（GitHub Pages のデフォルト）。

## ローカルデータについて
- 入力内容は端末ごとに `localStorage`（キー: `simplePickerListV1`）に保存されます。他の人からは見えません。
