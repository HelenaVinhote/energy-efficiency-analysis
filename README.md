# Previsão da Carga Térmica de Aquecimento de Edifícios

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
  
</p>

## Sobre o projeto

Este projeto tem como objetivo analisar a relação entre as características físicas de edifícios e sua necessidade de aquecimento, utilizando conceitos de Probabilidade e Estatística e técnicas de Aprendizado de Máquina.

A análise utiliza o algoritmo de **Regressão Linear Simples** para investigar a relação entre a altura total de uma edificação e sua carga térmica de aquecimento, buscando estimar valores a partir dos dados disponíveis.

## Base de dados

Foi utilizado o conjunto de dados **Energy Efficiency**, disponibilizado pelo UCI Machine Learning Repository.

A base apresenta informações sobre características construtivas de edifícios e suas respectivas cargas térmicas.

**Características do conjunto de dados:**

- 768 observações;
- 10 variáveis;
- 8 variáveis de entrada;
- 2 variáveis de saída.

Fonte: [UCI Machine Learning Repository – Energy Efficiency](https://archive.ics.uci.edu/dataset/242/energy+efficiency)

## Variáveis utilizadas

Para a implementação da Regressão Linear Simples, foram selecionadas duas variáveis:

| Variável | Descrição | Função |
|---|---|---|
| X5 | Altura total do edifício | Variável independente |
| Y1 | Carga térmica de aquecimento | Variável dependente |

## Metodologia

O desenvolvimento do projeto foi dividido nas seguintes etapas:

1. **Importação dos dados:** obtenção do conjunto de dados Energy Efficiency.
2. **Análise exploratória:** investigação da distribuição da carga térmica e das correlações entre as variáveis.
3. **Seleção das variáveis:** escolha da altura total (X5) e da carga térmica de aquecimento (Y1).
4. **Divisão dos dados:** separação em conjuntos de treinamento (80%) e teste (20%).
5. **Implementação do modelo:** aplicação da Regressão Linear Simples utilizando Scikit-learn.
6. **Avaliação:** análise do desempenho do modelo por meio de métricas estatísticas.

## Tecnologias e ferramentas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- UCI Machine Learning Repository

## Resultados e análise

Nesta seção são apresentados os resultados obtidos durante a implementação do modelo, incluindo:

- Equação estimada da reta de regressão;
- Gráfico de dispersão e reta de regressão;
- Comparação entre valores reais e previstos;
- Análise dos resíduos;
- Avaliação do modelo utilizando as métricas MAE, RMSE e R².

Os resultados permitem analisar a capacidade do modelo de representar a relação entre as variáveis selecionadas e estimar a carga térmica de aquecimento dos edifícios.

## Autores

Projeto desenvolvido em colaboração como atividade acadêmica da disciplina de Probabilidade e Estatística.

- [Estefane Tainá Pallaro](https://github.com/estefanepallaro)
- [Gustavo Augusto Guimarães de Azevedo](https://github.com/gustavoguimaraes1)
- [Helena Vinhote Dias](https://github.com/HelenaDias)

## Contexto acadêmico

Trabalho desenvolvido com o propósito de aplicar conceitos estatísticos na análise de dados e compreender a utilização da Regressão Linear Simples em problemas relacionados à eficiência energética de edificações.