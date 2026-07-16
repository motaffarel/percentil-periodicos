# Percentil — Catálogo de Métricas de Periódicos Científicos

**Aplicativo para consulta e gerenciamento de métricas bibliométricas de periódicos científicos, desenvolvido para apoiar processos de credenciamento docente em programas de pós-graduação stricto sensu na área de Medicina Veterinária.**

---

## Sobre o aplicativo

O **Percentil** é uma ferramenta web autossuficiente (arquivo HTML único, sem instalação, sem servidor) que consolida em uma única interface as principais métricas utilizadas pela CAPES para avaliação de periódicos científicos:

| Métrica | Fonte | Descrição |
|---|---|---|
| **JCR Percentil** | Clarivate / Web of Science | Posição percentual do periódico na categoria do JCR |
| **SJR Percentil** | SCImago Journal Rank | Percentil calculado a partir do ranking SJR por área |
| **SJR Quartil** | SCImago Journal Rank | Classificação Q1–Q4 na categoria |
| **CiteScore Percentil** | Scopus / Elsevier | Percentil "Highest percentile" exportado diretamente da Scopus |
| **h5-index** | Google Scholar Metrics | Índice h baseado em artigos publicados nos últimos 5 anos |

A base de dados atual inclui **379 periódicos** da área de Medicina Veterinária e áreas correlatas (Zootecnia, Ciência Animal, Reprodução Animal, Equinos, dentre outras), com dados importados das planilhas oficiais do SCImago (2025), Scopus CiteScore (2025) e JCR/InCites (2025).

---

## Funcionalidades

- **Busca** por nome do periódico ou ISSN
- **Filtros combinados** por métrica, valor mínimo e quartil SJR
- **Ordenação** por nome ou por qualquer uma das métricas (maior para menor)
- **Visualização** com barras de percentil e marcação do limiar 50%
- **Cadastro e edição manual** de novos periódicos via formulário
- **Importação** de base em formato JSON (para atualização em lote)
- **Exportação** em JSON (para backup e compartilhamento) e CSV (para uso em planilhas)

---

## Como usar

1. Faça o download do arquivo `percentil_periodicos.html`
2. Abra-o em qualquer navegador moderno (Chrome, Firefox, Edge, Safari)
3. Não requer instalação, conexão com internet ou servidor

Para **atualizar a base de dados** com novos periódicos ou versões mais recentes das planilhas:
- Baixe a planilha atualizada do SCImago (scimagojr.com → Journal Rankings → categoria Veterinary → Download)
- Baixe a planilha do CiteScore (scopus.com/sources → Export)
- Baixe a planilha do JCR (InCites via Portal de Periódicos CAPES → categoria Veterinary Sciences → Export)
- Use a função **Importar JSON** para mesclar novos dados com sua base existente

---

## Contexto de uso

Este aplicativo foi desenvolvido para atender à recomendação da CAPES de utilizar o percentil JCR, SJR e CiteScore — além do h5-index do Google Scholar Metrics — como base para avaliação e credenciamento de docentes em programas de pós-graduação stricto sensu na área de Medicina Veterinária.

O aplicativo é disponibilizado gratuitamente para uso por quaisquer programas de pós-graduação, coordenadores, docentes e pesquisadores.

---

## Dados e fontes

Os dados bibliométricos utilizados nesta versão foram obtidos das seguintes fontes públicas e institucionais:

- **SCImago Journal Rank 2025** — scimagojr.com (acesso público gratuito)
- **Scopus CiteScore 2025** — scopus.com/sources (acesso público gratuito)
- **JCR 2025** — Clarivate InCites, via Portal de Periódicos CAPES (acesso institucional)
- **Google Scholar Metrics 2026** — scholar.google.com/citations?view_op=top_venues (acesso público gratuito)

> **Importante:** os dados do JCR são de acesso institucional (Clarivate/Web of Science) e estão aqui registrados como resultado de consulta realizada pela autora por meio do Portal de Periódicos CAPES. Para fins de credenciamento, recomenda-se sempre confirmar os valores diretamente nas fontes originais, verificando o critério vigente no documento de área e edital de credenciamento do programa.

---

## Autoria e citação

**Autora:** Marilda Onghero Taffarel  
**Instituição:** Universidade Estadual de Maringá (UEM) — Hospital Veterinário / Programa de Pós-Graduação em Ciências Veterinárias  
**Ano:** 2026  

Para citar este software:

> TAFFAREL, M. O. **Percentil: aplicativo para consulta de métricas de periódicos científicos na área de Medicina Veterinária**. Maringá: UEM, 2026. Disponível em: [URL do repositório]. Acesso em: [data].

---

## Licença

Este software é disponibilizado sob a licença **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

Você pode usar, copiar, redistribuir e adaptar este software para qualquer finalidade, inclusive comercial, desde que atribua crédito à autora original.

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)
