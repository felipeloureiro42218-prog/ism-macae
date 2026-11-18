# ISM Macaé — Dashboard experimental

Dashboard navegável para hospedagem estática no GitHub Pages, com dados agregados do ISP-RJ e população do IBGE.

## O que esta versão apresenta
- Taxas por 100 mil habitantes e registros absolutos, de 2014 a 2025, mais 2026 parcial (janeiro–setembro).
- Pontuação sintética **experimental** do ISM para 2014–2025, calculada com D1, D2 e D3.
- D1: letalidade violenta (1 indicador). D2: média de lesão corporal dolosa e tentativa de homicídio (2 indicadores). D3: média de roubos, furtos e estelionato (3 indicadores).
- Normalização min–max invertida, com limites fixados na série 2014–2025.
- Agregação provisória: ISM experimental = (D1 + D2 + D3)/3. Pesos iguais entre dimensões e entre indicadores de uma mesma dimensão.
- D4 segurança viária: pendente de dados. D5 violência de gênero: excluída provisoriamente desta versão.

**A pontuação experimental não é o ISM definitivo**, não inclui D4/D5 e não deve ser interpretada como avaliação causal das políticas de segurança.

## Publicar no GitHub Pages
1. Crie um repositório, por exemplo `ism-macae`.
2. Envie o `index.html` à raiz da branch `main`.
3. Em **Settings → Pages**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`.
4. Salve e aguarde o endereço publicado.
5. Atualizações: substitua o arquivo `index.html` no repositório.

O painel não exige servidor nem bibliotecas externas. Em repositório público, o HTML e os dados agregados ficam públicos.

## Ponderação experimental (versão 3)

- D1 (50%): letalidade violenta (100%).
- D2 (30%): tentativa de homicídio (70%), lesão corporal dolosa (30%).
- D3 (20%): roubos (60%), furtos (20%), estelionato (20%).
- ISM experimental = 0,50 × D1 + 0,30 × D2 + 0,20 × D3.

Os pesos são provisórios, sujeitos a testes de sensibilidade. D4 aguarda dados e D5 não integra esta versão.
