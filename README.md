# Vila Mont Serrat

Apresentação interativa para convencer amigos a se mudarem para o bairro Mont Serrat, Porto Alegre, RS.

## Como rodar

```bash
npm install
npm run dev
```

Abre em `http://localhost:5173`

## Como publicar no Vercel

```bash
npm install -g vercel
vercel
```

## Como publicar no Netlify

```bash
npm run build
# Arraste a pasta `dist/` para netlify.com/drop
```

## Tecnologias

- React 18 + Vite
- Leaflet (mapa interativo)
- Google Fonts: Bebas Neue, Noto Serif, IBM Plex Mono

## Navegação

- **Swipe** esquerda/direita no celular
- **Setas** ← → no teclado
- **Botões** na barra inferior
- **Dots** clicáveis na barra de navegação

## Estrutura dos slides

1. Capa
2. O Problema (Canoas)
3. Hipótese Social
4. A Vila (com mapa)
5. Raio Caminhável
6. Cafés
7. Restaurantes
8. Bares
9. Academias
10. Parques
11. Mercados
12. Padarias
13. Vida Prática
14. Vida Nerd
15. Simulação Social
16. ROI Social
17. A Equipe
18. Fundação da Vila
19. Guia da Vila

## Personalização

Edite `src/App.jsx` para:
- Trocar fotos (constantes `IMG_BR` e `IMG_MY` no topo)
- Atualizar listas de lugares
- Ajustar cores no objeto `C`
- Adicionar ou remover slides no array `SLIDES`
