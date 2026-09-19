# Projeto 1 (Fundamentos)

## Objetivo: Gerenciador de Tarefas

### O que é o projeto?

Um aplicativo web simples para criar, organizar e acompanhar tarefas, permitindo que o usuário registre suas atividades e controle quais já foram concluídas.

---
---

### Qual problema ele resolve?

Ajuda o usuário a organizar suas tarefas e compromissos, evitando que atividades sejam esquecidas e facilitando o acompanhamento do que ainda precisa ser feito e do que já foi concluído.

---
---

### Qual seria a ideia de funcionamento?

O usuário poderá adicionar uma tarefa, informando seu nome ou descrição. As tarefas serão exibidas em uma lista, onde será possível marcá-las como concluídas, editar ou excluir. Também será possível filtrar as tarefas para visualizar, por exemplo, apenas as pendentes ou concluídas.

Os dados serão armazenados no LocalStorage do navegador, permitindo que as tarefas continuem disponíveis mesmo depois de fechar ou atualizar a página.

* Criar tarefas
* Editar tarefas
* Excluir tarefas
* Marcar tarefa como concluída
* Filtrar tarefas
* Salvar dados no LocalStorage

---
---

### Tecnologias Utilizadas

* HTML
* CSS
* JavaScript
* DOM
* LocalStorage
* Git
* GitHub

---
---

### Passos seguidos durante o projeto

