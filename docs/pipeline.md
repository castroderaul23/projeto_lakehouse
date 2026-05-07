# Pipeline Bronze, Silver e Gold

## Fluxo do Projeto

1. Leitura do CSV do Brasileirão
2. Criação da camada Bronze
3. Limpeza e transformação na Silver
4. Agregações analíticas na Gold
5. Persistência usando Delta Lake e Iceberg

## Exemplo de processamento

Foram realizadas transformações como:

- padronização de colunas
- conversão de tipos
- remoção de inconsistências
- agregações estatísticas

## Resultado

O pipeline permitiu estruturar os dados do Brasileirão em um modelo analítico escalável.