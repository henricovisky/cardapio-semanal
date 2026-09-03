# Cardápio da Semana

Site estático de plano alimentar semanal. Clone do original feito em Next.js, convertido para **um único arquivo HTML** autocontido (CSS + JS inline).

## Abas
- **Hoje / por dia** — menu do dia com refeições (Segunda a Sexta)
- **Semana inteira** — cardápio completo da semana
- **Ingredientes** — quantidade de ingredientes **semanal** e **mensal**

## Como rodar
Basta abrir o `index.html` no navegador, ou servir com:

```bash
python3 -m http.server 8080
```

## Estrutura
```
index.html   # site completo (autocontido, ~20 KB)
```

## Deploy (Vercel / Netlify)
Arraste a pasta (ou o `index.html`) em https://vercel.com/new — HTTPS grátis automático.
