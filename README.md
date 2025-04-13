# Análise Preditiva de Inadimplência de Clientes

Este projeto tem como objetivo desenvolver um modelo preditivo para identificar clientes inadimplentes em uma fintech, utilizando técnicas de aprendizado de máquina. A análise é realizada com base em variáveis socioeconômicas, de crédito e comportamentais dos clientes. O modelo desenvolvido visa otimizar o processo de concessão de crédito, ajudando a fintech a reduzir a inadimplência e melhorar a assertividade nas decisões.

## Objetivos

- Realizar uma análise exploratória da base de dados para entender as variáveis que influenciam a inadimplência.
- Aplicar técnicas de pré-processamento para preparar os dados para modelagem.
- Construir e comparar diferentes modelos de aprendizado de máquina para prever a inadimplência.
- Otimizar o modelo XGBoost para alcançar a melhor performance preditiva.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para análise de dados e desenvolvimento do modelo preditivo.
- **Pandas**: Biblioteca para manipulação de dados.
- **Scikit-learn**: Biblioteca de aprendizado de máquina para desenvolvimento e avaliação dos modelos.
- **XGBoost**: Algoritmo de boosting utilizado para construir o modelo preditivo.
- **Matplotlib/Seaborn**: Bibliotecas para visualização de dados.
- **Google Colab**: Ambiente de desenvolvimento utilizado para este projeto.

## Descrição do Projeto

### Etapas do Processo:

1. **Análise Exploratória de Dados**: 
   - Análise das variáveis presentes na base de dados para identificar padrões e entender a relação com a inadimplência.
   - Cálculo do Information Value (IV) para medir a importância das variáveis na previsão da inadimplência.

2. **Pré-processamento de Dados**:
   - Normalização dos dados.
   - Utilização de técnicas como Dummy Encoding para transformar variáveis categóricas em variáveis numéricas.
   - Tratamento de dados desbalanceados utilizando a técnica de *resampling*.

3. **Modelagem**:
   - Desenvolvimento e comparação de diferentes modelos de aprendizado de máquina, como:
     - **Random Forest**
     - **Árvore de Decisão**
     - **Regressão Logística**
     - **XGBoost**
   - Avaliação dos modelos utilizando métricas como Acurácia, Precisão, Recall e AUC.

4. **Otimização do Modelo**:
   - Ajustes no modelo XGBoost para melhorar a performance, utilizando o *resampling* e outras técnicas de tuning.
   - Resultados finais e métricas de avaliação, como:
     - Acurácia: 0.7980
     - Precisão: 0.6310
     - Recall: 0.7867
     - AUC: 0.8233
