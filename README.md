# Análise de Mercado: Oportunidade de Investimento em Restaurantes

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-7db0ea?style=for-the-badge)

## 📌 Visão Geral do Projeto
Este projeto é uma análise de mercado desenvolvida para identificar a melhor oportunidade de investimento para a abertura de um novo restaurante. O estudo analisa os dados de mais de 9.600 estabelecimentos comerciais para avaliar a densidade comercial, localização em ruas específicas e o comportamento de redes locais.

## 🎯 Objetivos de Negócio
* **Identificação de Oportunidades:** Descobrir o melhor nicho de atuação e o tamanho ideal (capacidade de assentos) para um novo empreendimento gastronómico.
* **Análise de Localização e Concorrência:** Mapear ruas com boa movimentação comercial, equilibrando o alto fluxo de potenciais clientes com um nível aceitável de concorrência direta.
* **Recomendação Estratégica:** Fundamentar a decisão de investimento com dados concretos sobre a proporção de grandes redes de restaurantes versus estabelecimentos independentes no mercado atual.

## 🛠️ Stack Técnica
* **Linguagem:** Python
* **Manipulação de Dados:** Pandas, NumPy
* **Visualização de Dados:** Matplotlib, Seaborn, Plotly Express, Plotly Graph Objects
* **Estatística:** Scipy

## 📉 Metodologia e Processamento
1. **Coleta e Limpeza de Dados:** Importação do conjunto de dados (`rest_data_us_upd.csv`) contendo informações de morada, tipo de estabelecimento e categorização de redes, seguida do tratamento dos tipos de dados.
2. **Análise Exploratória (EDA):** Investigação da distribuição dos diferentes tipos de estabelecimentos (Pizzarias, Cafés, Fast Food, etc.) e análise da proporção de restaurantes de rede no mercado.
3. **Análise de Localização Geográfica:** Mapeamento das vias com maior concentração de restaurantes, avaliando a densidade comercial de artérias importantes (ex: Hollywood Blvd, Sunset Blvd, Santa Monica Blvd).
4. **Análise de Capacidade:** Estudo da distribuição do número de assentos por tipo de estabelecimento para definir o porte ideal que minimize riscos e maximize a taxa de ocupação.

## 🏆 Resultados e Conclusões
* **Tipo de Negócio Recomendado:** A análise demonstrou que a abertura de uma **pizzaria** representa a melhor oportunidade, por ser um modelo de negócio com menor saturação geral, independentemente de ser uma rede ou não.
* **Porte do Estabelecimento:** O tamanho ideal sugerido para o novo negócio é de aproximadamente **40 a 45 assentos**.
* **Localização Estratégica:** A rua recomendada para a instalação foi a **Santa Monica BLVD**. Esta via apresenta um bom volume de comércios, o que sugere excelente movimentação de público, mas não é a rua com a maior concentração do mercado, o que se traduz em menor concorrência direta para uma nova pizzaria.
* **Apresentação Executiva:** Os resultados consolidados foram transformados numa [apresentação executiva para investidores](https://drive.google.com/file/d/1RX_3RnwQSNtTFh0Aminm-Hx1J8Lmf-3n/view?usp=sharing).

---

### 📂 Estrutura do Repositório
* `projeto10.ipynb`: Notebook Jupyter contendo todas as etapas de limpeza de dados, análise exploratória e conclusões.
* `dataframes/`: Pasta contendo a base de dados bruta `rest_data_us_upd.csv`.

---
**João Pedro Vidotto Tavares Dias** *Data Analyst | Análise de Mercado | Especialista em Vendas* [LinkedIn](https://www.linkedin.com/in/joao-vidotto/) | [GitHub](https://github.com/jpvidotto)
