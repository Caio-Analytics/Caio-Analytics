# Caio Leão

### Analista de Dados & Analytics Engineer

Construo pipelines de dados de ponta a ponta: da ingestão de arquivo bruto e barulhento até o dashboard que a liderança usa pra decidir. Prefiro dado testado e documentado a dado bonito e frágil, e é por isso que arquitetura em camadas (Bronze, Silver, Gold) e teste automatizado aparecem em tudo que eu construo, corporativo ou pessoal.

📍 Parauapebas, Pará, Brasil &nbsp;·&nbsp; [Portfólio](https://caio-analytics.github.io/Portfolio-Caio-Leao/) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/caio-le)

---

## Projetos

Os dois projetos abaixo são a versão pública, com código aberto, do mesmo tipo de trabalho que faço em produção. Sem dado sintético: os dois rodam sobre arquivo real.

**[Recon](https://github.com/Caio-Analytics/Recon)**
Ferramenta de linha de comando que perfila arquivo de dado antes da análise começar de verdade: infere o que cada coluna representa mesmo com nome abreviado, roda estatística avançada (Shapiro-Wilk, correlação de Pearson/Spearman, ADF e Ljung-Box), cruza tabela pra achar fato e dimensão, detecta e mascara CPF/CNPJ. Só regra determinística, sem modelo de IA. 306 testes automatizados.

**[Bateia](https://github.com/Caio-Analytics/bateia)** &nbsp;·&nbsp; [dashboard ao vivo](https://caio-analytics.github.io/bateia/) &nbsp;·&nbsp; [documentação dbt](https://caio-analytics.github.io/bateia/dbt/)
Pipeline sobre dado público e real da mineração brasileira (ANM). A camada Bronze é Python/Polars, só o trecho que decodifica o CSV do governo; Silver, Gold e o cruzamento entre bases são inteiramente modelos dbt sobre DuckDB, com 58 testes de schema e documentação/linhagem geradas automaticamente. Dashboard publicado como um único HTML autocontido, sem backend.

---

## Impacto na Vale Base Metals

Como Analista de Dados na Planta Salobo, estruturei o ecossistema de dados de RH/Treinamento e Desenvolvimento em camadas (Bronze, Silver, Gold) via Power BI Dataflow, e automatizei a ingestão com Power Automate e SharePoint/Dataverse. Sustento 14+ dashboards oficiais, usados por 300+ pessoas, com redução de 80% no esforço operacional de relatórios que antes eram manuais.

O código é corporativo e não é público, mas os dois projetos acima usam exatamente a mesma abordagem (camadas, teste, documentação) em dado que qualquer um pode conferir.

---

## Stack

| Camada | Ferramentas |
| :--- | :--- |
| Transformação & modelagem | dbt, SQL, DuckDB, Power Query, DAX |
| Linguagens | Python (Polars, Pandas), SQL |
| BI & visualização | Power BI, Figma (prototipagem antes da primeira medida) |
| Automação & plataforma | Power Automate, Power Apps, Microsoft Dataverse, SharePoint |
| Testes & CI | pytest, dbt tests, GitHub Actions |

**Certificações:** SQL, Python para Análise de Dados e Modelagem de Dados (Alura) &nbsp;·&nbsp; Microsoft Power BI (MLF Soluções Tecnológicas) &nbsp;·&nbsp; AWS Data Lake: Pipeline de Ingestão &nbsp;·&nbsp; Metodologias Ágeis

---

## Fora do código

Mangá e RPG. A busca pela estratégia perfeita num sistema de jogo não é tão diferente da busca pela arquitetura certa pra um pipeline de dados.

---

<p align="left">
  <a href="https://caio-analytics.github.io/Portfolio-Caio-Leao/"><img src="https://img.shields.io/badge/Portfólio-1A1408?style=for-the-badge" /></a>
  <a href="https://www.linkedin.com/in/caio-le"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:caiolmnnml@proton.me"><img src="https://img.shields.io/badge/E--mail-8C6C21?style=for-the-badge&logo=protonmail&logoColor=white" /></a>
</p>
