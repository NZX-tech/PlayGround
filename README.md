# Marés de Auralis — Crônicas do Mar Vivo

Um protótipo de RPG de exploração e combate, em português, que roda diretamente no navegador. A primeira região jogável é a **Ilha do Farol**, no arquipélago de Lúmen.

## Executar

Requer Python 3. Na pasta do projeto, inicie um servidor HTTP:

```bash
python3 -m http.server 3002
```

Abra [http://localhost:3002](http://localhost:3002) no navegador. Também é possível usar qualquer servidor estático para servir `index.html`, `style.css` e `game.js` juntos. Não há etapa de build nem dependências de runtime.

## Como jogar

- **WASD** ou **setas**: mover-se.
- **Espaço** ou **1**: golpe leve.
- **2** ou **K**: lançar Brasa errante (custa vigor).
- **3**: Passo da maré (esquiva).
- **E**: conversar ou interagir quando estiver perto de alguém.
- **M**, **I**, **B**: abrir mapa, mochila e mercado.
- No celular, use o controle virtual e os botões de ação na tela.

Afaste três saqueadores da maré e retorne até Mira, a faroleira, para concluir a missão inicial. Derrotar inimigos concede experiência e conchas. O mapa mostra oito ilhas planejadas; novas rotas são desbloqueadas conforme a progressão. O estado do personagem e das missões é salvo no armazenamento local do navegador (`auralis-save`).

## Sistemas no protótipo

- Exploração em canvas, minimapa, inimigos, chefe, combate corpo a corpo e projéteis.
- Movimento, esquiva com breve invulnerabilidade, vida e vigor regeneráveis.
- Missão inicial, diálogo/interação com NPCs, experiência e níveis.
- Mapa de ilhas, inventário, poderes, treinamento e mercado.
- Recompensa diária e salvamento local.
- Interface responsiva com controles por toque.

As regiões além da Ilha do Farol, o modo cooperativo e parte das funcionalidades apresentadas na interface são planejados ou representados como progressão de protótipo, não conteúdo completo.

## Arquivos

- `index.html` — estrutura da interface.
- `style.css` — visual e layout responsivo.
- `game.js` — mundo, loop de jogo e sistemas.

<!-- omgithub:readme:start -->
## 🚀 Build, play, and remix with OMGithub

**Created using [OMGithub.com](https://go.ondev.store/).**

[![OMGithub](https://img.shields.io/badge/OMGithub-Open%20project-orange?style=for-the-badge)](https://go.ondev.store/NZX-tech/PlayGround)
[![GitHub](https://img.shields.io/badge/GitHub-Source-181717?logo=github&style=for-the-badge)](https://github.com/NZX-tech/PlayGround)

- 🎮 [Open the project](https://go.ondev.store/NZX-tech/PlayGround).
- ✨ [Remix this project](https://go.ondev.store/NZX-tech/PlayGround?remix=1).
- 💻 [Explore the source](https://github.com/NZX-tech/PlayGround).
- 🛠️ [Check build runs](https://github.com/NZX-tech/PlayGround/actions).
- 🐛 [Report an issue](https://github.com/NZX-tech/PlayGround/issues).
- 👤 [Explore the creator's projects](https://go.ondev.store/NZX-tech).
- 🌍 [Create with OMGithub](https://go.ondev.store/).
<!-- omgithub:readme:end -->
