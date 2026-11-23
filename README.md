# Percentil — Métricas de Periódicos e Planilha de Avaliação por Percentil

**Ferramentas gratuitas para consultar métricas bibliométricas de periódicos científicos e pontuar a produção intelectual de docentes segundo os critérios de percentil da CAPES (Área 24 – Medicina Veterinária). Desenvolvidas para apoiar coordenadores, docentes e pesquisadores de programas de pós-graduação stricto sensu na escolha de periódicos, no credenciamento docente e na montagem de propostas (APCN).**

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24479784.svg)](https://doi.org/10.5281/zenodo.24479784)

Versão atual: **1.1.0** (DOI 10.5281/zenodo.24479784). Versão anterior: 1.0.0 (DOI 10.5281/zenodo.21400661).

---

## O que há neste repositório

| Arquivo | Para que serve |
|---|---|
| `percentil_periodicos.html` | **Aplicativo de consulta.** Busca, filtra e compara periódicos pelas métricas de percentil. |
| `Percentil_planilha_avaliacao_v1.1.xlsx` | **Planilha de avaliação** (novo na v1.1). O avaliador digita quantos artigos o docente tem em cada revista e a planilha calcula os pontos, a soma das 5 melhores produções e se o docente atinge os mínimos do APCN. |

Os dois componentes usam a mesma base: **443 periódicos** de Medicina Veterinária e áreas correlatas (Zootecnia, Ciência Animal, Reprodução Animal, Equinos, entre outras).

---

## Métricas

| Métrica | Fonte | Nesta versão pública |
|---|---|---|
| **CiteScore Percentil** | Scopus / Elsevier | Incluída (acesso aberto) |
| **SJR Percentil e Quartil** | SCImago Journal Rank | Incluída (acesso aberto) |
| **h5-index** | Google Scholar Metrics | Incluído no aplicativo (acesso aberto) |
| **JCR – JIF Percentile** | Clarivate / Web of Science | **Coluna para preenchimento pelo usuário** |

> **Por que o JCR vem em branco?** As métricas do Journal Citation Reports pertencem à Clarivate e são de acesso institucional, e os termos de uso não permitem redistribuí-las. A planilha e o aplicativo já estão prontos para calcular com o JCR: cada programa preenche o **JIF Percentile** (não o JCI Percentile) consultado pelo próprio acesso ao Portal de Periódicos CAPES.

---

## Planilha de avaliação: como usar

1. Baixe `Percentil_planilha_avaliacao_v1.1.xlsx` e abra no Excel, no LibreOffice ou no Google Sheets.
2. Na aba **Avaliação**, digite o nome do docente e, na coluna amarela **Nº de artigos**, quantos artigos ele tem em cada revista.
3. O topo da aba mostra o total de pontos e a **soma das 5 melhores produções**. A aba **Resumo** mostra os artigos por estrato e se o docente atinge os mínimos do APCN (mestrado e doutorado).
4. Revistas fora da lista entram nas linhas cinza no fim da aba. Para revistas sem dado, digite o percentil na própria linha.

**Regra de cálculo:** vale o maior percentil entre JCR e CiteScore (o SJR pode ser incluído na aba *Tabela de pontos*). Pontos por artigo: ≥ 87,5 = 100; ≥ 75 = 75; ≥ 62,5 = 62,5; ≥ 50 = 50; ≥ 37,5 = 37,5; ≥ 25 = 25; ≥ 12,5 = 12,5; < 12,5 = 0,06. A tabela é editável e a planilha recalcula sozinha se o critério mudar.

A planilha **não avalia a aderência** do artigo à linha de pesquisa nem pontua patentes; esses itens continuam a cargo do avaliador.

---

## Aplicativo: como usar

1. Baixe `percentil_periodicos.html` e abra em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
2. Não requer instalação, conexão com a internet nem servidor.
3. Funcionalidades: busca por nome ou ISSN, filtros por métrica e quartil, ordenação, cadastro e edição manual de periódicos, importação e exportação em JSON e CSV.

---

## Atualização dos dados

- **SJR:** scimagojr.com → Journal Rankings → categoria Veterinary → Download
- **CiteScore:** scopus.com/sources → Export
- **JCR (uso interno do programa):** InCites, via Portal de Periódicos CAPES → categoria Veterinary Sciences

Os percentis mudam todos os anos. Para credenciamento e APCN, use o mesmo ano-base para todos os docentes e confirme os valores nas fontes originais e no documento de área vigente.

---

## Autoria e citação

**Autora:** Marilda Onghero Taffarel
**Instituição:** Universidade Estadual de Maringá (UEM) — Programa de Pós-Graduação em Produção Sustentável e Saúde Animal (PPS)
**Versão:** 1.1.0 (2026)

> TAFFAREL, M. O. **Percentil: aplicativo e planilha de avaliação para métricas de periódicos científicos na área de Medicina Veterinária**. Versão 1.1.0. Maringá: UEM, 2026. DOI: 10.5281/zenodo.24479784. Disponível em: https://github.com/motaffarel/percentil-periodicos.

---

## Licença

Disponibilizado sob a licença **Creative Commons Attribution 4.0 International (CC BY 4.0)**. Você pode usar, copiar, redistribuir e adaptar para qualquer finalidade, desde que atribua crédito à autora.

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
