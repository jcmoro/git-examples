```
git stash (list|pop)
git stash pop 1

git branch 
git branch nueva-rama
git branch nueva-rama -d

git checkout rama
git checkout -b nueva-rama

git tag
git tag "v1.0.0"

git revert id-commit

git branch -a
```

Crear un alias en git
```
Añadir alias de git en .gitconfig
```

Merge
```
git log --graph --abbrev-commit --oneline
desde nuestra rama: git merge master
```

Rebase
```
desde nuestra rama: git rebase master
```

Rebase interactive (squash)
```
3 commits más atrás:

git rebase -i HEAD~3

s para squash (combina el commit con el anterior)
r para cambiar nombre

git push -f
```

Pull Rebase
```
git pull origin rama --rebase
```

Resolve conflict
```
git pull --rebase --autostash

```

