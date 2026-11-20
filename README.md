# Gibraltek

Site estático servido pelo Cloudflare Workers Static Assets. As duas páginas e suas imagens estão em `public/`. O site usa Font Awesome via CDN para os ícones.

## Publicação

No Workers Builds, aponte para a branch `main`, com a raiz do repositório como diretório de trabalho, comando de build vazio e comando de publicação `npx --yes cf@1.0.0-rc.2 deploy ./public`. Use Node.js 24. A configuração publica em `workers.dev`. A associação do domínio é uma operação separada.
