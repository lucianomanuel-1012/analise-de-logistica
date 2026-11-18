# 📦 Análise de Dados de Logística | Dashboard em Power BI

Dashboard desenvolvido em **Power BI** para ajudar uma empresa de logística a compreender como está o processo de entrega dos seus produtos. O projeto parte de um trabalho anterior com problemas e erros evidentes, que foi refeito de raiz: dados tratados, modelo organizado e KPIs calculados com DAX.

## 🎯 Objetivo

Fornecer uma visão clara e fiável do desempenho das entregas, permitindo à gestão identificar atrasos, avaliar equipas e canais e acompanhar a evolução ao longo do tempo.

## 📊 KPIs desenvolvidos

| # | KPI | Visual utilizado |
|---|-----|------------------|
| 1 | Total de Entregas no Prazo por Canal de Entrega | Gráfico de área |
| 2 | Percentual de Entregas Antecipadas por Equipa de Entrega | Gráfico de barras horizontais |
| 3 | Total de Entregas por Mês | Gráfico de linhas |
| 4 | Total de Entregas de Produtos dos Top 5 Vendedores | Tabela (filtro Top N) |
| 5 | Total de Entregas com Atraso por Cidade | Tabela |
| 6 | Percentual de Entregas por Status de Entrega | Gráfico de colunas |

Além dos seis KPIs, o dashboard apresenta dois cartões de resumo: **Total de Entregas** (cerca de 54 mil) e **Total de Entregas no Prazo** (cerca de 47 mil).

## 🛠️ Ferramentas

- **Microsoft Excel**: fonte dos dados (planilha)
- **Power BI Desktop**: modelação e visualização
- **Power Query**: limpeza e transformação dos dados
- **DAX**: criação das medidas e cálculos

## 🔄 Processo de desenvolvimento

1. **Exploração dos dados**: análise das colunas, tipos de dados, nulos e duplicados.
2. **Tratamento no Power Query**: correção de tipos, padronização de textos e limpeza de inconsistências.
3. **Modelação**: relacionamentos entre as tabelas e criação de uma tabela de datas para a análise mensal.
4. **Medidas em DAX**: uma medida por KPI (contagens, percentuais e filtros de Top N).
5. **Visualização**: construção dos gráficos, definição de paleta de cores e títulos claros.
6. **Validação**: conferência dos totais do dashboard com os dados originais.


## 📌 Principais conclusões

- A grande maioria das entregas é feita **dentro do prazo ou antecipadamente**, com uma parcela menor de atrasos.
- O volume de entregas de **fevereiro a agosto** mantém-se estável, com queda acentuada em **setembro** e recuperação parcial nos meses seguintes.
- Poucos canais concentram a maior parte das entregas no prazo, com destaque para o **Canal07**.

## 👤 Autor

**Luciano Manuel Ferreira**
[LinkedIn]www.linkedin.com/in/lucianomanuelferreira · [GitHub]https://github.com/lucianomanuel-1012

---

⭐ Se este projeto lhe foi útil, deixe uma estrela no repositório!
