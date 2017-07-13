# mecatronica_unb

Material referente a diciplinas e atividades feitas ao longo do curso de Engenharia Mecatrônica na UnB. Cada disciplina fica em um branch separado e todo material público é referenciado através submodulos dentro do respectivo branch. Por padrão os branch de matérias da unb começam com "unb-" e a sigla do nome da matéria e os branchs de matérias feitas durante o intercâmbio começam com "wsu-" e são seguidos pelo código da diciplina.

## Lista de Matérias

### UnB

* [SisMed](https://github.com/akafael/mecatronica_unb/tree/unb-sismed): Sistemas de Medição
* [TCM](https://github.com/akafael/mecatronica_unb/tree/unb-tcm): Transporte de Calor e Massa
* [PTR](https://github.com/akafael/mecatronica_unb/tree/unb-ptr): Programação em Tempo Real

### Wayne State University



## Dicas

### Comandos Git Branch

Criando novo branch com o nome "unb-novamateria"

```
git branch unb-novamateria
``` 

Mudando de um Branch para outro

```
git checkout outro-branch
```

### Comandos Submodulos

Vinculando um repositório existente como submodulo dento da pasta "nomePastaSubmodulo"

```
git submodule add https://github.com/akafael/meuOutroRepositorio nomePastaSubmodulo
```

