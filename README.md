# 📊 Análise Operacional de Pedidos e Entregas — Olist Dataset

🔗 [Abrir no Google Colab](https://colab.research.google.com/drive/12EJqpVnDTMaJ2UDV3VxwMqg1_k1JCHaw?usp=sharing)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](SEU_LINK_AQUI)

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

---

## 📌 Sobre o Projeto

Este projeto foi desenvolvido com foco em demonstrar habilidades em:

- Análise exploratória de dados (EDA)  
- Manipulação e transformação de dados com Pandas  
- Visualização de dados  
- Interpretação de métricas operacionais  
- Geração de insights de negócio  

---

## 🎯 Objetivo

Este projeto analisa dados operacionais de um marketplace brasileiro utilizando o dataset público da Olist.

O objetivo é investigar métricas relevantes para empresas de e-commerce, marketplace e delivery, como volume de pedidos, tempo de entrega, atrasos extremos e relação entre frete e distância.

## 🧠 Problema de Negócio

Empresas digitais que operam com pedidos e entregas precisam monitorar constantemente sua eficiência logística.

Este projeto busca responder:

- Quais são os horários de pico de pedidos?
- Quais estados apresentam maior tempo médio de entrega?
- Existem entregas com atrasos muito fora do padrão?
- O valor do frete acompanha a distância entre vendedor e cliente?

## 📁 Dataset

Brazilian E-Commerce Public Dataset by Olist — Kaggle.

## 🛠️ Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## 🔍 Etapas da Análise

1. Carregamento dos dados
2. Tratamento de pedidos entregues
3. Análise de horários de pico
4. Cálculo do tempo médio de entrega por estado
5. Identificação de outliers com Z-score
6. Cálculo de distância estimada entre vendedor e cliente
7. Análise da relação entre frete e distância
8. Geração de insights de negócio

## 📊 Principais Insights

### ⏰ Horários de Pico

O volume de pedidos se concentra principalmente entre o período da tarde e da noite, sugerindo maior atividade dos consumidores fora do início do expediente.

### 🚚 Tempo de Entrega por Estado

Foram observadas diferenças relevantes no tempo médio de entrega entre os estados, indicando possíveis desafios logísticos regionais.

### ⚠️ Outliers de Entrega

Foram identificadas entregas com tempo muito acima do padrão da operação utilizando Z-score absoluto maior que 3.

### 📦 Frete vs Distância

A distância influencia o valor do frete, mas não explica sozinha toda a variação observada. Outros fatores, como peso, categoria, região e estratégia comercial, também podem impactar o custo logístico.

## ✅ Conclusão

A análise demonstra como dados operacionais podem apoiar decisões estratégicas em empresas de marketplace, e-commerce e delivery.

Os resultados podem ser usados para melhorar previsão de demanda, reduzir atrasos, identificar gargalos logísticos e otimizar custos de entrega.

## 🔮 Próximos Passos

- Criar modelo preditivo para prever atrasos
- Analisar impacto do tempo de entrega na avaliação do cliente
- Criar dashboard interativo
- Investigar regiões com maior incidência de outliers
- Avaliar relação entre frete, distância, peso e categoria do produto
