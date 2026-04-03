# CV em PDF (LaTeX)

Para compilar o CV em PDF, utilize o `arara`:

```bash
# Na raíz do repositório:
arara -v -d PDF main.tex

# Ou no diretório do arquivo .tex:
cd PDF
arara -v main.tex
```

Nos dois casos, o arquivo `main.pdf` será gerado no mesmo diretório do arquivo `/PDF/main.tex`.
