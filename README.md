
### Link do repositório: https://www.kaggle.com/datasets/parisrohan/credit-score-classification

* **Dicionário de dados:** Uma descrição detalhada de cada coluna (feature) presente no dataset.
* **Explicação do dataset:** Uma breve descrição do que o dataset representa e qual o seu objetivo.
* **Estratégia usando a variável credit_scoring:** Uma explicação sucinta de como a variável "credit_scoring" será utilizada no projeto.

**Considerações:**

* **Dicionário de dados:** É crucial para entender o significado de cada coluna e como elas se relacionam entre si.
* **Explicação do dataset:** Ajuda a contextualizar o problema e o objetivo da análise.
* **Estratégia para credit_scoring:** É fundamental para entender como essa variável será utilizada como alvo (target) ou como preditor (feature) na modelagem.

## **Proposta de Conteúdo para o README**

**Observação:** O conteúdo a seguir é uma proposta geral e pode ser adaptada de acordo com as especificidades do seu projeto. Recomenda-se consultar a documentação original do dataset para obter informações mais precisas.

### **README.md**

#### **Dicionário de Dados**

| Coluna | Descrição | Tipo de Dado |
|---|---|---|
| ID | Identificador único para cada registro | Numérico |
| Customer_ID | Identificador único do cliente | Categórico |
| Month | Mês da observação | Categórico |
| Name | Nome do cliente | Categórico |
| Age | Idade do cliente | Numérico |
| SSN | Número de Seguro Social | Categórico |
| Occupation | Ocupação do cliente | Categórico |
| Annual_Income | Renda anual do cliente | Numérico |
| Monthly_Inhand_Salary | Salário líquido mensal do cliente | Numérico |
| Num_Bank_Accounts | Número de contas bancárias | Numérico |
| Credit_Mix | Mistura de crédito (ex: boa, ruim) | Categórico |
| Outstanding_Debt | Dívida pendente | Numérico |
| Credit_Utilization_Ratio | Taxa de utilização do crédito | Numérico |
| Credit_History_Age | Idade do histórico de crédito | Categórico |
| Payment_of_Min_Amount | Pagamento do valor mínimo da fatura | Binário |
| Total_EMI_per_month | Prestação mensal total | Numérico |
| Amount_invested_monthly | Valor investido mensalmente | Numérico |
| Payment_Behaviour | Comportamento de pagamento | Categórico |
| Monthly_Balance | Saldo mensal | Numérico |
| Credit_Score | Pontuação de crédito | Numérico |


#### **Descrição do Dataset**

O dataset "credit_score-classification" do Kaggle contém informações detalhadas sobre clientes, incluindo dados demográficos, financeiros e de comportamento de crédito. O objetivo principal deste dataset é construir um modelo de machine learning capaz de prever a pontuação de crédito de um indivíduo com base em suas características. 

#### **Estratégia Utilizando a Variável `credit_score`**

A variável `credit_score` será utilizada como a **variável alvo** (target variable) em nosso modelo de machine learning. Isso significa que o modelo será treinado para prever o valor da pontuação de crédito para um novo cliente, com base nos valores das outras variáveis (features).


* **Regressão:** Se o objetivo for prever um valor numérico preciso para a pontuação de crédito, utilizaremos algoritmos de regressão como Regressão Linear, Random Forest Regressor ou XGBoost Regressor.
* **Classificação:** Se o objetivo for classificar os clientes em diferentes faixas de pontuação de crédito (ex: baixa, média, alta), utilizaremos algoritmos de classificação como Árvore de Decisão, Random Forest Classifier ou XGBoost Classifier.


