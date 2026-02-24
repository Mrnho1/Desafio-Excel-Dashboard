# 🎮 Dashboard de Vendas – GameSphere Studios

## 📌 Sobre o Projeto

Este projeto consiste na criação de um Dashboard de Vendas no Excel, desenvolvido para simular um cenário real de análise de dados em uma empresa do setor de jogos digitais.

A empresa fictícia **GameSphere Studios** comercializa jogos, DLCs e assinaturas para PC, Console e Mobile, atuando em diferentes regiões do mundo.

O objetivo do dashboard é transformar dados brutos em informações visuais estratégicas, permitindo análise de desempenho e apoio à tomada de decisão.

---

## 🎯 Objetivo do Projeto

Criar um dashboard executivo capaz de responder perguntas estratégicas de negócio como:

- 💰 Qual o faturamento total?
- 📈 Qual o lucro total?
- 📦 Qual a quantidade total vendida?
- 🧾 Qual o total de pedidos realizados?
- 🎮 Quais são os Top 5 jogos mais vendidos?
- 🏆 Quais jogos geram mais lucro?
- 🌎 Existe região com alta venda mas baixa margem?
- 💳 Qual método de pagamento é mais utilizado?
- 📊 Qual categoria vende mais?

---

## 🗂 Base de Dados

A base de dados foi estruturada com informações de vendas contendo:

- ID do Pedido  
- Data  
- Região  
- País  
- Plataforma (PC, Console, Mobile)  
- Categoria (RPG, FPS, Esporte, Aventura, Assinatura)  
- Produto  
- Tipo de Produto  
- Quantidade  
- Preço Unitário  
- Custo Unitário  
- Método de Pagamento  

Foram criadas colunas calculadas para:

- Receita = Quantidade × Preço Unitário  
- Custo Total = Quantidade × Custo Unitário  
- Lucro = Receita − Custo Total  
- Margem = Lucro ÷ Receita  

---

## 📊 Indicadores Criados (KPIs)

O dashboard apresenta os seguintes indicadores principais:

- Receita Total
- Lucro Total
- Quantidade Total Vendida
- Total de Pedidos

Esses KPIs permitem uma visão executiva imediata do desempenho da empresa.

---

## 📈 Análises Desenvolvidas

### 🔹 Top 5 Jogos Mais Vendidos
Identificação dos produtos com maior volume de vendas.

### 🔹 Jogos Que Geram Mais Lucro
Análise de rentabilidade por produto, destacando que nem sempre o mais vendido é o mais lucrativo.

### 🔹 Lucro por Região
Comparação de desempenho geográfico, permitindo identificar regiões com:

- Alta receita
- Alta margem
- Alto volume, mas menor rentabilidade

### 🔹 Método de Pagamento
Análise do comportamento do consumidor e preferência de pagamento.

### 🔹 Vendas por Plataforma
Comparação entre PC, Console e Mobile para apoiar decisões estratégicas.

---

## 🛠 Ferramentas Utilizadas

- Microsoft Excel
- Tabelas Dinâmicas
- Gráficos Dinâmicos
- Segmentação de Dados (Slicers)
- Fórmulas e colunas calculadas
- Organização visual orientada a dashboard executivo

---

## 🧠 Principais Insights Obtidos

- Alguns produtos possuem alto volume de vendas, mas margem inferior.
- Determinadas regiões apresentam boa receita, porém menor rentabilidade.
- Console representa a maior participação no faturamento total.
- Cartão de Crédito é o método de pagamento mais utilizado.

---

## 📷 Estrutura do Dashboard

O dashboard foi estruturado com:

- Cards de indicadores no topo
- Gráficos comparativos
- Visual limpo e executivo
- Filtro por período (segmentação mensal)

---

## 📁 Estrutura do Repositório
