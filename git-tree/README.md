## Gitのコミット履歴を見やすくする。

```sh
$ vi ~/.gitconfig

---

[alias]
        tree = log --graph --pretty=format:'%x09%C(auto) %h %Cgreen %ar %Creset%x09by"%C(cyan ul)%an%Creset" %x09%C(auto)%s %d'
```
