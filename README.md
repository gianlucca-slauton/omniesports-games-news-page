# OmniEsports

Gianlucca Lauton <br>
Samuel Borborema <br>
Tiago Hiroshi 
 
2026

## 📌 Descrição do projeto

OmniEsports é um portal de e-sports desenvolvido com Bootstrap, reunindo em um só lugar notícias, lançamentos e a cobertura competitiva de 9 jogos (Valorant, Counter-Strike 2, League of Legends, Dota 2, Free Fire, Fortnite, Tekken 8, Street Fighter 6 e Rocket League).

## 🎮 Tema escolhido

Site sobre jogos / e-sports.

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3 (customizações próprias em `css/style.css`)
- Bootstrap 5.3.8 (via CDN)
- JavaScript (filtro de notícias e dropdown/navbar do Bootstrap)

## 📄 Páginas do projeto

| Página | Descrição |
| --- | --- |
| `index.html` | Página principal, com hero, últimas notícias e próximas partidas |
| `noticias.html` | Notícias de todos os jogos, com filtro por categoria |
| `lancamentos.html` | Lançamentos, jogos em pré-venda/beta e patch notes |
| `campeonatos.html` | Hub de campeonatos por categoria (FPS, MOBA, Battle Royale, Fighting, Esportes/Corrida) e calendário |
| `bootstrap.html` | Página explicativa sobre o Bootstrap (obrigatória pelo desafio) |
| `valorant.html`, `cs2.html`, `lol.html`, `dota2.html`, `freefire.html`, `fortnite.html`, `tekken.html`, `sf6.html`, `rocketleague.html` | Página individual de cada jogo, com partidas, resultados, classificação e notícias |

## 📂 Estrutura de pastas

```
omniesports/
│
├── index.html
├── noticias.html
├── lancamentos.html
├── campeonatos.html
├── bootstrap.html
├── valorant.html
├── cs2.html
├── lol.html
├── dota2.html
├── freefire.html
├── fortnite.html
├── tekken.html
├── sf6.html
├── rocketleague.html
│
├── css/
│   └── style.css
│
├── img/
│   ├── logo.svg
│   ├── thumb-valorant.svg
│   ├── thumb-cs2.svg
│   ├── thumb-lol.svg
│   ├── thumb-dota2.svg
│   ├── thumb-freefire.svg
│   ├── thumb-fortnite.svg
│   ├── thumb-tekken.svg
│   ├── thumb-sf6.svg
│   ├── thumb-rocketleague.svg
│   └── (demais imagens do projeto)
│
└── README.md
```

## 🔗 Links

- **Repositório GitHub:** _(adicionar link após o upload)_
- **Site publicado (Vercel):** _(adicionar link após o deploy)_

## ✍️ Sobre o desenvolvimento

O projeto utiliza o sistema de grid do Bootstrap (`container`, `row`, `col-*`) em todas as páginas, com componentes como Navbar, Dropdown, Card, Badge, Table e Buttons. A identidade visual (paleta escura + dourado + magenta) foi aplicada por cima do tema `data-bs-theme="dark"` do Bootstrap via variáveis CSS customizadas em `css/style.css`, e cada página de jogo recebe uma cor de destaque própria através do atributo `data-game` no `<body>`.
