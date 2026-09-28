# Pastel Dourado

Site estático responsivo para uma pastelaria brasileira premium.

## Arquivos

- `index.html`: estrutura da landing page, cardápio, combos, história e CTA.
- `styles.css`: identidade visual, responsividade, animações e componentes.
- `script.js`: menu mobile, ano automático e revelação ao rolar.

## Como testar localmente

```bash
cd /root/pastel-site
python3 -m http.server 4173
```

Abra: http://localhost:4173

## Antes de publicar

Troque todos os links `https://wa.me/5500000000000` pelo número real da pastelaria, em formato internacional.

## Deploy sugerido

- GitHub + Vercel: criar repositório, subir estes arquivos e importar o repo na Vercel.
- Cloudflare Pages: criar projeto, conectar o repositório e usar output estático sem build.
- GitHub Pages: publicar a branch principal com raiz `/`.
