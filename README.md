# Povar: página de inscrição

Página única para inscrições em sessões e formações. Cada evento é uma entrada em `EVENTOS` no `index.html`; o link é `?e=<chave>`.

- No ar: https://davidecalheiros.github.io/povar-registo/?e=aepvz-restauracao (futuro: registo.povar.pt, CNAME na Hostinger).
- Envio: POST para o webhook n8n `/webhook/povar-registo`, workflow "Povar | Registos" (e5OqXG74h5Bpx4ra): guarda na tabela n8n `registos` (jSTgj4GQWu7BJwH4) e envia email de confirmação. O link do Meet de cada evento preenche-se no nó "Validar inscrição".
- Atualizar: editar `index.html` e fazer `git push`.
