プロジェクトを作る
GithubのCollaboratorに誰かを追加する

$ git clone <url>

$ ls -lrt

$ cd <cloneしたレポジトリ名（=ディレクトリ名）>

$ pwd

$ ls

$ ls -a

$ git status

$ git branch

$ git branch feature/add_<your_name>_file

$ git branch

$ git checkout feature/add_<your_name>_file

$ git branch

$ touch <your_name>.md
your_nameは以下のルールで入力する
- 氏、名の順
- 小文字アルファベット
- ハイフン区切り
- koyama-yoshihito.md

$ ls

$ vi <your_name>.md

$ i

一行目にファイル名と同じ氏名を記入する。
例：koyama-yoshihito

escキーを押す

:wqを押す

エンターキーを押す

$ cat <your_name>.md

$ git status

$ git add <your_name>.md

$ git status

$ git commit -m "<your_name>.mdを追加"
<your_name>は自分が追加したファイル名に置き換える

$ git log

$ git log --oneline

$ git push

$ git push --set-upstream origin feature/add_<your_name>_file

GitHubを開いてPull Requestを作成する

小山がApproveしたらマージする

$ git checkout main

$ git branch

$ git log --oneline

$ git pull

$ git log --oneline

$ git branch --delete feature/add_<your_name>_file

$ git branch
