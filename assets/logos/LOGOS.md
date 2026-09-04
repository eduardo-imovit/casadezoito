# Logos das empresas

Aplicados na seção "Empresas" do `index.html` (grid `.brands`).

| Empresa | Arquivo | Situação |
|---|---|---|
| Imovit | `imovit.png` | ok — rasterizado de `Logos-Imovit-Lares_imovit-lares-grafite.png` (variante grafite, já transparente) |
| Montblanc Capital | `montblanc.png` | ok — rasterizado do PDF "MB EQI HORIZONTAL", recortado pra excluir a co-marca EQI, fundo removido |
| Veraci | `veraci.png` | ok — de `VERACI_Logo_INPI.jpg`, fundo branco removido (chroma-key) |
| GOMA | `goma.png` | ok — página 01 do brandbook (`GOM-0001-25 Brand_001_V1-01.png`), já vinha com alpha |
| Larissa Gimenes | `larissa.png` | ok — rasterizado do `logo-larissa.ai` (monograma + wordmark + "Arquitetura") |
| Sterna Café | `sterna.png` | ok — logo oficial do LinkedIn da empresa (marca "STERNA CAFÉ" + pássaro), fundo removido. Tile usa `.lg.sq` (52px) em vez de 32px por ser um lockup quadrado/empilhado, não uma linha só |

Todos recortados no conteúdo real (sem bordas de sobra) e com fundo transparente.
No grid, aparecem em escala de cinza sutil e voltam à cor original no hover
(`.brands .b .lg`, CSS em `index.html`).

CasaDezoito: `casadezoito-tan.png` / `casadezoito-greige.png` (o site usa texto na marca do topo;
guardado aqui caso precise). Ideal conseguir o vetor SVG.
