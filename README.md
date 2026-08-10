
# Projeto PRF 2025 — Preparação dos Dados

## Variável-alvo
`acidente_fatal = 1` quando `mortos >= 1`; caso contrário, `acidente_fatal = 0`.

## Bases geradas
- `dados_tratados/base_analitica_prf_2025.csv`: base completa para EDA e Power BI.
- `dados_tratados/base_modelavel_prf_2025.csv`: base para modelagem, sem data leakage.

## Fonte dos dados

Dados abertos da PRF — registros de acidentes de trânsito em rodovias federais, ano de 2025. Cada linha representa uma ocorrência (acidente), não um veículo ou uma pessoa envolvida.

## Objetivo

Transformar a base bruta da PRF em duas bases prontas para uso, tratando problemas comuns de dados públicos: encoding, tipos, nulos, duplicidade, padronização de texto e datas — e construir a variável-alvo do projeto.

## Variável-alvo

acidente_fatal = 1 quando mortos >= 1; caso contrário, acidente_fatal = 0.

Nesta execução: 72.529 acidentes, dos quais 7,18% foram fatais.
