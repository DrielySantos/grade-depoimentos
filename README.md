<h1 align="center">Seção de grade de depoimentos</h1>

Esta é uma solução para o [desafio da seção de grade de depoimentos no Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). 
Os desafios do Frontend Mentor ajudam a melhorar habilidades de codificação através da construção de projetos realistas.

## Índice

- [Visão geral](#visão-geral)
  - [Desafio](#desafio)
  - [Screenshot](#screenshot)
- [Meu progresso](#meu-progresso)
  - [Construído com](#construído-com)
  - [O que eu aprendi](#o-que-eu-aprendi)
  - [Desenvolvimento contínuo](#desenvolvimento-contínuo)
- [Desenvolvedor](#desenvolvedor)


## Visão geral

### Desafio

Os usuários devem ser capazes de:

- Veja o layout ideal para o site dependendo do tamanho da tela do dispositivo.

### Screenshot

![](./design/desktop-design.jpg)


## Meu progresso

### Construído com:

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### O que eu aprendi

De inicio, fiz as ocupações de espaço criando uma tabela de 5 colunas e 3 linhas e fui atribuíndo seus espaços. Mas com algumas pesquisas, aprendi que tinha uma outra opção que é utilizando o auto-fill e span. 

```css
.container-grid{
  grid-template-columns: repeat(5, auto);
  grid-template-rows: repeat(3, auto);
}

.container-grid .comment_one{
   grid-area: 1 / 1 / 1 / 3;
}
```
Achei dessa forma mais eficiente, expandindo os espaços dos elementos que precisavam, sem ter que determinar os espaços de cada um individualmente.

```css
.container-grid {
  grid-template-columns: repeat(auto-fill, minmax(230px, 1fr));
}

.container-grid .comment_one{
  grid-column: span 2;
}
```
### Desenvolvimento contínuo

Pretendo utilizar mais do CSS Grid em futuros projetos para que assim eu possa aperfeiçoar, aprender técnicas e estar mais confortável para útiliza-lo.

## Desenvolvedor

- Frontend Mentor - [@DrielySantos](https://www.frontendmentor.io/profile/DrielySantos)
- LinkedIn - [Driely Santos](https://www.linkedin.com/in/driely-santos98/)


