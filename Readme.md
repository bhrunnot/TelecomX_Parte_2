# 📊 Customer Churn Prediction | Machine Learning
## 🚀 Contexto

O churn (cancelamento de clientes) é um dos principais problemas em empresas de telecomunicações, pois afeta diretamente a receita e o crescimento do negócio.

Este projeto utiliza Machine Learning para identificar clientes com maior probabilidade de cancelar o serviço, permitindo que a empresa adote estratégias de retenção baseadas em dados.

## 🎯 Objetivos

Criar um modelo capaz de prever churn

Identificar fatores que influenciam o cancelamento

Construir um pipeline de dados organizado

Transformar resultados técnicos em insights de negócio

## 🛠️ Tecnologias Utilizadas

Python

Pandas

NumPy

Scikit-Learn

Pipeline e ColumnTransformer

Logistic Regression

Random Forest

## 📂 Estrutura do Projeto
```
📦 churn-prediction
 ┣ 📜 churn_model.ipynb
 ┗ 📜 README.md
```
## 🔍 Metodologia
1️⃣ Preparação dos Dados

Conversão da coluna TotalCharges para formato numérico

Tratamento de valores ausentes com SimpleImputer

Separação entre dados de treino e teste

Aplicação de StandardScaler para variáveis numéricas

Uso de One-Hot Encoding para variáveis categóricas

2️⃣ Pipeline de Processamento

O pré-processamento foi organizado dentro de um Pipeline, garantindo:

reprodutibilidade

prevenção de data leakage

facilidade de reutilização do modelo

3️⃣ Treinamento dos Modelos

Foram avaliados dois algoritmos principais:

Logistic Regression

Random Forest

## 📊 Variáveis Mais Importantes

Entre as variáveis com maior influência no churn estão:

Customer Tenure

Total Charges

Monthly Charges

Internet Service (Fiber Optic)

Payment Method (Electronic Check)

Contract Type

## 📈 Principais Insights

🔹 Tempo de permanência

Clientes com pouco tempo de contrato possuem maior probabilidade de cancelamento.

➡ Estratégia: ações de retenção nos primeiros meses.

🔹 Valor da mensalidade

Cobranças mais altas aumentam a chance de churn.

➡ Estratégia: oferecer planos mais flexíveis.

🔹 Tipo de contrato

Contratos de longo prazo apresentam menor taxa de cancelamento.

➡ Estratégia: incentivar planos anuais.

🔹 Método de pagamento

Clientes que utilizam Electronic Check apresentam maior risco de churn.

➡ Estratégia: incentivar pagamento automático.

## 📉 Avaliação do Modelo

O desempenho foi avaliado utilizando:

Accuracy

Precision

Recall

F1-score

Confusion Matrix

## 💡 Impacto para o Negócio

Com esse modelo é possível:

identificar clientes com maior risco de cancelamento

direcionar campanhas de retenção

reduzir custos de aquisição de clientes

melhorar previsibilidade de receita

## ⚡ Possíveis Melhorias

Cross-validation

Ajuste de hiperparâmetros

Teste com XGBoost ou LightGBM

Interpretabilidade com SHAP

Deploy do modelo via API

## 👨‍💻 Autor

Bruno Trindade
