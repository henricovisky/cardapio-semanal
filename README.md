# Cardápio da Semana

Site estático de plano alimentar semanal. Focado em **controle glicêmico rigoroso, digestão leve (baixo FODMAP/anti-fermentação) e alto teor de fibras**. Um único arquivo HTML autocontido (CSS + JS inline).

## Abas
- **Hoje / por dia** — menu do dia com refeições (Segunda a Domingo)
- **Semana inteira** — cardápio completo da semana (7 dias)
- **Ingredientes** — lista de compras **semanal** e **mensal** (×4 semanas)

## Regras do plano
- **Carboidrato travado**: chia/aveia/linhaça na tapioca e cuscuz antes do cozimento.
- **Feijão**: remolho mínimo de 12h, descartando a água da espuma.
- **Alho e cebola**: sempre refogados, nunca crus.
- **Conservas** (atum/sardinha): em óleo, mas o óleo totalmente escorrido e descartado.
- **Frutas**: consumir com casca/bagaço (quando aplicável) e salpicar fibras.

## Como rodar
Basta abrir o `index.html` no navegador, ou servir com:

```bash
python3 -m http.server 8080
```

## Estrutura
```
index.html   # site completo (autocontido)
```

## Deploy (Vercel / Netlify)
Arraste a pasta (ou o `index.html`) em https://vercel.com/new — HTTPS grátis automático.
