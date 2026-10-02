# portfolio.cyberhat.com.br

Site estático, sem build.

```
index.html      página completa (CSS, JS e foto embutidos)
foto.webp       cópia da foto (não é usada pelo index, só backup)
videos/*.webm   prévias dos cards, carregadas sob demanda pelo index.html
.htaccess       HTTPS, www -> sem www, MIME do webm, gzip e cache
robots.txt      libera tudo e aponta para o sitemap
sitemap.xml     URL raiz
```

## Publicar na Hostinger

Enviar todo o conteúdo desta pasta para a raiz do subdomínio `portfolio.cyberhat.com.br`
(a pasta `public_html` dele), mantendo `videos/` ao lado do `index.html`.
O `.htaccess` é um arquivo oculto: confira se ele foi junto.

Alternativa: hPanel > Avançado > Git, apontando este repositório para a pasta do subdomínio.
