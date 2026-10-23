# Dashboard de Filmes: IMDb e Rotten Tomatoes

Painel em Power BI que analisa 200 filmes, relacionando orçamento, bilheteria, retorno sobre o investimento (ROI) e avaliações.

## Dados
Coletados diretamente dos sites do IMDb e do Rotten Tomatoes.

## Tratamento (Power Query)
- Remoção de duplicados e de linhas em branco
- Correção de dados incorretos

## Medidas (DAX)
Criei as medidas das análises, como ROI médio e nota média ponderada.

## O que o painel mostra
- Indicadores de orçamento, bilheteria, nota média ponderada e ROI médio
- Dispersão entre bilheteria, orçamento e número de votos
- Ranking de bilheteria e distribuição de filmes por gênero
- Metascore, árvore de decomposição (gênero, diretor e título) e nota por ano
- Filtros por nota, duração, votos, prêmios e gênero

## Principais conclusões
- **Retorno geral:** os 200 filmes somam US$ 3,22 bi de orçamento e US$ 8,17 bi de bilheteria, cerca de 2,5 vezes o valor investido (ROI médio de 153,75%).
- **Orçamento não garante bilheteria:** Justice League tem o maior orçamento (cerca de US$ 300 mi), mas Jurassic World, com metade desse orçamento, teve a maior bilheteria (cerca de US$ 1,7 bi).
- **Sucesso comercial e nota são coisas diferentes:** o filme de maior bilheteria (Jurassic World) não é o de maior nota (Soorarai Pottru).
- **Gêneros:** drama (51), ação (41) e comédia (40) concentram a maior parte dos filmes analisados.
- **Notas por ano:** a maior nota do ano ficou acima da média geral (7,43) de 2019 a 2023, com pico de 8,6 em 2020, e abaixo dela de 2024 a 2026.
- **Crítica e público:** a nota média é 6,57 (escala de 0 a 10), enquanto o Metascore médio é 53,73 (escala de 0 a 100), o que indica que a crítica foi mais exigente.
