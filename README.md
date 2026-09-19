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

### Registrar Inicio e Fim do Projeto

* Inicio do projeto: 17/09/2026
* Termino do projeto: 

---

### Artes usadas de terceiros para produzir a logo do site no Canva

[![Canva](https://img.shields.io/badge/canva-blue?style=for-the-badge)](https://canva.link/i8e545czuxtb3ns)

* Desenho do menino: https://professoracarina.blogspot.com/2011/01/desenhos-para-colorir-tema-escolar.html
<img title='Desenho Menino Fazendo Tarefa' src='/images/desenho_menino.jpg' alt='Menino fazendo tarefa' width='320px' height='300'>

<br>

Imagens que me fizeram ter ideias para o relógio final:

* Relógio Final:
<img title='Relógio Final' src='' width='320px' height='300px'>

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
</details>

---
---