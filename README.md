# Crônicas do Mar

O **Crônicas do Mar** é um espaço autoral dedicado à publicação de crônicas poéticas, ensaios reflexivos e ficção (ou releituras da vida real). O projeto combina a leveza e a segurança de um gerador de sites estáticos com uma arquitetura de frontend totalmente customizada para entregar uma experiência de leitura imersiva, minimalista e focada na privacidade.


## 🚀 Implementações

O projeto foi construído utilizando o **Publii CMS** como base estática, mas passou por um processo profundo de refatoração estrutural via JavaScript nativo (Vanilla JS) e CSS avançado para contornar as limitações do tema original:

*   **Motor de Busca Reativo Local:** Sistema de busca assíncrono que consome um índice estático (`feed.json`) via `fetch`. Entrega resultados instantâneos sem depender de bancos de dados ou APIs externas pesadas.
*   **Carrossel Editorial com Suporte a Gestos:** Slider de destaques desenvolvido do zero em Vanilla JS, contando com aceleração por hardware (`transform: translateX`) e suporte nativo a *swipe* em dispositivos móveis (`touchstart`/`touchend`).
*   **Injeção Dinâmica de Layout (Grid System):** Manipulação cirúrgica do DOM para reestruturar o feed nativo em um sistema de grid de duas colunas (Conteúdo Principal + Barra Lateral Stick) sem quebrar o ciclo de renderização do CMS.
*   **Privacidade Absoluta por Padrão:** Arquitetura livre de cookies de rastreamento. Conta com modo avançado de privacidade para embeds de vídeo (Vimeo e YouTube Enhanced Privacy) e telemetria leve processada exclusivamente na borda (Edge) via Cloudflare.
*   **SEO & Open Graph Customizados:** Metadados estruturados manualmente para garantir compartilhamentos otimizados em redes federadas e descentralizadas, como Mastodon e Bluesky.

---

## 🛠️ Tecnologias Utilizadas

*   **Core:** Publii CMS (Static Site Generator)
*   **Linguagens:** HTML5, CSS3 Avançado (Grid, Flexbox, Animações) e Vanilla JavaScript (ES6+)
*   **Hospedagem & CDN:** Cloudflare Pages (Deploy automatizado via Git e Analytics sem cookies)
*   **Assets:** Inkscape
*   **Ambiente de Testes:** Mozilla Firefox

---

## 🖋️ Autoria e Licença

*   **Autor:** Anthuan Sousa 
*   **Licença:** Conteúdo distribuído sob a licença [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.pt_BR).