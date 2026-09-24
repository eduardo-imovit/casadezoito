# Handoff — CasaDezoito (site institucional)

## Sprint 2026-09-24 — Revisão de copy

**Objetivo:** revisar e otimizar os textos do site (`index.html`).

### Feito
- Hero: o 2º parágrafo agora diz o que tem na casa (imóveis, arquitetura, construção, design, investimentos) em vez de falar do "andar de negócios".
- Conceito: textos de Casa e Dezoito mais claros, sem parênteses; a frase de destaque trocou "move o invisível" por "dá nome ao que não se vê, mas se sente".
- Faixa de citação: "Como uma casa" virou "Uma casa" (a casa é literal), e "parte principal da cena" virou "protagonista".
- Pessoas: frases finais mais enxutas.
- Seção 03: tirei o jargão ("unir operações", "consumidor", "jornada de compra"), consertei a frase que não tinha verbo principal e troquei "ponto de conexão" por "ponto de encontro".
- Andar de negócios: texto mais curto.
- Grade de empresas: o Sterna Café passou a ser "Cafeteria" (antes repetia "o café da casa", que já aparece na lista de espaços).
- A meta description acompanha o novo hero.
- Continua sem travessões.

### Estado atual
- Commitado e enviado para `origin/main` a pedido do Eduardo, que vai colocar no ar. O mesmo commit leva uma alteração de JS de uma sessão anterior (`setupConcept()`, que refaz a animação do "18" ao cruzar 860px ao redimensionar). Ela foi lida por cima, mas não testada.
- Não conferi o texto no navegador: a quebra de linha dos textos animados palavra a palavra (`data-split`) no hero e na seção 03 não foi verificada.

### Pendências / próximos passos
- [ ] O Eduardo aprovar a copy.
- [ ] Confirmar "Visitas com hora marcada" no rodapé, porque o Sterna Café sugere que o público pode entrar sem agendar.
- [ ] Testar o `setupConcept()` redimensionando a janela (desktop → mobile → desktop).
- [ ] Publicar na Vercel, colocar a logo da Imovit e testar no celular (veja o README).

### Como retomar
- `npx serve .` (ou qualquer servidor estático) na raiz e abrir `index.html`.
