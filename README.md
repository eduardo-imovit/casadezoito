# CasaDezoito — site

Página institucional única (one-pager) da CasaDezoito — *Lares, Design e Negócios*.
Av. Rotary, 134 — Vila Brandina, Campinas/SP.

Site **estático**, sem build: um `index.html` + a pasta `assets/`. Direção visual "A"
(editorial de galeria), animações em JavaScript puro (sem bibliotecas).

## Estrutura

```
index.html            página inteira (HTML + CSS + JS embutidos)
favicon.svg
robots.txt  sitemap.xml
vercel.json           clean URLs + cache dos assets
assets/
  og.jpg              imagem de compartilhamento (redes sociais)
  fotos/              fotos do espaço usadas na página
  logos/              logos das empresas (entram na seção "Empresas" quando prontos)
```

## Como editar

- **Textos:** direto no `index.html`, nas seções marcadas por comentários (`<!-- HERO -->`,
  `<!-- 01 CONCEITO -->`, etc).
- **Fotos:** troque os arquivos em `assets/fotos/` mantendo o mesmo nome, ou ajuste o
  `src` no HTML. Mantenha ~1200–1500 px de largura e < 180 KB por imagem.
- **Contato:** rodapé, procure por `gestao@casadezoito.com.br` e `casadezoito_campinas`.

## Deploy (Vercel)

1. Suba este diretório para um repositório no GitHub (privado).
2. Na Vercel: *New Project* → importe o repositório.
   - Framework Preset: **Other**
   - Build Command: *(vazio)*
   - Output Directory: `.` (raiz)
3. Deploy. Depois, em *Settings → Domains*, aponte o domínio final.

## Pendências (v1)

- [ ] Logo da **Imovit** (não recebido)
- [ ] Logo do **Sterna Café** (não recebido)
- [ ] Telefone / WhatsApp (aguardando chip) — hoje o contato é só e-mail + Instagram + endereço
- [ ] Logos das 6 empresas na seção "Empresas" (hoje em texto) — arquivos em `assets/logos/`
- [ ] Aprovação final da copy pelo cliente
- [ ] Revisar tempos verbais (o espaço já está pronto; alguns trechos estão no futuro)
