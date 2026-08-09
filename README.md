# github-first-test

Claude CodeとGitHubの連携を学ぶための練習用リポジトリです。

## 内容

- `index.html`: カラフルなHello Worldページ(クリックできるボタン付き)
- `about.html`: このプロジェクトについての説明ページ
- `README.md`: このファイル

## ブランチ運用ルール(GitHub flow)

このリポジトリでは、以下の流れで変更を行います。

1. `main`ブランチから作業用の`feature/〇〇`ブランチを作成する
2. `feature/〇〇`ブランチ上でファイルを編集・追加し、コミットする
3. `feature/〇〇`ブランチをGitHubにプッシュする
4. `main`向けにPull Request(PR)を作成する
5. GitHub上でPRの内容(Files changedタブ)を確認する
6. 問題なければブラウザ上でマージする
7. マージ後、不要になった`feature/〇〇`ブランチを削除する
8. ローカルの`main`を最新化し、ローカル側のブランチも削除する

- `main`ブランチには直接コミットせず、必ずPR経由で変更する
- ブランチ名は `feature/変更内容がわかる名前` の形式にする
