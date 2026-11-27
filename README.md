# joaomario-site

O site profissional de **João Mário Araújo**, Product Designer UI/UX e Identidade Visual, em João Pessoa.
Publicado em [duminguz.com.br](https://duminguz.com.br) pelo GitHub Pages.

## Como é feito

Uma página estática, sem framework e sem build no servidor:

- `index.html`: a página;
- `assets/media/`: as imagens e os vídeos das peças;
- `assets/favicon.svg`, `CNAME`, `robots.txt`, `sitemap.xml`, `.nojekyll`.

**Não edite o `index.html` à mão.** Ele é gerado fora deste repositório, a partir das peças originais, e é
sobrescrito a cada nova versão. Uma mudança feita aqui se perde na próxima.

## Publicação

1. **Settings → Pages:** branch `main`, pasta `/ (root)`. O arquivo `CNAME` já aponta para `duminguz.com.br`.
2. **DNS no Registro.br**, na zona de `duminguz.com.br`:

   | Tipo | Nome | Valor |
   |---|---|---|
   | A | (vazio) | 185.199.108.153 |
   | A | (vazio) | 185.199.109.153 |
   | A | (vazio) | 185.199.110.153 |
   | A | (vazio) | 185.199.111.153 |
   | CNAME | www | joaoduminguz.github.io |

3. Quando o DNS propagar, marque **Enforce HTTPS** em Settings → Pages.

© João Mário Araújo. As peças mostradas pertencem a seus clientes e equipes, com os créditos indicados no site.
