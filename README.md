# Transações Pix por Município

Análise dos dados abertos de transações Pix disponibilizados pelo Banco Central do Brasil.

## Fonte

**Banco Central do Brasil — Dados Abertos**

**Dataset:** Transações Pix por Município

## Dados

O dataset apresenta informações sobre transações Pix agregadas por município, permitindo analisar a movimentação do Pix ao longo do tempo e sua distribuição geográfica.

## Etapas

1. Extração dos dados
2. Análise dos metadados
3. Análise da qualidade dos dados
4. Limpeza e tratamento
5. Análise exploratória
6. Análise dos resultados
7. Conclusões

## Fluxo

```text
DADO BRUTO
    │
    ▼
EXTRAÇÃO
    │
    ▼
DATA PROFILING
    │
    ├──────────────────┐
    ▼                  ▼
METADADOS          QUALIDADE
                       │
              ┌────────┼─────────┐
              ▼        ▼         ▼
            Nulos  Duplicados  Inconsistências
              │
              └────────┬────────┘
                       ▼
               LIMPEZA E TRATAMENTO
                       │
                       ▼
                    ANÁLISE
                       │
                       ▼
                 VISUALIZAÇÕES
                       │
                       ▼
                   CONCLUSÕES
```
