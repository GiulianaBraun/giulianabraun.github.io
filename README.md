# MEU SITE

Para gerar o `index.html`, use o comando

```bash
pandoc index.md \
    --standalone \
    --metadata=lang:pt-BR \
    --katex \
    --css="https://cdn.jsdelivr.net/npm/water.css@2/out/dark.css" \
    --css=styles.css \
    -o index.html
```
