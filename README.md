# 📊 Análise de Performance de Estudantes

## 📝 Sobre o Projeto
O objetivo principal desta análise é identificar e compreender os fatores que influenciam o desempenho acadêmico dos estudantes. Através de técnicas de **Análise Exploratória de Dados (EDA)**, o projeto investiga como variáveis demográficas e socioeconômicas impactam as notas em matemática, leitura e escrita.

Este projeto também possui um caráter experimental, realizando um **estudo comparativo entre bibliotecas de visualização** (Matplotlib, Seaborn e Plotly) para identificar qual oferece a melhor estética e densidade de informação.



[Image of data analysis workflow diagram]


## 📂 O Dataset
O conjunto de dados utilizado possui **5.000 registros** e foca em 7 variáveis principais:
* **Gênero:** Público feminino e masculino.
* **Grupo Étnico:** Classificação em grupos de A a E.
* **Escolaridade dos Pais:** Nível de instrução dos responsáveis (desde ensino médio até mestrado).
* **Almoço:** Tipo de alimentação (padrão ou lanche reduzido).
* **Curso Preparatório:** Se o aluno completou ou não curso para o teste.
* **Notas:** Desempenho em Matemática, Leitura e Escrita.

## 🛠️ Tecnologias Utilizadas
O projeto foi desenvolvido em Python, utilizando as seguintes bibliotecas:
* **Pandas & Numpy:** Manipulação e tratamento de dados.
* **Matplotlib & Seaborn:** Visualizações estatísticas estáticas.
* **Plotly:** Gráficos interativos e dinâmicos.

## 🔍 Etapas da Análise
1.  **Tratamento de Dados:** Tradução sistemática das colunas e categorias para o português, visando clareza e padronização.
2.  **Verificação de Integridade:** Confirmação de ausência de valores nulos e tipagem correta das variáveis.
3.  **Análise Demográfica:** Exploração da distribuição dos estudantes por gênero, etnia e nível de instrução familiar.
4.  **Visualização Comparativa:** Criação de gráficos de pizza e distribuições utilizando diferentes ferramentas visuais.

## 📈 Principais Insights
* **Distribuição por Gênero:** A base apresenta um equilíbrio demográfico, com uma leve predominância feminina (52,2%).
* **Instrução dos Pais:** Apenas uma minoria (12,8%) dos responsáveis possui apenas o nível médio completo, com a maioria apresentando formação acadêmica ou técnica.
* **Etnia:** O grupo B é o mais representativo (29,74%), seguido pelo grupo C (27,52%).

## 🚀 Como Executar
1. Clone este repositório.
2. Certifique-se de ter o Python instalado.
3. Instale as dependências:
   ```bash
   pip install pandas numpy matplotlib seaborn plotly openpyxl