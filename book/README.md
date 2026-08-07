# IA Generativa para Data Science — Notas de Estudo

## Compilar o livro localmente

```bash
jupyter-book build .
```

O HTML gerado fica em `_build/html/`.

> Se ainda não tiver o `jupyter-book` instalado:
> ```bash
> pip install jupyter-book
> ```

## Publicar no GitHub Pages

O conteúdo de `_build/html/` precisa ir para a branch `gh-pages`. Use o `ghp-import` (bem mais simples que fazer na mão):

```bash
# Instale uma vez (se ainda não tiver)
pip install ghp-import

# Publique (no diretório raiz do livro)
ghp-import -n -p -f _build/html
```

O livro fica disponível em:
**https://lucas-data-science.github.io/GenAI_notes/**
