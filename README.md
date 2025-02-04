# Predição de Diabetes com Machine Learning

Este repositório contém um projeto de análise exploratória e modelagem preditiva para diagnóstico de diabetes. O objetivo principal é explorar os dados, identificar padrões e criar um modelo de aprendizado de máquina capaz de prever o diagnóstico com base em características clínicas dos pacientes.

## 👤 Autor

Pedro Gabriel Fonseca

## 📄 Descrição do Projeto

O projeto utiliza uma abordagem de aprendizado supervisionado para prever o diagnóstico de diabetes com base em variáveis como níveis de glicose, IMC, pressão arterial, idade, entre outras características médicas.

## 🔧 Ferramentas Utilizadas

- **Linguagem: Python***
- **Bibliotecas:**

  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `plotly (plotly.express)`
  - `scikit-learn (model_selection, preprocessing, metrics, ensemble, neighbors, svm, tree, neural_network)`
## 📊 Etapas do Projeto

1️⃣ **Coleta e Limpeza dos Dados**
  - O conjunto de dados foi carregado e limpo, garantindo a integridade das informações.
  - Remoção de valores inconsistentes e tratamento de outliers usando o algoritmo Local Outlier Factor (LOF).
2️⃣ **Análise Exploratória de Dados (EDA)**
  - Visualizações com matplotlib, seaborn e plotly para analisar distribuições e correlações.
  - Geração de mapas de calor, histogramas e gráficos de dispersão para entender melhor os padrões dos dados.
3️⃣ **Predição com Machine Learning**
  - Implementação e comparação de vários modelos, incluindo:
  - Regressão Logística
  - K-Nearest Neighbors (KNN)
  - Support Vector Machine (SVM)
  - Árvores de Decisão
  - Random Forest
  - Gradient Boosting
  - Redes Neurais Artificiais (MLPClassifier)
  - Avaliação dos modelos com métricas como acurácia, recall, F1-score e matriz de confusão.

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/pedrogabrielf/diabetes_analyzes.git
2. Navegue até o diretório do projeto:
   ```bash
    cd predicao-diabetes
3. Instale as dependências necessárias:
   ```bash
    pip install -r requirements.txt
4. Execute o notebook para visualizar as análises e predições:
5. Abra o arquivo analysis.ipynb e rode todas as células.

## 📂 Estrutura do Repositório

    predicao-diabetes/
    │
    ├── datasets/               # Conjunto de dados utilizado
    ├── analysis.ipynb          # Notebook com as análises e predições
    ├── README.md               # Instruções e descrição do projeto
    └── requirements.txt        # Dependências necessárias

## 📝 Licença

Este projeto é para fins educacionais e está disponível sob a licença MIT.
Sinta-se à vontade para contribuir e melhorar a análise! 🚀
