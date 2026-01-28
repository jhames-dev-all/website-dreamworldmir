# dreamworldmir

Site estático gerado para publicação via GitHub Pages.

Publicação automática:
- O workflow em `.github/workflows/gh-pages.yml` publica o conteúdo do repositório para a branch `gh-pages` quando há push para `main` ou `master`.

Como publicar localmente (exemplo):

```powershell
git init
git remote add origin https://github.com/jhames-dev-all/dreamworldmir.git
git add .
git commit -m "Initial site + GitHub Pages workflow"
git push -u origin main
```

Se preferir usar `master` troque `main` por `master` nos comandos acima.

URL prevista after deploy:
`https://jhames-dev-all.github.io/dreamworldmir/`

Se for usar domínio próprio, adicione um arquivo `CNAME` com o domínio na raiz.
