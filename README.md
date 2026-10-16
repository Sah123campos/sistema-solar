# O Sistema Solar — uma jornada de 4,5 bilhões de anos

Site imersivo e cinematográfico sobre os planetas do Sistema Solar. A rolagem da página é uma viagem pelo espaço: a câmera 3D visita o Sol e cada um dos oito planetas, compara seus tamanhos reais e se afasta até a Via Láctea.

**[▶ Ver o site](https://sah123campos.github.io/sistema-solar/)**

## Destaques

- **3D em tempo real** com Three.js: todos os planetas são procedurais (shaders GLSL, sem imagens externas).
- **Atmosferas físicas** com espalhamento de Rayleigh e Mie calculado por ray-marching.
- **Geografia real**: Monte Olimpo, Valles Marineris e Hellas em Marte; faixas de Júpiter nas latitudes reais e Grande Mancha Vermelha; hexágono polar e divisões dos anéis de Saturno; Grande Mancha Escura de Netuno.
- **Rolagem narrativa** com GSAP + ScrollTrigger e rolagem suave com Lenis.
- Fichas técnicas com dados da NASA (Planetary Fact Sheet) e comparação de escala em proporção real.
- Responsivo, com suporte a toque e respeito a `prefers-reduced-motion`.

## Como rodar

É um único arquivo HTML, sem build: abra `index.html` no navegador (as bibliotecas e fontes vêm de CDN, então é preciso estar online).

## Tecnologias

Three.js r160 · GSAP 3.12 · ScrollTrigger · Lenis · Cormorant Garamond e Space Grotesk (Google Fonts)

---

Dados: NASA Planetary Fact Sheet; contagem de luas confirmadas segundo a NASA (2025). Visualização artística: as distâncias entre os planetas na cena estão fora de escala.
