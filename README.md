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

Incluir partes do arquivo editado em um commit e partes não

```
git add -p
```

Exibe a árvore de commits

```
git log --graph
```
