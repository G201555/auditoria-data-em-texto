# Auditoria: a data em texto que sumia com um ano

Correção de um relatório de Power BI de campanha que mostrava números errados.

## O problema

A query excluía algumas UFs num período. A comparação de datas era feita com as datas guardadas como texto, então a ordem era alfabética e não cronológica: os registros de 2026 eram descartados e os de 2025 ficavam.

## A correção

- `f_compreeganhe_corrigido.sql`: a query com a data convertida antes da comparação.
- `medidas_volta_as_aulas.dax`: as medidas DAX revistas.

## Stack

SQL Server (T-SQL), DAX, Power BI.

---
Projeto feito no trabalho, publicado sem dados.
