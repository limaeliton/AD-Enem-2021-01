# Análise Exploratória de Dados - ENEM 2021

![Análise de Dados](images/analysis_banner.png)

Este repositório contém um notebook Jupyter que realiza uma análise exploratória de dados (EDA) do ENEM 2021 com o objetivo de identificar padrões, relações e possíveis insights.

---

## Estrutura do Projeto

### Arquivos no Repositório
- **`analise.ipynb`**: Notebook principal contendo o código Python e as etapas de análise.
- **Dataset**: Presume-se que o conjunto de dados está armazenado em um arquivo CSV.

### Conteúdo do Notebook

1. **Importação de Bibliotecas:**
   - Utiliza bibliotecas como `pandas`, `numpy`, `matplotlib` e `seaborn` para manipulação e visualização de dados.

2. **Leitura dos Dados:**
   - Carrega o conjunto de dados no notebook e exibe uma visão geral inicial.

3. **Limpeza e Tratamento de Dados:**
   - Identificação de valores nulos e outliers.
   - Conversão de tipos de dados quando necessário.

4. **Análise Exploratória:**
   - Análise descritiva com estatísticas como média, mediana e desvio-padrão.
   - Visualizações como histogramas, gráficos de dispersão, boxplots e gráficos de correlação (heatmap).

5. **Resultados e Insights:**
   - Identificação de padrões nos dados e sugestões de áreas para investigações futuras.

6. **Exportação de Resultados:**
   - Salva tabelas e visualizações como arquivos para documentação posterior.

---

## Como Utilizar

1. **Requisitos**
   - Certifique-se de ter Python 3.x instalado.
   - Instale as bibliotecas necessárias:
     ```bash
     pip install pandas numpy matplotlib seaborn
     ```

2. **Execução do Notebook**
   - Abra o arquivo `analise.ipynb` em um ambiente Jupyter (local ou online, como Google Colab).
   - Substitua o caminho do dataset no notebook pelo caminho do seu arquivo.
   - Execute as células para visualizar os resultados.

3. **Personalização**
   - Ajuste parâmetros do código para explorar diferentes aspectos dos dados.

---

## Exemplos de Saída

### Estatísticas Resumidas
| Variável      | Média | Mediana | Desvio-Padrão |
| --------------|-------|---------|---------------|
| Exemplo A     | 10.5  | 10.0    | 2.3           |
| Exemplo B     | 23.1  | 22.5    | 5.1           |

![Gráfico de Dispersão](images/scatter_plot.png)

### Visualizações
- Histogramas
- Gráficos de dispersão
- Boxplots
- Heatmaps de correlação

---

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorar este projeto.