<details>
  <summary>Passo 1 - Esquema visual</summary>

  <br>

  [![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/design/nWFo6tjUOMONoEtUcKP4Pm/Projeto-1--Fundamentos----Gerenciador-de-Tarefas?node-id=0-1&t=bsf9F7YlXKjTSzj5-1)
  [![Canva](https://img.shields.io/badge/canva-blue?style=for-the-badge)](https://canva.link/i8e545czuxtb3ns)

  * (EV) Estrutura visual do site no Figma
  * (CL) Criação da Logo do Gerenciador de Tarefas pelo Canva
  
  <br>

  Histórico de atividade:
  * EV - Iniciada 18/09/2026
  * * Esquema principal do site definida:
  <img title='Esquema Site' src='' width='600px' height='300px'>
  
  * * Fontes
  * * * Header: Open Sans;
  * * * Body
  * * * * Titulos: determinar;
  * * * * Subtitulos: determinar;
  * * * * Paragrafos: determinar;
  * * * * Footer: determinar.
  * EV - Finalizada
  
  <br>

  * CL - Iniciada 18/09/2026:
  * * Fiz uma logo que faz referência a "Concluir Tarefas no Prazo"
  * CL - Finalizada
</details>

<details>
  <summary>Passo 2 - Tal coisa</summary>

  <br>

  Reconstruir o esquema do figma para html e css.
</details>
  
<details>
  <summary>Passo 3 - Tal coisa</summary>

  <br>

  Adicionar as funcionalidades.
</details>

---
---

### Registrar Inicio e Fim do Projeto

* Inicio do projeto: 17/09/2026
* Termino do projeto: 

---
---

### Artes usadas de terceiros para produzir a logo do site no Canva

[![Canva](https://img.shields.io/badge/canva-blue?style=for-the-badge)](https://canva.link/i8e545czuxtb3ns)

* Desenho do menino: https://professoracarina.blogspot.com/2011/01/desenhos-para-colorir-tema-escolar.html
<img title='Desenho Menino Fazendo Tarefa' src='/images/desenho_menino.jpg' alt='Menino fazendo tarefa' width='320px' height='300'>

<br>


* Relógio Final:
<img title='Relógio Final' src='' width='320px' height='300px'>

Imagens que me fizeram ter ideias para o relógio final:

* * Desenho do relógio: https://www.flaticon.com/br/icone-gratis/relogio-de-parede_1085157 
<br>
<img title='Desenho Relógio' src='/images/desenho_relogio.png' width='320px' height='300px' alt='Relógio'>

* * Desenho de Conclusão: https://www.flaticon.com/br/icone-gratis/conclusao_9757455 <br>
<img title='Desenho Conclusão' src='/images/desenho_conclusao.png' width='320px' height='300px' alt='Circulo colorido com quadrado centralizado nele e certinho no meio do quadrado'>

---
---

### Fontes de Estudo:

<details>
  <summary>Duvidas sobre Markdown</summary>

  * Como colocar imagens: https://www.digitalocean.com/community/tutorials/markdown-markdown-images
  
  * * Usando a tag HTML img: 
  ```html
  <img title='Um titulo' src='o caminho ou link da imagem' alt='descrição da imagem' width='se quiser mexer na largura da imagem' height='se quiser mexer na altura da imagem'>
  ```
  
  * * Adicionando com código md de fato:
  ```md
  ![alt](link-da-imagem-ou-caminho)

  Exemplo:
  ![Gato](https://i.pinimg.com/236x/5b/ba/00/5bba000e97f2ae347e6949b412bdb5a4.jpg)
  ou se tiver baixada
  ![Gato](/images/gato.jpg)
  ```

  * * Colocando link em imagens no formato md:
  ```md
  [![alt](link-da-imagem-ou-caminho)](link-para-onde-ir)

  Exemplo:
  [![Gato](https://i.pinimg.com/236x/5b/ba/00/5bba000e97f2ae347e6949b412bdb5a4.jpg)](https://www.youtube.com/watch?v=dQw4w9WgXcQ&themeRefresh=1)
  ```

  ---

  * Como fazer lista alternante: https://gist.github.com/scmx/eca72d44afee0113ceb0349dd54a84a2 
  ```html
  <details>
    <summary>Aqui é o titulo da lista</sumarry>
    Quando aberta aparecera o conteudo aqui dentro, sendo possivel usar os códigos md e html normalmente.
  </details>
  ```
  
  ---
  
  * Como usar Badges: https://ileriayo.github.io/markdown-badges/
  
  * * Possui varias badges prontas de varias ferramentas para utilizar.
  
  * * Pegar uma badge pronta do Linkedin e levar para o meu por exemplo:
  ```md
  [![Linkedin](https://img.shields.io/badge/LinkedIn-0077b5?logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0nMjU2JyBoZWlnaHQ9JzI1NicgeG1sbnM9J2h0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnJyBwcmVzZXJ2ZUFzcGVjdFJhdGlvPSd4TWlkWU1pZCcgdmlld0JveD0nMCAwIDI1NiAyNTYnPjxwYXRoIGQ9J00yMTguMTIzIDIxOC4xMjdoLTM3LjkzMXYtNTkuNDAzYzAtMTQuMTY1LS4yNTMtMzIuNC0xOS43MjgtMzIuNC0xOS43NTYgMC0yMi43NzkgMTUuNDM0LTIyLjc3OSAzMS4zNjl2NjAuNDNoLTM3LjkzVjk1Ljk2N2gzNi40MTN2MTYuNjk0aC41MWEzOS45MDcgMzkuOTA3IDAgMCAxIDM1LjkyOC0xOS43MzNjMzguNDQ1IDAgNDUuNTMzIDI1LjI4OCA0NS41MzMgNTguMTg2bC0uMDE2IDY3LjAxM1pNNTYuOTU1IDc5LjI3Yy0xMi4xNTcuMDAyLTIyLjAxNC05Ljg1Mi0yMi4wMTYtMjIuMDA5LS4wMDItMTIuMTU3IDkuODUxLTIyLjAxNCAyMi4wMDgtMjIuMDE2IDEyLjE1Ny0uMDAzIDIyLjAxNCA5Ljg1MSAyMi4wMTYgMjIuMDA4QTIyLjAxMyAyMi4wMTMgMCAwIDEgNTYuOTU1IDc5LjI3bTE4Ljk2NiAxMzguODU4SDM3Ljk1Vjk1Ljk2N2gzNy45N3YxMjIuMTZaTTIzNy4wMzMuMDE4SDE4Ljg5QzguNTgtLjA5OC4xMjUgOC4xNjEtLjAwMSAxOC40NzF2MjE5LjA1M2MuMTIyIDEwLjMxNSA4LjU3NiAxOC41ODIgMTguODkgMTguNDc0aDIxOC4xNDRjMTAuMzM2LjEyOCAxOC44MjMtOC4xMzkgMTguOTY2LTE4LjQ3NFYxOC40NTRjLS4xNDctMTAuMzMtOC42MzUtMTguNTg4LTE4Ljk2Ni0xOC40NTMnIGZpbGw9JyNmZmYnLz48L3N2Zz4K)](www.linkedin.com/in/hectorportes)

  Usamos a badge pronta do linkedin como uma imagem e linkamos meu linkedin nela.
  ```
  
  ---
  
  * Shild.io Badges: https://shields.io/badges
  * * Possui varias badges prontas de diferentes ferramentas e ensina como usar.
  
  ---
  
  * Como criar a própria Badge: https://shields.io/docs/logos
  
  * * Para criar Badges:
  ``` md
  ![alt](https://img.shields.io/badge/oquequerescrito-cor?style=for-the-badge)
  
  oquequerescrito-cor: é o que vai aparecer escrito na badge mais a cor de funco da badge que quer;

  style=for-the-badge: define tamanho e largura pradonizada de badges, se não colocar isso vai ficar pequena.
  ```

  ---

  * Como realçar um código: https://www-codecademy-com.translate.goog/resources/docs/markdown/code-blocks?_x_tr_sl=en&_x_tr_tl=pt&_x_tr_hl=pt&_x_tr_pto=tc&_x_tr_hist=true
  
  ```
  Abrindo ``` escrevendo o que quer e fechando novamente com ```. Se colocar ```js por exemplo tudo que estiver dentro será interpretado como um código javascript, e assim por diante para outras linguagens.
  ```
</details>
 
---

<details>
  <summary>Duvidas sobre quais fontes de texto utilizar no site</summary>

  * https://www.flaticon.com/br/icone-gratis/conclusao_9757455
  
  ```
  Usei para ter ideias de fonts para usar no site.
  ```
</details>

---

<details>
  <summary>Duvidas sobre localstorage e storage</summary>

  * Localstorage: https://developer.mozilla.org/pt-BR/docs/Web/API/Window/localStorage
  * Storage: https://developer.mozilla.org/pt-BR/docs/Web/API/Storage 
</details>

---

<details>
  <summary>Duvidas sobre CSS</summary>
  
  * https://developer.mozilla.org/pt-BR/docs/Web/CSS
</details>

---

<details>
  <summary>Duvidas sobre HTML</summary>
  
  * https://developer.mozilla.org/pt-BR/docs/Web/HTML
</details>

---

<details>
  <summary>Duvidas sobre SVG</summary>

  * Playlist do canal Willian Justen sobre SVGs: https://www.youtube.com/watch?v=VNTmT1qMgp0&list=PLlAbYrWSYTiOufRJOeP73o4GR9N1afQdP
  * Canal Willian Justen: https://www.youtube.com/@WillianJustenCursos
  
  #### O que é SVG? 
  Scalable Vector Graphics (SVG). É uma imagem vetorial no formato XML que suporta interatividade e animações.
  * Uma imagem vetorial é formada por coordenadas de pontos x e y que se ligam formando um desenho, por ela ser formada por esses vetores ela redimensiona de acordo com seu tamanho sem perder qualidade, o vetor é adimensional.
  * O formato XML é bem antigo com tags similares ao HTML.
  * Interatividade como arrastar um ponto ou fazer um houver em cima da imagem. Animações como fazer a imagem do relógio rodar o ponteiro.

  <br>
  
  ---

  #### Por que usar SVG?
  * Adaptavel a qualquer dispositivo sem perder a qualidade independente de tamanho;
  * Pode trabalhar com icones multicor e unicor
  * É interativo e estilizavel via css
  * Além de responsivo é adaptativo (em diferentes resoluções ele pode mudar seu visual)
  * Permite ter animações avançadas como line drawing (linha que vai se desenhando com uma imagem que vai aparecendo - atras com fading)
  * Muito bom para fazer gráficos de dados
  * Pode-se usar efeitos e filtros nas imagens
  * Ótimo suporte (até internet explorer aguenta)
  * Pode ser minificado (GZIP)
  * Boa acessibilidade
  * Possui árvore no DOM

  <br>
  
  ---

  #### Quando usar?
  Quando forem icones/fotos mais simples com poucos detalhes/efeitos. Se forem imagens muito complexas em questões de efeito/detalhes usar png ou outros formatos.

  <br>
  
  ---

  #### Como criar SVG?
  Desenhando:
  * Illustrator (windows e mac)
  * Sketch (mac)
  * Inkscape (windows, linux e mac)
  
  <br>

  Na mão
  * Vim
  * VSCode
  * Qualquer editor de texto

  <br>
  
  ---

  #### Onde baixar SVGs prontos?
  Bancos de imagem:
  * Shutter stock
  * Vecteezy
  * SVGCuts
  
  <br>

  Ícones
  * Icomoon
  * Iconmonstr
  * Material Desing Icon
  * Iconic
  * Flation
  * The Noun Project
  
  <br>

  Patterns
  * Plain Pattern
  * Trianglify
  * SVGeneration
  * Pattern bold
  * Gerstnerizer
  
  <br>
  
  ---

  #### Formas de utilizações e suas vantagens e desvantagens:
  
  Usando como imagem

  ```html
  <img src='/images/relogio.svg' alt='Relogio'> 

  ```

  * Vantagens:
  * * Pode ser cacheadas (só precisa fazer requisição uma vez no site)
  
  <br>
  
  * Desvantagens:
  * * Sem interação de CSS
  * * Sem edição no DOM
  * * Animações só funcionam se estiverem dentro do SVG
  
  <br>

  __ __ __ __ __ __ __ __ __ __ __ __ || __ __ __ __ __ __ __ __ __ __ __ __

  <br>

  Usando como background-image

  ```css
  .icon {
    display: inline-block;
    width: 300px;
    height: 300px;
  }

  .icon-relogio {
    background-image: url(/images/relogio.svg);
  }

  Exemplo de conjunto de classes
  .icon-ondas {
    background-image: url(/images/ondas.svg)
  }
  ```
  ```html
  <i class='icon icon-relogio'></i>

  Exemplo de conjunto de classes
  <i class='icon icon-ondas'>
  ```

  * Vantagens:
  * * Pode ser cacheadas (só precisa fazer requisição uma vez no site)
  * * Pode criar um conjunto de classes pra definir os icones/imagens (padroniza estilização de varios icones/imagens)
  
  <br>
  
  * Desvantagens:
  * * Sem interação de CSS
  * * Sem edição no DOM
  * * Animações só funcionam se estiverem dentro do SVG
  
  <br>

  __ __ __ __ __ __ __ __ __ __ __ __ || __ __ __ __ __ __ __ __ __ __ __ __

  <br>

  Usando como iframe/object/embed

  ```html
  <iframe src='/images/relogio.svg' frameborder='0'></iframe>

  <object data='/images/relogio.svg' type=''></object>

  <embed src='/images/relogio.svg' type=''>
  ```

  * Vantagens:
  * * Nenhuma
  
  <br>
  
  * Desvantagens:
  * * Reage diferente em cada browser
  * * Bastante lento
  * * Comportamentos diferentes dependendo do Browser
  * * Sem permissão de muitas edições
  
  <br>

  __ __ __ __ __ __ __ __ __ __ __ __ || __ __ __ __ __ __ __ __ __ __ __ __

  <br>

  Usando com data-uri
  ```css
  .icon-ondas {
    height: 100px;
    width: 100px;
    background-image: url(data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMTI4MC4wMDAwMDBwdCIgaGVpZ2h0PSI2NDAuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAxMjgwLjAwMDAwMCA2NDAuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+CjxtZXRhZGF0YT4KQ3JlYXRlZCBieSBwb3RyYWNlIDEuMTUsIHdyaXR0ZW4gYnkgUGV0ZXIgU2VsaW5nZXIgMjAwMS0yMDE3CjwvbWV0YWRhdGE+CjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuMDAwMDAwLDY0MC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiMwMDAwMDAiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0yMjU1IDU0NTUgYy0zNDkgLTU0IC01NzUgLTE5NCAtNjg3IC00MjMgLTQyIC04NiAtNDMgLTg5IC00MyAtMTkyCjAgLTkzIDMgLTExMCAyNSAtMTUwIDI1IC00MyA4MCAtOTAgMTA3IC05MCAxMCAwIDExIDUgMyAxOSAtMzAgNTggMTkgMTE3IDEyNQoxNTEgMjczIDg5IDU4MiAtOTUgNzQ1IC00NDMgMTkzIC00MTIgMTg0IC05MDggLTI2IC0xNDAxIC0yNDUgLTU3NCAtNzkxCi0xMTI4IC0xNTI5IC0xNTU0IC0yMzUgLTEzNSAtNjIwIC0zMTMgLTg3MyAtNDAyIC01MSAtMTggLTkxIC0zNCAtOTAgLTM1IDIKLTEgODI2IDEgMTgzMyA0IDEwMDcgNCAxODMyIDQgMTgzNSAxIDMgLTMgNzkwIC0zIDE3NTAgMCA5NjAgMyAxNzQ3IDIgMTc1MAotMSAzIC0zIDg5NiAtMiAxOTg1IDIgMTA4OSA0IDIzNDEgOCAyNzgyIDggNzU0IDEgODAyIDIgODA3IDE5IDMgOSAxMyA2MCAyMwoxMTIgMjEgMTE5IDI0IDQ1NyA0IDYxMCAtMTUyIDExOTggLTk4MSAyNjYyIC0xODk3IDMzNTEgLTI4MiAyMTIgLTU3MSAzNDcKLTg1NCAzOTkgLTE0NyAyOCAtNDE1IDM3IC01NjAgMjEgLTM2NCAtNDMgLTYxNSAtMTkwIC03MzIgLTQyOCAtNDIgLTg3IC00MwotOTAgLTQzIC0xOTMgMCAtOTMgMyAtMTEwIDI1IC0xNTAgMjUgLTQzIDgwIC05MCAxMDcgLTkwIDEwIDAgMTEgNSAzIDE5IC0zMAo1NyAxOCAxMTUgMTI1IDE1MSAyODggOTggNjE4IC0xMjAgNzc1IC01MTMgOTUgLTIzOCAxMjkgLTQ4NyAxMDAgLTc0MiAtNTAKLTQzOCAtMjQ3IC04NjUgLTU3NiAtMTI0OSAtNTggLTY5IC02OSAtNzcgLTc1IC02MCAtNCAxMCAtMjYgODEgLTQ5IDE1OCAtMjU1Cjg2NyAtODA4IDE3OTcgLTE0MjEgMjM5MSAtNTE3IDUwMSAtOTc4IDcxNSAtMTUzOSA3MTUgLTM2NiAwIC02MzcgLTg5IC04MTYKLTI2NyAtMTg1IC0xODQgLTIyNyAtNDUwIC05MCAtNTcwIDUwIC00NSA2NSAtNDMgNTkgNiAtNyA1MSA2IDcyIDY1IDEwNCA3NQo0MSAxNTcgNTYgMjQ1IDQ3IDE0NSAtMTcgMjU2IC03MiAzNjggLTE4NCAyMDYgLTIwNCAzMzIgLTU0OCAzMzIgLTkwMSAtMQotNTQyIC0yNDMgLTEwODcgLTY5MCAtMTU1NyBsLTkzIC05NiAtMTAgNDEgYy00MiAxNjMgLTg4IDMyMSAtMTI3IDQzNyAtMjc2CjgxNCAtNzY2IDE2MjIgLTEzMjggMjE4NSAtNDAyIDQwNCAtODE3IDY0OSAtMTIyNSA3MjYgLTE0OSAyNyAtNDcwIDM1IC02MDUKMTR6Ii8+CjwvZz4KPC9zdmc+Cg==)
  }
  ```
  ```html
  Usando como imagem: no lugar da src vai passar um código data com base64 de encode
  <img src='data:image/svg+xml;base64,PD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI/Pgo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDIwMDEwOTA0Ly9FTiIKICJodHRwOi8vd3d3LnczLm9yZy9UUi8yMDAxL1JFQy1TVkctMjAwMTA5MDQvRFREL3N2ZzEwLmR0ZCI+CjxzdmcgdmVyc2lvbj0iMS4wIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciCiB3aWR0aD0iMTI4MC4wMDAwMDBwdCIgaGVpZ2h0PSI2NDAuMDAwMDAwcHQiIHZpZXdCb3g9IjAgMCAxMjgwLjAwMDAwMCA2NDAuMDAwMDAwIgogcHJlc2VydmVBc3BlY3RSYXRpbz0ieE1pZFlNaWQgbWVldCI+CjxtZXRhZGF0YT4KQ3JlYXRlZCBieSBwb3RyYWNlIDEuMTUsIHdyaXR0ZW4gYnkgUGV0ZXIgU2VsaW5nZXIgMjAwMS0yMDE3CjwvbWV0YWRhdGE+CjxnIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAuMDAwMDAwLDY0MC4wMDAwMDApIHNjYWxlKDAuMTAwMDAwLC0wLjEwMDAwMCkiCmZpbGw9IiMwMDAwMDAiIHN0cm9rZT0ibm9uZSI+CjxwYXRoIGQ9Ik0yMjU1IDU0NTUgYy0zNDkgLTU0IC01NzUgLTE5NCAtNjg3IC00MjMgLTQyIC04NiAtNDMgLTg5IC00MyAtMTkyCjAgLTkzIDMgLTExMCAyNSAtMTUwIDI1IC00MyA4MCAtOTAgMTA3IC05MCAxMCAwIDExIDUgMyAxOSAtMzAgNTggMTkgMTE3IDEyNQoxNTEgMjczIDg5IDU4MiAtOTUgNzQ1IC00NDMgMTkzIC00MTIgMTg0IC05MDggLTI2IC0xNDAxIC0yNDUgLTU3NCAtNzkxCi0xMTI4IC0xNTI5IC0xNTU0IC0yMzUgLTEzNSAtNjIwIC0zMTMgLTg3MyAtNDAyIC01MSAtMTggLTkxIC0zNCAtOTAgLTM1IDIKLTEgODI2IDEgMTgzMyA0IDEwMDcgNCAxODMyIDQgMTgzNSAxIDMgLTMgNzkwIC0zIDE3NTAgMCA5NjAgMyAxNzQ3IDIgMTc1MAotMSAzIC0zIDg5NiAtMiAxOTg1IDIgMTA4OSA0IDIzNDEgOCAyNzgyIDggNzU0IDEgODAyIDIgODA3IDE5IDMgOSAxMyA2MCAyMwoxMTIgMjEgMTE5IDI0IDQ1NyA0IDYxMCAtMTUyIDExOTggLTk4MSAyNjYyIC0xODk3IDMzNTEgLTI4MiAyMTIgLTU3MSAzNDcKLTg1NCAzOTkgLTE0NyAyOCAtNDE1IDM3IC01NjAgMjEgLTM2NCAtNDMgLTYxNSAtMTkwIC03MzIgLTQyOCAtNDIgLTg3IC00MwotOTAgLTQzIC0xOTMgMCAtOTMgMyAtMTEwIDI1IC0xNTAgMjUgLTQzIDgwIC05MCAxMDcgLTkwIDEwIDAgMTEgNSAzIDE5IC0zMAo1NyAxOCAxMTUgMTI1IDE1MSAyODggOTggNjE4IC0xMjAgNzc1IC01MTMgOTUgLTIzOCAxMjkgLTQ4NyAxMDAgLTc0MiAtNTAKLTQzOCAtMjQ3IC04NjUgLTU3NiAtMTI0OSAtNTggLTY5IC02OSAtNzcgLTc1IC02MCAtNCAxMCAtMjYgODEgLTQ5IDE1OCAtMjU1Cjg2NyAtODA4IDE3OTcgLTE0MjEgMjM5MSAtNTE3IDUwMSAtOTc4IDcxNSAtMTUzOSA3MTUgLTM2NiAwIC02MzcgLTg5IC04MTYKLTI2NyAtMTg1IC0xODQgLTIyNyAtNDUwIC05MCAtNTcwIDUwIC00NSA2NSAtNDMgNTkgNiAtNyA1MSA2IDcyIDY1IDEwNCA3NQo0MSAxNTcgNTYgMjQ1IDQ3IDE0NSAtMTcgMjU2IC03MiAzNjggLTE4NCAyMDYgLTIwNCAzMzIgLTU0OCAzMzIgLTkwMSAtMQotNTQyIC0yNDMgLTEwODcgLTY5MCAtMTU1NyBsLTkzIC05NiAtMTAgNDEgYy00MiAxNjMgLTg4IDMyMSAtMTI3IDQzNyAtMjc2CjgxNCAtNzY2IDE2MjIgLTEzMjggMjE4NSAtNDAyIDQwNCAtODE3IDY0OSAtMTIyNSA3MjYgLTE0OSAyNyAtNDcwIDM1IC02MDUKMTR6Ii8+CjwvZz4KPC9zdmc+Cg=='>

  Usando como background-image:
  <i class='icon-ondas'></i>
  ```
  * Vantagens:
  * * Nenhuma
  
  <br>
  
  * Desvantagens:
  * * Não são cacheadas (pagina faz requesição sempre que recarrega)
  * * Sem interação de CSS
  * * Sem edição no DOM
  * * O tamanho pode ser maior que o normal
  
  <br>

  __ __ __ __ __ __ __ __ __ __ __ __ || __ __ __ __ __ __ __ __ __ __ __ __

  <br>

  Usando Inline

  ```html
  <svg version="1.0" xmlns="http://www.w3.org/2000/svg"
  width="1127.000000pt" height="1280.000000pt" viewBox="0 0 1127.000000 1280.000000"
  preserveAspectRatio="xMidYMid meet">
  <metadata>
  Created by potrace 1.15, written by Peter Selinger 2001-2017
  </metadata>
  <g transform="translate(0.000000,1280.000000) scale(0.100000,-0.100000)"
  fill="#000000" stroke="none">
  <path d="M3280 12789 c-330 -38 -748 -188 -1205 -431 -932 -496 -1515 -1035
  -1619 -1495 -20 -89 -21 -211 -2 -283 12 -44 401 -1059 410 -1067 1 -2 49 52
  107 120 210 246 524 552 794 773 760 622 1684 1060 2645 1254 107 22 219 42
  248 46 28 4 52 9 52 12 0 2 -161 205 -357 450 -393 489 -418 515 -565 572
  -137 53 -317 71 -508 49z"/>
  <path d="M7646 12785 c-112 -19 -209 -57 -291 -113 -63 -43 -107 -94 -432
  -497 -199 -248 -363 -453 -363 -456 0 -4 24 -9 53 -13 28 -4 131 -23 227 -42
  877 -174 1708 -543 2440 -1082 347 -256 743 -625 1019 -949 58 -68 106 -122
  107 -120 9 8 398 1023 410 1067 19 72 18 194 -2 283 -79 349 -435 747 -1014
  1134 -430 288 -926 543 -1310 675 -108 36 -289 83 -405 103 -127 23 -341 28
  -439 10z"/>
  <path d="M5245 11259 c-845 -58 -1698 -320 -2430 -747 -1482 -864 -2493 -2343
  -2749 -4022 -49 -324 -60 -480 -60 -855 0 -376 11 -536 60 -855 215 -1406 962
  -2682 2089 -3571 765 -604 1669 -997 2625 -1143 322 -49 480 -60 855 -60 376
  0 534 11 855 60 1406 215 2682 961 3571 2089 604 765 996 1666 1143 2625 49
  319 60 479 60 855 0 375 -11 531 -60 855 -214 1401 -956 2674 -2079 3566 -891
  707 -1980 1127 -3123 1204 -176 11 -580 11 -757 -1z m790 -774 c970 -83 1848
  -429 2610 -1029 339 -266 674 -616 932 -971 775 -1069 1079 -2400 847 -3710
  -188 -1062 -750 -2059 -1564 -2779 -350 -309 -689 -534 -1115 -742 -1321 -644
  -2893 -645 -4213 -4 -101 49 -225 113 -275 141 -1078 612 -1877 1589 -2256
  2761 -249 770 -298 1623 -140 2423 121 615 349 1172 703 1724 259 403 664 845
  1061 1157 756 595 1637 944 2595 1029 202 18 610 18 815 0z"/>
  <path d="M5508 9711 c-108 -43 -191 -122 -230 -219 l-23 -57 -3 -1707 -2
  -1708 -1713 -2 -1712 -3 -66 -32 c-79 -39 -150 -111 -187 -191 -24 -50 -27
  -69 -27 -157 0 -87 3 -107 26 -156 50 -106 143 -185 254 -214 52 -13 275 -15
  1955 -15 1549 0 1904 3 1945 14 119 31 206 103 258 214 l32 67 0 1945 0 1945
  -23 57 c-33 81 -108 160 -190 200 -58 29 -78 33 -157 36 -69 1 -101 -2 -137
  -17z"/>
  </g>
  </svg>
  ```

  * Vantagens:
  * * Permite edição no DOM
  * * Animações e Interações de CSS
  * * Sem requests HTTP adicionais
  
  <br>
  
  * Desvantagens:
  * * Imagens não podem ser cacheadas (pagina faz requesição sempre que recarrega)
  
  <br>

  __ __ __ __ __ __ __ __ __ __ __ __ || __ __ __ __ __ __ __ __ __ __ __ __

  <br>

  Resumo
  * Trabalhar com animações, interatividade e criativas -> inline
  * Imagens estaticas mas que precisam se adequar ao tamanho sem perder qualidade -> image
  * Se for reutilizar a mesma configuração para varios icones/imagens -> background-image
  
  <br>

  ---

  #### Plano Cartesiano

  <img title='Plano Cartesiano' src='/images/plano_cartesiano.png' alt='Plano Cartesiano' width='320px' height='300px'>

  O que precisa saber?
  * Como funciona o eixo x e y
  * * Eixo x é o eixo horizontal, que define a largura e distância dos elementos. Exemplo ponto A, ele está antes do ponto 0 do eixo x, então ele é negativo, está na posição -5 do eixo x.
  * * Eixo y é o eixo vertical, que define a altura do elemento. Exemplo ponto A, ele está acima do ponto 0 do eixo y, então é positivo, está na posição 3 do eixo y.
  * * * Ponto A está na posição (x,y)==(-5,3).
  * * * Ponto B está na posição (x,y)==(6,5).
  * * * Ponto C está na posição (4.5,-3,5).
  * * * Ponto D está na posição (0,0) -> Origem.
  * * Processos de Translação: mover no eixo x ou no eixo y.
  

</details>

---
---