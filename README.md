# Lud · Motoaventuras pela Europa

Site estático (HTML + CSS puro) com os roteiros de moto.

## Publicar grátis no GitHub Pages

1. Crie um repositório público chamado **`ludmila06marques.github.io`**. Esse nome gera o endereço `https://ludmila06marques.github.io` (se seu usuário do GitHub for outro, use `SEUUSUARIO.github.io`).
2. Suba todos os arquivos desta pasta pra branch `main`.
3. No repositório, vá em **Settings → Pages → Build and deployment**, escolha *Deploy from a branch*, selecione `main` e a pasta `/ (root)` e salve.
4. Em 1 ou 2 minutos o site está no ar.

## Estrutura

```
index.html                  → home (apresentação + lista de roteiros)
roteiros/bardenas-reales.html
roteiros/picos-de-europa.html
assets/style.css            → cores e estilos
assets/fotos/               → coloque as fotos aqui
```

## Colocar fotos

1. Salve as fotos em `assets/fotos/` (de preferência em .jpg, com até ~1600px de largura e menos de 500 KB cada).
2. Nos HTML, troque os blocos marcados com o comentário `<!-- Troque ... -->` por uma `<img>`, por exemplo:
   ```html
   <div class="foto"><img src="../assets/fotos/bardenas-1.jpg" alt="Pista de cascalho nas Bardenas"></div>
   ```

## Novo roteiro

Copie `roteiros/picos-de-europa.html`, renomeie o arquivo, preencha o conteúdo e adicione um card novo em `index.html`, na seção `#roteiros`.
