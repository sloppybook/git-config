# git-config

.gitの中身

1. .git/info/exclude
gitignoreに載せるほどでもないようなローカルでのみ無視したいファイルを記載する
```
echo .vscode/* >> .git/info/exclude
```
