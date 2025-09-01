#senai-versoes-colaboracoes

Readme de Exemplo

---

| Markdown - tags:

| Títulos:
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6

---

| Ênfase

*itálico* ou _itálico_

**negrito** ou __negrito__

**_negrito+itálico_**

~~tachado~~

---

| Listas - ordenadas:

1. Item 01
2. Item 02
3. Item 03

| Listas - não ordenadas:

* Asterisco
- Menos
+ Mais

---

| Link:

[Google](https://www.google.com)

---

| Tabelas:

| Tables    | Are       | Cool |
| ---       |:--:       | ----:|
| col 3 is  | right     | $1600|
| col 2 is  | centered  |  $12 |
| zebra     | are       |   $1 |

---

| Imagens:

<img src="https://portalead.sp.senai.br/Img/logo-senai2.png" />

<img src="https://www.gstatic.com/marketing-cms/assets/images/c5/3a/200414104c669203c62270f7884f/google-wordmarks-2x.webp=n-w100-h32-fcrop64=1,00000000ffffffff-rw" />

---

| Emojis:

:grinning:
:wave:
:eye:
* dog :dog:
* octocat :octocat:
* unicorn :unicorn:

---

| Blocos de código:

```
function test() {
    console.log("notice the blank line before this function?");
}
```


````
```
Look! You can see my backticks.
```
````


```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

| Estrutura README - "documentação técnica":

# Projeto Exemplo
Repositório criado com o objetivo de compartilhar
conteúdo sobre orientação a objetos.
### :rocket: Descrição 
"A programação orientada a objetos..."
---
## 🧑‍💻 Tecnologias Utilizadas
Esse projeto foi criado utilizado as tecnologias:
#### Back-End
- [C#](https://docs.microsoft.com/pt-br/dotnet/csharp/)
- [.NET](https://dotnet.microsoft.com/download)
### Editor
- [Visual Studio Code](https://code.visualstudio.com/)
---
## 📦 Como rodar o projeto
Clone o projeto com o comando abaixo:
```bash
    #Clone o repositório
    > git clone https://github.com/[usuario]/[nome-projeto].git

    #Entre no diretório
    > cd [nome-projeto]
    
    # Execute no projeto
    > dotnet run
```
---
## 🔮 Funcionalidades Futuras
- [x] A
- [ ] B
- [ ] C
---