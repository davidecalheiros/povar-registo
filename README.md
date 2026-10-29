# Povar: página de inscrição

Página única para inscrições em sessões e formações. Cada evento é uma entrada em `EVENTOS` no `index.html`; o link é `?e=<chave>`.

- No ar: https://davidecalheiros.github.io/povar-registo/?e=aepvz-restauracao (futuro: registo.povar.pt, CNAME na Hostinger).
- Envio: POST para o webhook n8n `/webhook/povar-registo` (workflow por criar). Até lá, o formulário mostra erro e pede para escrever para hello@povar.pt.
- Atualizar: editar `index.html` e fazer `git push`.
