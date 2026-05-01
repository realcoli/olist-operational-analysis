# 📊 Análise Operacional de Pedidos e Entregas — Olist Dataset

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
