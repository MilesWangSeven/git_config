# git_config
take notes for git

## git config

git 显示分支

git ba 显示所有分支

```bash
git config --global alias.ba "branch --format '%(color:bold red)%(HEAD) %(color:bold yellow)%(align:32,left)%(refname:short)%(color:bold red)%(if)%(upstream:short)%(then)->%(upstream:short)%(else) %(end)%(end)%(color:bold blue) %(objectname:short) %(color:white)- %(color:bold green)(%(authordate:iso)) %(color:white)%(subject)%(color:dim white) - %(authorname)%(authoremail)' --all"
```



git lga 所有分支

git lgc 当前分支

```bash
git config --global alias.lga "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ai)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an<%ae>%C(reset)%C(bold yellow)%d%C(reset)' --all"
git config --global alias.lgc "log --graph --abbrev-commit --decorate --format=format:'%C(bold blue)%h%C(reset) - %C(bold green)(%ai)%C(reset) %C(white)%s%C(reset) %C(dim white)- %an<%ae>%C(reset)%C(bold yellow)%d%C(reset)'"
```

