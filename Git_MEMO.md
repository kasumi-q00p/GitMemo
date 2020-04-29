# Git学習メモ
## Gitコマンド

-- git init ローカルリポジトリを作る
- git add .　カレントディレクトリ配下のすべてのファイルを追加
- git add filename　指定したファイルのみ追加
- git status ローカルリポジトリ状態を確認
- git diff　差分を確認
- git restore ファイルをステージングエリアの状態に戻す
- git reset HEAD file name　ステージングエリアの登録を取り消す(ファイルの内容はそのまま)
- git rm　コミットしたファイルを削除。この後に、削除しとことをcommitする
- gitで管理しないファイルの設定　(VScodeで.gitignoreファイルを作成し、その中に無視したいファイル名を記載)
- git log　コミット履歴を確認（-pオプションで差分表示）

## 共同作業
- Fork　Github上のリポジトリの複製
- git clone　ローカルリポジトリに取得
- git branch name　ブランチを作製
- git branch　使用中のブランチを確認　＊が今のブランチ
- git checkout name　ブランチをチェックアウトする
-git commit -am"コメント"　更新されたファイルをステージングエリアに追加して、そのままコミットする
- commit , push origin filename, プルリクエスト作成、レビュー、マージ

追加する