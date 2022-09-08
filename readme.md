# Projetos de Alunos DevPleno

Este repositório lista os projetos de alunos entregues em seus respectivos módulos. Cada projeto deverá ser revisado por outro aluno e/ou pela equipe DevPleno.

Este repositório consiste em 2 partes:

- students: neste diretório consta a lista de todos os alunos que realizaram alguma entrega de projeto.
- projects: neste diretório consta todos os projetos disponíveis para entrega. Atente-se que vários deles estão organizados em subdiretórios.

## Formato do cadastro de `students`:

Na sua primeira entrega, crie um novo arquivo em `students` com seu nome em formato slug. Por exemplo, `Tulio Faria` -> `tulio-faria.md`.
O template para o conteúdo é o seguinte:

```markdown
---
name: Tulio Faria
location: Pouso Alegre / MG / Brazil
url: https://tuliofaria.dev
email: tuliofaria[em]gmail.com
github: tuliofaria
linkedin: https://www.linkedin.com/in/tuliofaria/
---
```

## Formato do cadastro de cada projeto:

Para cada entrega de projeto, crie um arquivo com o slug de seu nome dentro da pasta do projeto. Por exemplo, se seu slug em students é `tulio-faria.md`, dentro da pasta de entrega do projeto (a mesma pasta que contém o readme.md com a descrição do projeto.), crie um arquivo com o mesmo nome. Usando como exemplo a entrega do aluno `Tulio Faria` do projeto 01 de Remix o arquivo seria criado em: `projects/remix/01/tulio-faria.md` com o seguinte conteúdo:

```
---
student: tulio-faria
title: Listagem da bolsa de valores
description: Este projeto lista ações da bolsa de valores.
repo: tuliofaria/remix-list-stocks
post: tuliofaria.dev/remix-listing-stocks
---

```

## Exemplo: o que será entregue?

A sua primeira entrega será composta por 2 arquivos. Por exemplo, se o aluno `Tulio Faria` está entregando o primeiro projeto de Remix, 2 arquivos serão criados:

- `students/tulio-faria.md`
- `projects/remix/01/tulio-faria.md`

As suas entregas subsequentes, contarão apenas com o arquivo do projeto:

- `projects/remix/02/tulio-faria.md`

# Como entregar?

- Clone este repositório para seu Github, crie os arquivos seguindo as instruções acima (fazendo commit e push em seu repositório clonado). Abra um pull-request do seu repositório para este repositório. Compartilhe o link do seu PR no Discord para que outro aluno faça o devido review.
