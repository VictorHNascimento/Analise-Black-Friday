# 📊 Análise Histórica de Black Friday - Zoop MegaStore

## 📌 Sobre o Projeto

Este projeto tem como objetivo analisar o comportamento das vendas da Zoop MegaStore durante os períodos de Black Friday, utilizando SQL para explorar dados históricos e gerar insights que possam apoiar decisões estratégicas para futuras campanhas.
A análise foi desenvolvida simulando um cenário real de negócio, no qual a empresa planeja aumentar seus investimentos na próxima Black Friday e precisa compreender os fatores que mais impactam o desempenho comercial do evento.

---

# 🎯 Objetivo de Negócio

Responder perguntas estratégicas como:
* A Black Friday realmente impulsiona as vendas?
* O crescimento ocorre pelo aumento do ticket médio ou pelo volume de pedidos?
* Quais categorias apresentam maior impacto durante o evento?
* Quais produtos, marcas e fornecedores merecem atenção especial?
* Qual o perfil dos clientes mais relevantes para a campanha?
* Como medir o sucesso das próximas Black Fridays?

---

# 🗂️ Estrutura dos Dados

O projeto utiliza uma base relacional composta pelas seguintes tabelas:

### Clientes

* id_cliente
* nome_cliente
* idade
* endereço

### Vendas

* id_venda
* data_venda
* total_venda
* cliente_id

### Itens_Venda

* venda_id
* produto_id

### Produtos

* id_produto
* nome_produto
* preco
* categoria_id
* marca_id
* fornecedor_id
* data_estoque
* status

### Categorias

* id_categoria
* nome_categoria

### Marcas

* id_marca
* nome

### Fornecedores

* id_fornecedor
* nome
* contato

---

# 🛠️ Ferramentas Utilizadas

* SQL (SQLite)
* Excel
* Python

---

# 📈 Metodologia

A análise foi dividida em cinco etapas:

### 1. Entendimento do Negócio

Definição das perguntas que geram valor para a tomada de decisão.

### 2. Análise Exploratória

Comparação entre:

* Black Friday vs meses normais
* Black Friday ao longo dos anos
* Desempenho por categoria
* Desempenho por fornecedor
* Perfil dos clientes

### 3. Geração de Insights

* Transformação dos resultados em recomendações de negócio.

### 4. Construção das Métricas

Criação de indicadores relacionados a:

* Volume de vendas
* Faturamento
* Ticket médio
* Categorias
* Produtos
* Fornecedores
* Clientes

---

# 📊 Principais Métricas Analisadas

## Volume de Vendas

Comparação entre:

* Vendas realizadas em novembro
* Média de vendas dos demais meses
* Participação da Black Friday no total anual
---

## Ticket Médio

Comparação entre:

* Ticket Médio Black Friday
* Ticket Médio fora da Black Friday
* Ticket Médio anual
---

## Evolução Histórica

Análise de:

* Quantidade de vendas
* Faturamento
* Ticket médio
---

## Categorias

Análise de:

* Quantidade vendida
* Faturamento
* Impacto em relação aos demais meses
---

## Produtos

Identificação de:

* Produtos mais vendidos
* Produtos com maior faturamento
* Produtos críticos para estoque
---

## Marcas

Análise de:

* Volume de vendas
* Receita estimada
---

## Fornecedores

Análise de:

* Volume vendido
* Dependência da Black Friday
* 
---

## Perfil dos Clientes

Segmentação por faixa etária.

---

# 💡 Principais Insights de Negócio

### Insight 1

A Black Friday representa aproximadamente 18% das vendas anuais da empresa.

### Insight 2

O evento gera mais que o dobro do volume esperado para um único mês do calendário.

### Insight 3

O crescimento da Black Friday é impulsionado principalmente pelo aumento do volume de compras.

### Insight 4

As categorias de Eletrônicos, Vestuário e Esportes são as mais estratégicas para campanhas futuras.

### Insight 5

O público entre 25 e 44 anos deve ser priorizado em campanhas de marketing.

---

# 🚀 Recomendações

* Planejar campanhas considerando que novembro gera cerca de 18% das vendas do ano.
* Priorizar categorias de alto faturamento (Eletrônicos e Vestuário), mas sem desconsiderar as demais categorias.
* Criar segmentações para clientes de alto valor e faixas etárias de 25 a 44 anos.
* Definir metas de volume e faturamento com base em 2022 como piso: 3.200 vendas e R$ 9,72 mi de faturamento em novembro, mas sem desconsiderar que o volume e faturamento cresceram menos em comparação a 2020-2021.
* Acompanhar diariamente vendas vs meta, ticket médio, conversão e participação de novembro no acumulado anual.
* Negociar condições com fornecedores-chave antes do pico, principalmente AstroSupply e HorizonDistributors.
* Reforçar compras para produtos de alta saída.
* Priorizar itens com histórico de status vendido e marcas líderes.
* Dimensionar atendimento, separação e logística para um volume mensal aproximadamente 2,4x superior ao de um mês normal.
---

# 📁 Estrutura do Projeto

```text
📦 Analise-Black-Friday
│
├── data/
│   └── base_de_dados.db
│
├── .sql/
│   ├── Analises.sql.sql
│   ├── KPI.sql 
│
├── Relatorio_Black_Friday.pdf
│   
│
└── README.md
```

---

# 📚 Aprendizados

Durante o desenvolvimento deste projeto foram praticados conceitos de:

* SQL Avançado
* CTEs
* Funções de agregação
* Análise Exploratória de Dados (EDA)
* Métricas de Negócio
* Storytelling com Dados
* Geração de Insights para Tomada de Decisão

---

# 👨‍💻 Autor

Victor Hugo do Nascimento

Projeto desenvolvido para fins de estudo e desenvolvimento profissional na área de Análise de Dados.
