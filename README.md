# Futura Casa — Versão Final Corrigida

Esta versão corrige tela branca causada por carregamento incompleto de arquivos, rewrite amplo no Vercel ou service worker/cache antigo.

## Estrutura correta

Suba todos estes itens na raiz do repositório/projeto:

- index.html
- styles.css
- app.js
- assets/

Não suba apenas o index.html.

## Vercel

No Vercel, importe o repositório como projeto estático. Não é necessário vercel.json.

Se já havia uma versão anterior publicada:
1. Limpe cache do navegador.
2. Faça novo deploy.
3. Em caso de PWA/cache antigo, abra em aba anônima ou remova dados do site.

## HTML único

Também gerei uma versão standalone:
futura-casa-final-standalone.html

Ela não depende de CSS/JS externos.
