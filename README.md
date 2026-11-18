# ISM Macaé — Painel experimental de indicadores

Painel navegável para GitHub Pages, elaborado com registros agregados do ISP-RJ e população do IBGE.

## Conteúdo
- Taxas por 100 mil habitantes e ocorrências absolutas de 2014 a 2025, além de 2026 parcial (janeiro–setembro).
- Indicadores normalizados em escala experimental 0–100, com referências min–max fixas de 2014–2025.
- ISM sintético experimental de 2014–2025, composto por três dimensões.
- Seletor de medida aplicado à leitura do indicador selecionado e ao seu gráfico histórico. A pontuação sintética do ISM é sempre expressa em pontos.

## Ponderação experimental
- **D1 — Violência letal (50%):** letalidade violenta (100%).
- **D2 — Violência contra a pessoa (30%):** tentativa de homicídio (70%) e lesão corporal dolosa (30%).
- **D3 — Criminalidade patrimonial (20%):** roubos (60%), furtos (20%) e estelionato (20%).

**Fórmula:** ISM experimental = 0,50 × D1 + 0,30 × D2 + 0,20 × D3.

Os pesos são provisórios e dependem de testes de sensibilidade. D4 — Segurança viária aguarda dados; D5 — Violência baseada em gênero não integra esta versão por insuficiência de cobertura. O ISM experimental não constitui avaliação causal de políticas públicas.

## Publicação
Envie `index.html` e `README.md` para a raiz da branch `main` de um repositório GitHub e ative **Settings → Pages → Deploy from a branch → main → / (root)**.

O HTML contém os dados e não depende de servidor externo. Em repositórios públicos, o conteúdo fica acessível a terceiros.
