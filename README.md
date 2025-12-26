# 🧠 Pré-modelagem: Projeto de Credit Score – Processamento dos Dados

Este projeto faz parte do Módulo Correlação, Balanceamento, Variáveis Categóricas - A Terceira etapa Pré Modelagem do curso de Cientista de Dados da EBAC e corresponde à primeira etapa do desenvolvimento de um modelo de Credit Score. O objetivo é aplicar técnicas de pré-processamento e preparação dos dados, garantindo que a base esteja adequada para o treinamento de modelos de Machine Learning.

O credit score é uma pontuação que representa o risco de inadimplência de um indivíduo. Modelos desse tipo são essenciais para instituições financeiras, pois apoiam decisões sobre concessão de crédito, limites e condições de financiamento.

## 🧩 Etapas Desenvolvidas

**1. Análise inicial dos dados:** compreensão das variáveis demográficas, financeiras e comportamentais dos clientes..

**2. Tratamento de dados:** correção de tipos de variáveis, tratamento de valores ausentes e padronização dos dados.

**3. Codificação de variáveis categóricas:** aplicação de técnicas como One-Hot Encoding e Label Encoding, conforme a necessidade de cada variável e da etapa de modelagem.

**4. Separação da base:** divisão dos dados em conjuntos de treino e teste, garantindo uma avaliação adequada do modelo.

**5. Balanceamento do target:** aplicação do SMOTE exclusivamente na base de treino para corrigir o desbalanceamento da variável Score de Crédito.

**6. Etapa de treinamento (Preparação):** com a base de treino balanceada e tratada, os dados ficam prontos para a etapa de treinamento dos modelos de Machine Learning, reduzindo vieses e melhorando a capacidade de generalização.

## 📊 Resultados e Insights

- Foi identificado um forte desbalanceamento entre as classes de Score de Crédito.

- Após a aplicação do SMOTE, as classes passaram a ter distribuição equilibrada (Baixo, Médio e Alto com a mesma quantidade de registros).

- Esse balanceamento é fundamental para garantir um treinamento mais justo e previsões mais confiáveis.

## ✅ Conclusão

Esta etapa evidencia a importância do pré-processamento e preparação dos dados antes do treinamento. A correta limpeza, codificação, balanceamento e separação da base são essenciais para o desenvolvimento de modelos de Credit Score mais robustos, precisos e alinhados às necessidades do negócio.
