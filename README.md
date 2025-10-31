# Recriação — iPhone 15 Pro (Apple)

Este projeto é uma recriação do site do iPhone 15 Pro da Apple, construída com foco em animações avançadas e cenas 3D. Ele combina:

- React (Vite) para a aplicação front-end moderna e rápida
- Tailwind CSS para estilo utilitário e responsivo
- GSAP para animações fluídas e controladas
- Three.js (via @react-three/fiber e @react-three/drei) para cenas 3D interativas

O objetivo é simular a experiência visual e interativa do site oficial, usando técnicas modernas de web (WebGL, animações e otimizações) — é um projeto de portfólio.

## Demonstração

- Visite a versão hospedada no Vercel (https://apple-xi-virid.vercel.app/).
- Repare nas animações de entrada, rotação do modelo 3D, e transições entre seções.

## Tecnologias

- Vite — bundler e dev server rápido
- React 18+ — biblioteca UI
- Tailwind CSS — utilitários CSS
- GSAP — animações (timelines, scroll, morphs)
- Three.js + @react-three/fiber + @react-three/drei — render 3D
- Deploy: Vercel

## Recursos e funcionalidades

- Modelo 3D do aparelho integrado com Three.js (GLTF/GLB)
- Animações orquestradas com GSAP (entrada, parallax, micro-interações)
- Carousel de vídeos e mídia responsiva
- Loader inicial e experiência otimizada para WebGL
- Layout responsivo com Tailwind, otimizado para desktops e mobile
- Pré-carregamento de texturas/meshes e gestão básica de performance

## Estrutura do projeto (resumo)

- `src/` — código fonte React
  - `components/` — componentes (Hero, Navbar, ModelView, Loader, etc.)
  - `constants/`, `utils/` — valores e helpers
  - `App.jsx`, `main.jsx`, `index.css` — entrada da aplicação
- `models/` — modelos 3D e assets relacionados
- `public/assets/` — imagens, vídeos
- `vite.config.js`, `tailwind.config.js`, `postcss.config.js` — configs
