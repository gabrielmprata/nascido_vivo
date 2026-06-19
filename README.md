# Como os Brasileiros Chegam ao Mundo · SINASC 2023

Página estática construída para o GitHub Pages, explorando dados do **SINASC** (Sistema de Informações sobre Nascidos Vivos) de 2023.

https://gabrielmprata.github.io/nascido_vivo/

## 🛠️ Tecnologias

### Estrutura
- **HTML5** puro, em um único arquivo (`index.html`) — sem build, sem framework de componentes. Ideal pra GitHub Pages porque pode ser publicado direto.

### Estilo
- **CSS puro** (sem Tailwind/Bootstrap), com variáveis CSS (`:root`) definindo uma paleta de design tokens (rose, teal, amber, ink, mist) — abordagem de "design system" simples.
- Fontes do **Google Fonts**: **Playfair Display** (serifada, para títulos), **Inter** (sans-serif, para texto) e **JetBrains Mono** (monoespaçada, para labels/dados).
- Efeitos modernos como `backdrop-filter: blur()` na navbar (efeito vidro/glassmorphism).

### Gráficos / Dados
- **[Chart.js](https://www.chartjs.org/) v4.4.1** (via CDN cdnjs) — usado para renderizar múltiplos gráficos (pelo menos 9 instâncias de `new Chart(...)`).
- Plugin **[chartjs-plugin-datalabels](https://chartjs-plugin-datalabels.netlify.app/) v2.2.0** — para mostrar rótulos de dados diretamente nos gráficos.

### JavaScript
- **JS vanilla** (sem React/Vue), com um bloco `<script>` controlando a lógica de inicialização dos gráficos.

### Conteúdo
- Dados sobre como os brasileiros nascem, com base no **SINASC 2023**.

## 🎨 UI/UX

Paleta completa usada na página:

| Nome | Hex | Uso |
|---|---|---|
| **Rose** | ![#FF5733](https://placehold.co/15x15/e8546a/e8546a/png) `#e8546a` | Cor principal — CTAs, destaques, bordas, labels |
| **Rose Light** | ![#FF5733](https://placehold.co/15x15/fce8eb/fce8eb/png) `#fce8eb` | Fundos suaves de badges e highlights de tabela |
| **Teal** | ![#FF5733](https://placehold.co/15x15/2d7a7a/2d7a7a/png) `#2d7a7a` | Cor secundária — links, dots alternativos |
| **Teal Light** | ![#FF5733](https://placehold.co/15x15/e0f2f2/e0f2f2/png) `#e0f2f2` | Fundos suaves teal |
| **Amber** | ![#FF5733](https://placehold.co/15x15/d97706/d97706/png) `#d97706` | Cor de destaque — badges de warning |
| **Amber Light** | ![#FF5733](https://placehold.co/15x15/fef3c7/fef3c7/png) `#fef3c7` | Fundos suaves amber |
| **Ink** | ![#FF5733](https://placehold.co/15x15/1a1a2e/1a1a2e/png) `#1a1a2e` | Fundo hero, fundo stat cards, texto principal |
| **Ink 2** | ![#FF5733](https://placehold.co/15x15/2e2e4a/2e2e4a/png) `#2e2e4a` | Variação escura secundária |
| **Mist** | ![#FF5733](https://placehold.co/15x15/f7f6f3/f7f6f3/png) `#f7f6f3` | Fundo geral da página (off-white quente) |
| **Text 2** | ![#FF5733](https://placehold.co/15x15/4a4a6a/4a4a6a/png) `#4a4a6a` | Texto de corpo/parágrafos |
| **Text 3** | ![#FF5733](https://placehold.co/15x15/8888aa/8888aa/png) `#8888aa` | Texto auxiliar, labels de tabela |

**Acentos no hero (inline):**
- Teal claro: ![#FF5733](https://placehold.co/15x15/5dd6d6/5dd6d6/png) `#5dd6d6` — valores teal no card do hero
- Lilás: ![#FF5733](https://placehold.co/15x15/a78bfa/a78bfa/png) `#a78bfa` — valor de "98% hospital" no card
- Amarelo: ![#FF5733](https://placehold.co/15x15/fbbf24/fbbf24/png) `#fbbf24` — valor amber no card do hero

# 👨‍💼💻 Author 
Gabriel Prata
