📊 Análise do IDEB 2023 – Amazonas
Projeto de análise e modelagem usando Machine Learning para identificar escolas com eficiência acima da média no estado do Amazonas.

👨‍💻 Autor
Keven Gomes

📁 Arquivos do Repositório
Este repositório contém apenas dois arquivos, como solicitado:

analise_completa.ipynb → Notebook com todo o código, gráficos, modelos e análises (K‑Means, XGBoost, projeções etc.)
README.md → Este arquivo, explicando o projeto de forma clara e objetiva
🎯 Objetivo do Projeto
Responder à pergunta:

“Quais escolas do Amazonas apresentam eficiência de gestão acima da média estatística prevista pela IA?”

Para isso, o notebook aplica:

📌 Clusterização (K‑Means)
Segmentação das escolas em três perfis:
🔴 Crítico • 🟡 Em Desenvolvimento • 🟢 Alta Performance

📌 Predição (XGBoost)
Estima a nota esperada para cada escola e calcula o quanto ela supera (ou não) a previsão.

📌 Projeção Temporal
Utiliza regressão linear para prever a tendência do IDEB estadual para 2024–2025.

📊 Dataset
Fonte oficial: Portal do INEP
https://www.gov.br/inep/pt-br/areas-de-atuacao/pesquisas-estatisticas-e-indicadores/ideb/resultados
Escopo: Escolas de Ensino Médio do Amazonas
Tamanho: ~600 linhas × 15 colunas
Variáveis principais:
Taxa de aprovação
Nota SAEB (Matemática / Língua Portuguesa)
Nota IDEB
Município
Dependência administrativa
O dataset não está incluído no repositório por ser público e disponibilizado diretamente pelo INEP.

🚀 Como Executar
Baixe o notebook analise_completa.ipynb
Abra no Google Colab (recomendado)
Faça o upload da base do IDEB 2023
Execute as células do início ao fim
📈 Principais Resultados
As escolas foram organizadas em 3 clusters de desempenho
O XGBoost permitiu identificar as unidades que superam a expectativa de forma estatisticamente relevante
A projeção indica tendência de crescimento moderado para o IDEB em 2024–2025
📌 Licença
Este projeto é de uso acadêmico e demonstrativo.
