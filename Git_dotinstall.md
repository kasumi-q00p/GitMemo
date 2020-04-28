## Git入門

Git scm pro git 日本語ページ
https://git-scm.com/book/ja/v2

- git help
- git add .
- git commit -m "コメント"
- git commit --amend　 直前のコミットを変更する
- git status
- git push

- git diff　addする前に差分を見るとき
- git diff --cached　addした後に差分を見るとき

- git rm filename　ファイルを削除する
- git mv filename　ファイルを移動する
<<<<<<< HEAD

- git reset --hard HEAD　直前のVerに戻す
- git reset --hard HEAD^　二つ前に戻す
- git reset --hard ORIG_HEAD リセットしたものを元に戻す（コミットしたもの）
=======
- git add
- git commit 
- git status
- git push
>>>>>>> 0a64bc6190a2a0daa08244f05f4153088593c7e2
