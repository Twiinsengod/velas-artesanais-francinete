# Francinete · velas artesanais

Site de uma página para as aulas presenciais de velas artesanais da Francinete, em Taguatinga Norte, Brasília.

Enquanto a pessoa rola a página, uma vela desenhada em código se desmonta peça por peça (tampa, pavio, fragrância, cera, cumbuca de alumínio, recipiente e rótulo), e cada peça explica uma parte da vela artesanal.

## Estrutura

- `index.html`: a página inteira (HTML, CSS e o script da vela)
- `scrollcraft.css` / `scrollcraft.js`: motor de animação por scroll ([scroll-craft](https://github.com/nateherkai/scroll-craft))
- `fonts/`: Fraunces e Geist (variáveis, só caracteres latinos)
- `assets/`: foto de "Quem ensina", camadas do hero e a imagem de prévia do link (`og.jpg`)

Site estático: não tem build. Para ver localmente, sirva a pasta com qualquer servidor estático, por exemplo `npx serve .`.

## Publicação

Qualquer hospedagem estática serve (Vercel, Cloudflare Pages, Netlify, GitHub Pages). Sem comando de build; a pasta publicada é a raiz do repositório.

Depois de ter o endereço final, troque em `index.html` a linha `og:image` pelo endereço completo da imagem (ex.: `https://seudominio.com.br/assets/og.jpg`) para a prévia do link aparecer no WhatsApp.
