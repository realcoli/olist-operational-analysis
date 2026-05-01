# 📊 Análise Operacional de Pedidos e Entregas — Olist Dataset

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/12EJqpVnDTMaJ2UDV3VxwMqg1_k1JCHaw?usp=sharing)

---

## 🎯 Objetivo

Este projeto tem como objetivo analisar dados operacionais de um marketplace brasileiro utilizando o dataset público da Olist.

A proposta é simular desafios reais enfrentados por empresas como iFood, explorando métricas essenciais relacionadas a demanda, logística e eficiência operacional.

---

## 🧠 Problema de Negócio

Plataformas de e-commerce e delivery precisam entender padrões de consumo e gargalos logísticos para garantir uma boa experiência ao cliente e otimizar custos.

Este projeto busca responder:

- Em quais horários ocorrem mais pedidos?
- Quais regiões apresentam maior tempo de entrega?
- Existem entregas com atrasos fora do padrão?
- O valor do frete acompanha a distância logística?

---

## 📁 Dataset

- Fonte: Brazilian E-Commerce Public Dataset by Olist (Kaggle)
- Dados incluem informações sobre pedidos, clientes, vendedores, itens e geolocalização

---

## 🛠️ Tecnologias Utilizadas

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy  

---

## 🔍 Etapas da Análise

1. Carregamento e entendimento dos dados  
2. Tratamento e filtragem de pedidos entregues  
3. Análise de volume de pedidos por horário  
4. Cálculo do tempo médio de entrega por estado  
5. Identificação de outliers utilizando Z-score  
6. Estimativa de distância entre vendedor e cliente  
7. Análise da relação entre frete e distância  
8. Geração de insights de negócio  

---

## 📊 Principais Insights

### ⏰ Padrão de Demanda

A demanda apresenta crescimento ao longo do dia, com forte concentração entre 10h e 22h, indicando comportamento de consumo concentrado no período ativo.

### 🚚 Desigualdade Logística Regional

Estados das regiões Norte e Nordeste apresentam maiores tempos médios de entrega, sugerindo desafios logísticos relacionados à distância e infraestrutura.

### ⚠️ Impacto dos Outliers

Embora a maior parte das entregas ocorra dentro do padrão esperado, existem casos de atrasos extremos que podem impactar negativamente a experiência do cliente.

### 📦 Frete e Distância

A distância influencia o valor do frete, porém não de forma linear, indicando que outros fatores também impactam o custo logístico.

---

## 📈 Conclusão

A análise demonstra como dados operacionais podem ser utilizados para identificar padrões de comportamento, gargalos logísticos e oportunidades de otimização.

Os insights gerados permitem apoiar decisões estratégicas voltadas à melhoria da eficiência operacional e da experiência do cliente.

---

## 🚀 Aplicações Práticas

- Ajuste de capacidade operacional em horários de pico  
- Otimização de prazos de entrega por região  
- Monitoramento de entregas fora do padrão  
- Revisão de estratégias de precificação de frete  
- Apoio à tomada de decisão baseada em dados  

---

## 🔮 Próximos Passos

- Construção de modelo preditivo para atraso de entregas  
- Análise do impacto do tempo de entrega na satisfação do cliente  
- Segmentação de performance logística por região  
- Criação de dashboards interativos  
- Análise de fatores adicionais no custo de frete (peso, categoria, etc.)  


