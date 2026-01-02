# TeleconX_BR_DanielLima
Programa ALURA + ONE em Ciências de Dados
# 📊 Telecom X: Análise de Evasão de Clientes (Churn)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-444876?style=for-the-badge&logo=python&logoColor=white)

## 📝 Sobre o Projeto
Este projeto faz parte de um **Desafio de Data Science da Alura**, onde o objetivo foi atuar como Assistente de Dados na empresa **Telecom X**. A missão principal foi investigar as causas do alto índice de cancelamento de clientes (Churn) e fornecer diagnósticos precisos para a equipe de estratégia.

O projeto percorre desde a coleta de dados brutos em formato JSON até a entrega de um relatório com recomendações práticas para a diretoria.



---

## 🛠️ Ferramentas e Tecnologias
* **Linguagem:** Python 3.x
* **Bibliotecas de Dados:** Pandas e NumPy
* **Visualização:** Matplotlib e Seaborn
* **Manipulação de JSON:** Requests e Json_normalize
* **Processamento de Texto:** Regex (Expressões Regulares)

---

## 📈 Etapas do Processo de Dados

### 1. Limpeza e Tratamento (ETL)
Os dados originais possuíam estruturas aninhadas e prefixos desnecessários.
* **Normalização:** Conversão de JSON complexo para DataFrame tabular.
* **Regex:** Limpeza em massa dos nomes das colunas para melhor legibilidade.
* **Tratamento de Nulos:** Identificação de strings vazias e remoção de registros sem a variável alvo (Churn).
* **Mapeamento:** Transformação de variáveis numéricas em categóricas para análise qualitativa.

### 2. Análise Exploratória (EDA)
Exploração visual focada em entender as diferenças comportamentais entre clientes que saem e clientes que ficam.



[Image of churn analysis dashboard]


---

## 💡 Principais Insights e Recomendações

### **O que os dados revelaram:**
* **Barreira de Preço:** Clientes com faturas mensais acima de **R$ 70,00** têm uma propensão muito maior ao cancelamento.
* **Serviços Críticos:** A ausência de suporte prioritário e segurança online aumenta a insegurança e o abandono.
* **Período de Risco:** A maior parte das desistências ocorre nos **primeiros 3 meses** de contrato.

### **Sugestões Estratégicas:**
1. **Fidelização:** Criar planos anuais com descontos progressivos para reduzir o abandono dos contratos mensais.
2. **Valor Agregado:** Incluir serviços de segurança nos planos de Fibra Óptica para aumentar a percepção de custo-benefício.
3. **Migração de Pagamento:** Oferecer benefícios para quem utiliza cartão de crédito ou débito automático, reduzindo o atrito do cheque eletrônico.

---

## 🚀 Como Executar
1. Clone este repositório.
2. Certifique-se de ter as bibliotecas `pandas`, `seaborn` e `requests` instaladas.
3. Execute o script principal ou abra o arquivo `.ipynb` no **Google Colab**.

---
**Desenvolvido por Daniel Marques Lima** 🚀 *Conecte-se comigo no https://www.linkedin.com/in/daniel-m-lima/*
