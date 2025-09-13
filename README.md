# Analise-imigrantes-canada

Este projeto realiza uma análise exploratória dos dados de imigração para o Canadá entre 1980 e 2013, com foco nos países da América do Sul. Foram utilizados diferentes tipos de visualizações para entender o comportamento das migrações ao longo do tempo.

---

## Objetivos

- Explorar os dados de imigração para o Canadá.  
- Analisar padrões específicos de países da América do Sul (Brasil, Argentina, Colômbia e Peru).  
- Comparar a evolução da imigração entre diferentes países.  
- Utilizar técnicas de visualização para destacar tendências e insights.  

---

## Estrutura do Projeto

| Arquivo | Descrição |
|---------|-----------|
| `notebook.ipynb` | Notebook principal com toda a análise (limpeza, exploração e visualizações). |
| `imigrantes_canada.csv` | Base de dados utilizada no estudo. |
| `Imigração_america_sul.html` | Gráfico interativo gerado com Plotly (linha temporal da América do Sul). |

---

## Tecnologias & Bibliotecas

- Python  
- Pandas – Manipulação e limpeza de dados  
- Matplotlib – Visualizações estáticas  
- Seaborn – Gráficos mais estilizados  
- Plotly Express – Visualizações interativas  
- Google Colab – Ambiente de execução  

---

## Metodologia

1. Carregamento dos dados (`imigrantes_canada.csv`).  
2. Exploração inicial: informações básicas, colunas, países, períodos.  
3. Criação de subconjuntos: análise específica de Brasil, Argentina, Peru e Colômbia.  
4. Visualizações:
   - Séries temporais da imigração por país.  
   - Comparação entre Brasil e Argentina.  
   - Gráficos de linha, boxplots e subplots combinados.  
   - Gráfico de barras horizontais destacando o Brasil na América do Sul.  
   - Top 10 países com maior imigração para o Canadá (1980–2013).  
   - Gráficos interativos com Plotly.  
5. Exportação: geração de um HTML interativo com a imigração dos países da América do Sul.  

---

## Principais Insights

- O Brasil apresentou crescimento constante de imigrantes ao longo dos anos, com picos na década de 2000.  
- A Argentina teve variações mais irregulares, mas também um aumento notável em determinados períodos.  
- Colômbia e Peru aparecem entre os maiores emissores de imigrantes da América do Sul.  
- Entre 1980 e 2013, os 10 países com maior imigração para o Canadá incluem nações fora da América do Sul, com destaque para fluxos muito superiores aos latinos.  

---

## Dados

- Fonte: Conjunto de dados de imigração disponibilizado em formato CSV.  
- Período analisado: 1980 a 2013.  
- Variáveis principais:  
  - País de origem  
  - Ano  
  - Número de imigrantes  

---

## Exemplos de Visualizações

- Imigração do Brasil para o Canadá (linha temporal).  
- Comparação Brasil x Argentina.  
- Boxplot para distribuição anual da imigração.  
- Top 10 países em imigração para o Canadá.  
- Gráficos interativos em HTML para América do Sul.  

---

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/MariarpSaraiva/Analise-imigrantes-canada.git
