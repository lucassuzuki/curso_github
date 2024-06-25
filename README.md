# Markdown

Este é um curso onde está sendo abordado o Markdown para deixarmos o nosso readme mais apresentavel.

## Hashtag 

O # em frente a frase define o <h1></h1> igual ao html simples, uma # -> h1, ## -> h2, assim por diante

## Negrito e Italico

Para deixarmos nosso texto em **negrito**, basta colocar ```**negrito**```
Para deixarmos nosso tezto em *italico*, basta colocar ```*italico*```

## Listas nao ordenadas e ordenadas

Para criar lista nao ordenadas, podemos fazer da seguinte forma, adicionando um asteristico e um espaço antes da palavra ```* aaaa```
* lista nao ordenada 1
* lista nao ordenada 2
* lista nao ordenada 3

Para criar uma lista ordenada, podemos fazer da seguinte forma, adicionando o numero e um ponto antes da palavra ```1. aaa```
1. lista ordenada 1
2. lista ordenada 2
3. lista ordenada 3

Para criar uma lista ordenada com sublistas, seguimos o exemplo abaixo:
1. lista ordenada 1
    1. subtopico ordenado 1
    2. subtopico ordenado 2

## Imagens em Markdown

Para inserir uma imagem no readme, devemos seguir a seguinte sintaxe: ```![Texto imagem](link imagem)```
A imagem pode estar no proprio repo, ou externo via link

![Logo Github](img/github-logo.webp)

## Links

Para inserir link no readme, devemos seguir a seguinte sintaxe: ```[Texto do link](link .)```

Para baixar o git, [Clique aqui](https://git-scm.com/downloads)

Podemos tambem, colocar o link em uma imagem, fazendo com a seguinte sintaxe: ```[![Texto imagem](link imagem)](link .)```


[![Foto](img/github-logo.webp)](https://github.com/lucassuzuki/curso_github)

## Código fonte

Para inserir o codigo fonte, devemos seguir a sintaxe: ``` ```"nome linguagem" "codigo" ``` ``` **Somente no GITHUB**

```python
    print("Hello World")
```

## Listas de Tarefas

Para fazer lista de tarefas, devemos seguir a seguinte sintaxe ``` - [ ] Para tarefas nao concluidas // - [X] Para tarefas concluidas ```

### A fazer

- [ ] Tela de login

### Feito

- [X] Tela de Cadastro