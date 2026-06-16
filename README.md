# Painel Contruc

Frontend estatico do painel administrativo de respondentes e relatorios individuais.

## Arquivos

- `index.html`
- `config.js`
- `netlify.toml`

## Deploy na Netlify

1. Conecte este repositorio no GitHub.
2. Importe o repositorio na Netlify.
3. Deixe `Base directory`, `Publish directory` e `Build command` vazios.
4. O site publica a raiz do repositorio.

## Backend

Por padrao, `config.js` aponta para:

- `https://backend-production-5b5cc.up.railway.app`

Esse backend precisa expor:

- `GET /api/admin/respostas`
- `GET /api/admin/respostas/:id/html`
- `GET /api/admin/respostas/:id/pdf`
