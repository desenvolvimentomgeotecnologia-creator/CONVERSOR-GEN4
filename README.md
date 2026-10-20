# Unificador GEN4 – MGEO

Site que unifica vários conjuntos de dados GEN4 (`MasterData.xml` + `SpatialFiles`) em um só, direto no navegador. Nenhum arquivo é enviado para servidor.

## Como usar

1. Abra o site.
2. Arraste as pastas das fazendas ou os arquivos `.zip` exportados (ou use os botões).
3. Confira a lista e, se quiser, escolha qual conjunto é o **principal** (o cliente dele será usado para todas as fazendas).
4. Clique em **Unificar e baixar**.
5. Extraia o `UNIFICADO_GEN4_MGEO.zip` e copie a pasta `Gen4` para a raiz do pen drive.

## Estrutura do repositório

```
index.html   ← o site completo
logo.png     ← logo exibida no topo e como ícone da aba
README.md
```

## Publicar no GitHub Pages

1. Envie `index.html` e `logo.png` para a raiz do repositório.
2. No GitHub: **Settings → Pages → Build and deployment**.
3. Em *Source*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Em alguns minutos o site fica disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPO/`.

---
Desenvolvido por: Lucas Benati – Versão 1.0 Web
