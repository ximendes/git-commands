# Git Commands


Alterar a descrição de um commit

```
git commit -m "alterando descrição do commit" --amend
```

Desfazer git add

```
git reset {nome arquivo ou sem nome}
```

Resetar dois commits MANTENDO os arquivos

```
git reset --soft HEAD~2
```

Resetar dois commits REMOVENDO os arquivos

```
git reset --hard HEAD~2
```

Resetar commit por tempo

```
git reset --hard master@{"10 minutes ago"}
```

Incluir partes do arquivo editado em um commit e partes não

```
git add -p
```

Delete Local Branch
```
git branch -d localBranchName
```

Delete Remote Branch
```
git push origin --delete remoteBranchName
```

Exibe a árvore de commits

```
git log --graph
```


Fetch tags

```
git fetch tag
```

Exibe Ultima Tag

```
git describe --tags $(git rev-list --tags --max-count=1)
```

