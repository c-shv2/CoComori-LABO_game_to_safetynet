# GitHub整理メモ

## いまの状態

- `README.md` を追加済み
- `.gitignore` を追加済み
- 通常画像16枚と `_share.png` 画像16枚が揃っています
- `.codex-script-check.js` と `__check_script.js` は検査用ファイルなのでGitHubに入れません

## GitHub Desktopで上げる場合

1. GitHub Desktopを開く
2. `File` > `Add local repository...` を選ぶ
3. このフォルダを選ぶ
4. リポジトリ未作成の場合は `create a repository` を選ぶ
5. 変更一覧で `.codex-script-check.js` と `__check_script.js` が出ていないことを確認する
6. コミット名は `Add CoComori diagnosis game` などにする
7. `Publish repository` でGitHubへ公開する

## GitHub Pagesで公開する場合

1. GitHubのリポジトリ画面を開く
2. `Settings` > `Pages` を開く
3. `Deploy from a branch` を選ぶ
4. Branchを `main`、フォルダを `/root` にする
5. 表示されたURLで `index.html` が開けることを確認する

公開URLで開いた場合だけ、LINE/Xの共有文に診断URLが自動で入ります。
