## Descrição do Projeto

Este projeto utiliza Python e suas bibliotecas de ciência de dados para analisar dados fornecidos pelo **DETRAN** (Departamento Estadual de Trânsito). O foco principal do projeto é explorar e compreender os padrões nos dados relacionados a veículos, motoristas, infrações e possíveis tendências observadas ao longo do tempo.

A análise tem como objetivo auxiliar na compreensão de comportamentos que possam influenciar políticas públicas, segurança no trânsito, campanhas educativas e o próprio planejamento estratégico do DETRAN.

## Funcionalidades Principais

- **Análise Exploratória de Dados (EDA)**: O projeto começa com uma exploração detalhada dos dados do DETRAN, buscando entender a distribuição, tendências e anomalias.
- **Visualização de Dados**: Criação de gráficos e visualizações interativas para apresentar os dados de maneira intuitiva.
- **Modelo Preditivo**: Implementação de um modelo que pode prever comportamentos ou resultados com base em atributos fornecidos no dataset.
- **Relatórios de Infrações**: Identificação das infrações mais comuns, comportamento de infrações por tipo de veículo, localidade e tempo.
- **Tendências de Registro de Veículos**: Análise do crescimento ou declínio de registros de veículos em diferentes períodos e regiões.

## Estrutura do Projeto

### 1. **Importação de Bibliotecas e Carregamento dos Dados**
   - Bibliotecas como Pandas, Matplotlib, Seaborn e Scikit-learn são utilizadas para a análise e modelagem de dados.
   - Leitura dos dados do DETRAN e tratamento de dados ausentes ou inconsistentes.

### 2. **Análise Exploratória de Dados (EDA)**
   - **Distribuição de Veículos**: Análise do número de veículos por tipo, região e ano de registro.
   - **Infrações de Trânsito**: Identificação das infrações mais frequentes, analisando comportamento de motoristas, tipos de infração e locais com maior incidência.
   - **Correlação de Dados**: Identificação de correlações entre variáveis importantes como idade do motorista, tipo de veículo e frequência de infrações.

### 3. **Modelos Preditivos**
   - **Classificação e Regressão**: Implementação de modelos de machine learning para prever infrações com base em variáveis como tipo de veículo, idade do motorista e local.
   - **Métricas de Avaliação**: Acurácia, precisão, recall e F1-score foram utilizadas para avaliar a performance dos modelos.

### 4. **Visualizações Interativas**
   - Gráficos de barras, histogramas e heatmaps para apresentar a distribuição e correlação dos dados.
   - Mapas interativos para visualizar as infrações por região e identificar áreas críticas.

### 5. **Conclusões e Insights**
   - Síntese dos principais insights extraídos dos dados, como padrões comportamentais de motoristas, locais com maior número de infrações e tendências no registro de veículos.

## Requisitos

### Dependências
- **Python 3.x**
- **Jupyter Notebook**
- Bibliotecas:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Base de Dados

O projeto utiliza uma base de dados fornecida pelo **DETRAN** contendo informações sobre:
- **Veículos**: Tipo de veículo, ano de registro, região.
- **Motoristas**: Idade, região, número de infrações.
- **Infrações**: Tipo de infração, localização, data.

Os dados foram pré-processados e limpos para garantir a integridade das análises.

## Principais Perguntas Respondidas

- Quais tipos de infração são mais comuns e em quais regiões?
- Existe correlação entre a idade do motorista e o número de infrações?
- Quais tipos de veículos são mais suscetíveis a cometer infrações?
- Qual o crescimento no número de registros de veículos ao longo dos anos?

## Resultados Esperados

- **Identificação de padrões de infrações**: Quais regiões e perfis de motoristas tendem a cometer mais infrações.
- **Previsões de comportamentos**: Modelos que podem ajudar a prever futuras infrações com base em dados históricos.
- **Visualizações claras e intuitivas**: Gráficos e mapas interativos para comunicar os resultados de forma visual e acessível.

  
## Autor

**Vitor Hugo Muniz de Sousa Santos**

Engenheiro de Computação | Cientista de Dados

[vitormunnizzdev@gmail.com](mailto:vitormunnizzdev@gmail.com)
[www.linkedin.com/in/vitormunnizz](https://www.linkedin.com/in/vitormunnizz)

## Licença

Este projeto está licenciado sob a **MIT License**.
Sinta-se livre para usar e modificar conforme necessário, mantendo os créditos ao autor.

**Se este projeto te ajudou, deixe uma estrela no repositório!**
