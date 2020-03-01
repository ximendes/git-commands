# Git Commands


Alterar a descrição de um commit

```
git commit -m "alterando descrição do commit" --ammend
```

Desfazer git add

```
git reset {nome arquivo ou sem nome}
```

Resetar dois commits MANTENDO os arquivos

```
<<<<<<< HEAD
<<<<<<< HEAD
git reset --soft HEAD~2
```

Resetar dois commits REMOVENDO os arquivos

```
git reset --hard HEAD~2
```

Incluir partes do arquivo editado em um commit e partes não
=======
=======
>>>>>>> a1c6ab10726d3acc415f115c578c42cb6e18d559
git reset --soft~2
```

Resetar dois commits REMOVENDO os arquivos
```
git reset --hard HEAD~2
```
Incluir partes do arquivos editado em um commit e partes não
<<<<<<< HEAD
>>>>>>> a1c6ab10726d3acc415f115c578c42cb6e18d559
=======
>>>>>>> a1c6ab10726d3acc415f115c578c42cb6e18d559

```
git add -p
```

Exibe a árvore de commits

```
git log --graph
```
