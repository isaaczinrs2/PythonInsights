# 📊 Python Insights - Cancelamento de Clientes

Este projeto faz parte de um case prático de análise de dados utilizando Python, desenvolvido durante um intensivo da Hashtag Programação.

## 🧠 Descrição

A empresa contratante, com uma base de mais de **800 mil clientes**, identificou que a **maioria dos seus clientes se tornaram inativos**, ou seja, cancelaram o serviço. Com isso, o objetivo do projeto foi **entender os principais motivos de cancelamento** e propor **ações estratégicas para reduzir o churn (cancelamento)**.

---

## 🎯 Objetivos

- Analisar a base de dados de clientes para entender o comportamento dos cancelamentos;
- Identificar os fatores mais relevantes que levam os clientes a cancelarem o serviço;
- Simular estratégias de retenção de clientes e observar o impacto nos resultados.

---

## 🧰 Tecnologias Utilizadas

- **Python**
- **Pandas** (tratamento e análise de dados)
- **Plotly Express** (visualização de dados interativa)
- **Jupyter Notebook** (ambiente de execução)

---

## 📝 Etapas do Projeto

### 1. Importação da Base de Dados
Foi utilizado o arquivo `cancelamentos_sample.csv`, contendo os dados dos clientes e informações como idade, tempo como cliente, assinatura, frequência de uso, entre outros.

### 2. Limpeza e Tratamento de Dados
- Exclusão da coluna `CustomerID`, irrelevante para a análise;
- Verificação e remoção de dados nulos com `dropna()`.

### 3. Análise Inicial
- Verificação do total e da porcentagem de clientes que cancelaram o serviço:
  - **56,79%** dos clientes cancelaram.
  - **43,21%** dos clientes permaneceram ativos.

### 4. Análise de Causas do Cancelamento
Foram criados **gráficos interativos** para analisar a influência de cada variável no cancelamento. Os principais insights foram:

#### 📌 Principais Motivos de Cancelamento:
- Clientes que **ligaram mais de 4 vezes para o call center** têm alta taxa de cancelamento.
- Clientes com **mais de 20 dias de atraso** no pagamento **sempre cancelam**.
- Todos os clientes com **contrato mensal** **cancelaram** o serviço.

---

## 🔁 Estratégias Simuladas

Com base nos insights, foram aplicadas regras para simular melhorias:

- **Limitar a 4 o número de ligações ao call center** (criar alerta ao atingir 3 ligações).
- **Monitorar atrasos acima de 10 dias** (alerta para cobrança preventiva).
- **Incentivar contratos mais longos** com promoções ou descontos (evitar planos mensais).

### 📉 Resultado da Simulação:

Após aplicar essas medidas, a **taxa de cancelamento caiu de 56,79% para apenas 18,35%**, mostrando a **eficácia das ações simuladas**.

---

## 👨‍💻 Autor

**Isaac de Castro Amorim**  
Estudante de Informática | ETEC Bartolomeu Bueno da Silva Anhanguera  
[LinkedIn](https://www.linkedin.com/in/isaac-amorim-1646ab265)

---

## 📌 Observações

Este projeto simula uma análise de dados realista e é um ótimo exemplo do impacto que **decisões orientadas por dados** podem gerar nos resultados de uma empresa.

