📊 Projeto Power BI – Análise de Metas

📌 Sobre o Projeto

Este projeto tem como objetivo analisar e acompanhar o desempenho de metas ao longo dos anos de,
utilizando o Power BI para transformar dados brutos em insights visuais e estratégicos.

A proposta é criar um dashboard interativo que permita identificar tendências, comparar resultados e apoiar a tomada de decisão.

🎯 Objetivos
Consolidar dados de diferentes anos em um único modelo
Comparar metas vs resultados
Identificar padrões de crescimento ou queda
Criar indicadores de desempenho (KPIs)
Desenvolver um dashboard intuitivo e interativo
📂 Estrutura dos Dados

Os dados utilizados estão organizados em arquivos Excel:

4_1_meta_2017.xlsx
4_1_meta_2018.xlsx
4_1_meta_2019.xlsx

🔹 Possíveis campos (exemplo)
Ano
Mês
Meta
Resultado Real
Diferença (Meta x Real)
Percentual de atingimento

⚙️ Ferramentas Utilizadas
Power BI Desktop
Excel (como fonte de dados)
Power Query (tratamento de dados)
DAX (criação de medidas e KPIs)

🔄 ETL (Tratamento dos Dados)

Etapas realizadas no Power Query:

Importação dos arquivos Excel
Padronização de colunas
Criação de coluna de Ano
União das tabelas (Append)
Tratamento de valores nulos
Tipagem correta dos dados

📈 Modelagem de Dados
Tabela fato: Metas
Possível tabela dimensão: Calendário
Relacionamentos baseados em data/ano

🧮 Medidas DAX (exemplos)
Total Meta = SUM(Metas[Meta])

Total Realizado = SUM(Metas[Realizado])

Atingimento (%) = 
DIVIDE([Total Realizado], [Total Meta], 0)

Diferença = 
[Total Realizado] - [Total Meta]
📊 Dashboard

O dashboard contará com:

📌 Cartões (KPIs)
Total Meta
Total Realizado
% de Atingimento

📈 Gráficos
Linha (evolução ao longo do tempo)
Barras (comparação por período)
Colunas (Meta vs Real)

🎛️ Filtros (Slicers)
Ano
Mês

💡 Insights Esperados
Identificar períodos com melhor desempenho
Detectar desvios de metas
Apoiar decisões estratégicas
Visualizar evolução ao longo dos anos

🚀 Possíveis Melhorias Futuras
Inserir previsão (forecast)
Criar análise por região ou categoria
Automatizar atualização de dados
Publicar no Power BI Service
Criar versão mobile do dashboard

📌 Status do Projeto
🚧 Em desenvolvimento

👨‍💻 Autor
Projeto desenvolvido por Daniel Francisco Sabino Rocha

