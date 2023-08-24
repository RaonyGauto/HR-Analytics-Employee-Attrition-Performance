![IBM HR](https://www.springml.com/wp-content/uploads/2020/08/employee-attrition.png)

# Projeto - Previsão de Rotatividade de Funcionários para Melhorar a Retenção de Talentos

Este projeto visa abordar o desafio de prever e reduzir a rotatividade de funcionários na empresa fictícia "Healthcare Technologies", uma organização de saúde que enfrenta um aumento na saída de colaboradores. Através da análise de dados históricos e a construção de um modelos de classificação de machine learning, nosso objetivo é identificar padrões e fatores que contribuam para a saída de funcionários e, assim, implementar estratégias proativas para melhorar a retenção de talentos e o engajamento dos colaboradores.

# Ferramentas
* Linguagem de programação: [Python](https://www.python.org/)
* IDE: [Colab](https://colab.research.google.com/)
* Ferramentas Estatísticas: Métodos Estatísticos e Análise Exploratória de Dados
* Modelos de Classificação: [Logistic Regression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) e [Random Forest Classifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html)

# Instalação
Este projeto usa as seguintes bibliotecas Python na versão 3.9 do Python:

__pandas, numpy, seaborn, matplotlib.pyplot, sklearn.preprocessing, sklearn.linear_model, sklearn.metrics, sklearn.ensemble, pickle__

Clone este repositório em sua máquina local usando $ git clone https://github.com/RaonyGauto/HR-Analytics-Employee-Attrition-Performance

# Dados:

Os dados utilizados neste projeto foram coletados a partir do site [Kaggle](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset). O dataset contêm informações sobre os funcionários de uma empresa fictícia criados por IBM. O conjunto de dados inclui recursos como a idade, atrito, viagem de neócio, educação, departamento, meio ambiente satisfação, entre outros.

# Análise Exploratória dos Dados
O projeto começa com uma análise exploratória dos dados, onde são verificados os tipos de variáveis, se há presença de valores ausentes, estatísticas descritivas e visualização de distribuições e correlações. Em seguida, são realizadas transformações nos dados, como remover variáveis e codificação de variáveis.

# Preparação dos Dados
Nesta etapa, os dados são preparados para treinamento dos modelos. Isso inclui a seleção de recursos relevantes, divisão dos dados em conjuntos de treinamento e teste, bem como a padronização ou normalização dos recursos, se necessário.

# Treinamento e Avaliação do Modelo
Nesta etapa, dois modelos de classificação são treinados usando o conjunto de dados. Os modelos são avaliados usando as métricas precision_score, recall_score, f1_score, classification_report. Os modelos utilizados foram Regressão Logística e Random Forest Classifier.

# Resultados
Os resultados finais do projeto incluem a avaliação dos modelos e a escolha do modelo com melhor desempenho para ser utilizado pela equipe de RH para prever o desgaste dos funcionários. Também são apresentadas análises sobre algumas variáveis que mais chamaram a atenção, com sugestões de melhorias e além do impacto financeiro de contratações novas e prejuízos com funcionários que saem.

# Contribuição
Este projeto está aberto a contribuições e sugestões. Se você tiver alguma sugestão ou correção a fazer, não hesite em enviar um pull request ou abrir uma issue.
