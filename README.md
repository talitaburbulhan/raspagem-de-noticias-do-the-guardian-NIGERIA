# Gerar um arquivo .CSV com os títulos das matérias publicadas no The Guardian-Nigéria com seus respectivos links é o propósito desse programa

Esse repositório contém um código para raspagem de informações do site do jornal The Guardian que realiza a cobertura de notícias sobre a Nigéria: 

🌐https://guardian.ng/category/news/nigeria/

A raspagem foi desenvolvida como trabalho final da disciplina de Pensamento Computacional, ministrada pelo programador Álvaro Justen (https://github.com/turicas), no Master de Jonalismo de Dados, Automação e Data Storytelling, do INSPER (🔎Saiba mais: https://www.insper.edu.br/pos-graduacao/master-em-jornalismo-de-dados-automacao-e-data-storytelling/).

https://user-images.githubusercontent.com/89229665/136798066-b7d2e2c7-9112-46b7-a139-3d45f42f2e5d.mp4

👆🏼 O vídeo ilustra para qual layout do site o código de raspagem foi criado. Isso é importante de ser documentado, porque se o site passar por mudanças de design, o código em questão ficará comprometido. Essa situação, de fato, aconteceu comigo. A primeira versão do código foi feita em 5 de outubro de 2021, mas, no dia seguinte, a estrutura do site estava diferente, o que demandou a criação de um novo programa.

## ⚙ Como funciona o programa?

O programa requer a instalação das bibliotecas requests e csv. Ele funciona extraindo informações de um arquivo JSON, gerado toda vez que uma pessoa clica no botão LOAD MORE do site https://guardian.ng/category/news/nigeria/. Em um primeiro momento, há uma restrição na quantidade de dados extraídos (12 registros). Para aumentar o escopo, foi necessário alterar a URL do JSON, mais especificamente, mexendo nos parâmetro OFFSET e PER_PAGE. 

![20211011_print-do-arquivo-JSON_editado](https://user-images.githubusercontent.com/89229665/136817996-a9eac86e-356b-4404-a83e-4aa18eabcdc8.png)


## ✔ Por que esse projeto é útil?

Em âmbito pessoal, esse projeto foi fundamental para colocar em prática os ensimentos da disciplina de Pensamento Computacional que teve como objetivo passar conceitos básicos de programação. Para o público em geral, o programa pode ser útil a quem desejar ter um repositórios de notícias, e em trabalhos acadêmicos pode contribuir no desenvolvimento de pesquisas diversas, como por exemplo, uma análise da cobertura midiática da Nigéria, por um veículo ocidental. 

## 🗂 Como o projeto está organizado?

Esse é um repositório bem simples de ser navegado. Ele possui a presente página (README.md) com explicações sobre o projeto, a página da licença escolhida para o compartilhamento do código, e o código do programa, que foi copiado do Google Colab.  

## 🤔 Há algo mais que eu precise saber?
Apesar das melhorias que podem e devem ser feitas, a princípio, esse programa não passará por novas modificações, porque a finalidade dele se cumpriu: demonstrar os conhecimentos obtidos ao longo da disciplina de Pensamento Computacional. Mas fique à vontade para sugerir, opinar, palpitar sobre o que achar que for pertinente para a melhoria do programa.  
