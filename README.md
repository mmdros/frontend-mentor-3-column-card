# Frontend Mentor - 3-column Preview Card Component

Esta é a minha solução para o desafio **3-column preview card
component** do Frontend Mentor.\
O objetivo do projeto é recriar três cards responsivos com layout
moderno, cores distintas e tipografia personalizada.

## 📋 Tabela de Conteúdos

-   [Visão Geral](#visão-geral)
    -   [O Desafio](#o-desafio)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [Meu Processo](#meu-processo)
    -   [Construído com](#construído-com)
    -   [O que aprendi](#o-que-aprendi)
    -   [Desenvolvimento contínuo](#desenvolvimento-contínuo)
    -   [Recursos úteis](#recursos-úteis)
-   [Autor](#autor)

## 📌 Visão Geral

### O Desafio

Os usuários devem conseguir:

-   Ver o layout ideal em cada tamanho de tela\
-   Visualizar estados de hover nos botões\
-   Navegar entre cards de forma legível e harmoniosa\
-   Acessar um design fiel ao modelo original do Frontend Mentor

### 📸 Screenshot

*(Adicione aqui o caminho da sua screenshot)*

    ./images/desktop.jpg
    ./images/mobile (1).png
    ./images/mobile (2).png

### 🔗 Links

-   **Solução:** https://your-solution-url.com\
-   **Site ao vivo:** https://your-live-site-url.com

## 🛠️ Meu Processo

### ✔️ Construído com

-   **HTML5 semântico**
-   **CSS3**
    -   Flexbox
    -   Variáveis CSS
    -   Google Fonts (Big Shoulders & Lexend Deca)
-   **Mobile-first**
-   **Media Query customizada (max-width: 900px)**

### 📚 O que aprendi

#### Variáveis de cor por componente

``` css
.card-1 {
  --accent-color: hsl(31, 77%, 52%);
}
```

#### Flexbox com alinhamento centralizado

``` css
main {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100vh;
}
```

#### Responsividade eficiente

``` css
@media screen and (max-width: 900px) {
  main {
    flex-direction: column;
    height: auto;
  }
}
```

#### Hover elegante

``` css
.card .button button:hover {
  background-color: transparent;
  color: #fff;
  border: 2px solid rgba(255,255,255,1);
}
```

## 🚀 Desenvolvimento contínuo

-   Animações suaves\
-   Versão em React\
-   CSS Grid\
-   Tema dark/light\
-   Melhor acessibilidade

## 📎 Recursos úteis

-   https://developer.mozilla.org/\
-   https://css-tricks.com/snippets/css/a-guide-to-flexbox/\
-   https://fonts.google.com/

## 👤 Autor

-   **Matheus Medeiros**
-   GitHub: https://github.com/mmdros
