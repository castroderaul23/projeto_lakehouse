# Arquitetura Lakehouse

O projeto foi estruturado em três camadas.

## Bronze

Camada responsável pela ingestão bruta do CSV.

Nenhuma transformação relevante é aplicada.

## Silver

Camada responsável pela limpeza e padronização dos dados.

Exemplos:

- tratamento de valores nulos
- conversão de tipos
- padronização textual

## Gold

Camada analítica.

Responsável pelas agregações e métricas utilizadas para análise dos dados do Brasileirão.