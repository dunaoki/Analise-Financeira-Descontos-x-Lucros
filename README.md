# Analise Financeira Descontos x Lucros

> Dashboard interativo desenvolvido para analisar como as políticas de desconto impactam as vendas e lucros da empresa ao longo do tempo.
> 

---

### ✅ **Resumo do Projeto**

📌 **Objetivo**: Analisar o impacto dos descontos no volume de vendas e no lucro.

📊 **Ferramenta do Dashboard**: Power BI

📁 **Dados**: Base fictícia tirado do kaggle

🕒 **Período de Análise**: 2011 a 2014

🔧 **Ferramentas usadas**: CVS,  Power BI , Python 

---

### 🧠 **1. Entendimento do Problema**

> Pergunta principal:
> 
> 
> Como os descontos afetam o desempenho financeiro da empresa?
> 
- Os maiores descontos realmente trazem mais lucro?
- Existe uma sazonalidade ideal para campanhas promocionais?
- Todos os segmentos se comportam da mesma forma?

---

### 🗂️ **2. Coleta e Extração de Dados**

🛠️ Fontes de dados: arquivos em CSV (.CSV)

[Fonte:](https://www.notion.so/Fonte-1eb4a17cfd55800bb9c5cd166c84dc55?pvs=21)

🔍 Métodos de extração: Python / Pandas 

📌 *Etapas executadas:*

- Importação do arquivo de vendas
- Conversão de datas e separação por ano/trimestre
- Limpeza de dados nulos e inconsistentes

---

### 🧹 **3. Limpeza e Tratamento dos Dados**

[✅ Tipagem correta das colunas](https://www.notion.so/Tipagem-correta-das-colunas-1eb4a17cfd5580419f53d5a403f6cfe5?pvs=21)

[✅ Remoção de linhas duplicadas](https://www.notion.so/Remo-o-de-linhas-duplicadas-1eb4a17cfd5580de8225e19af3c7fd67?pvs=21)

📅 Ano, Mês, Trimestre

📉 Margem de Lucro

🎯 % de Desconto

---

### 📊 **4. Análise Exploratória dos Dados**

[Evolução das vendas por trimestre (2013 e 2014 em destaque)](https://www.notion.so/Evolu-o-das-vendas-por-trimestre-2013-e-2014-em-destaque-1e94a17cfd5580609e4af080da452c57?pvs=21)

[Descontos aplicados x Periodo](https://www.notion.so/Descontos-aplicados-x-Periodo-1e94a17cfd5580f99c93ddf2cb01da3b?pvs=21)

[Relação entre Descontos, Lucro e Unidades Vendidas (Gráfico de Dispersão)](https://www.notion.so/Rela-o-entre-Descontos-Lucro-e-Unidades-Vendidas-Gr-fico-de-Dispers-o-1e94a17cfd5580ce8e79ef46e71d648e?pvs=21)

[KPIs com filtros](https://www.notion.so/KPIs-com-filtros-1e94a17cfd55805984dcdcc57fa1be2d?pvs=21)

---

### 📌 **5. Principais Insights**

💡Meses com maior desconto não necessariamente refletem maior lucratividade, o que sugere a necessidade de reavaliar as estratégias de precificação.

💡 **Descontos altos ≠ lucro alto**

💡 **Segmentos como “Enterprise” responderam melhor aos descontos**

💡 **Há uma tendência de crescimento geral nas vendas**

💡O crescimento das vendas ao longo dos anos reforça a importância de um planejamento estratégico contínuo.

---

### 📈 **6. Visualização no Dashboard (Power BI)**

📍 Métricas visuais:

- **Cards com KPIs**: Unidades Vendidas, Venda Bruta, Lucro, Total de Descontos
- **Gráfico de Linha**: Venda Bruta por Trimestre
- **Gráfico de Colunas**: Descontos por Mês/Ano
- **Gráfico de Dispersão**: Desconto x Lucro por Segmento

![Captura de Tela 2025-05-04 às 15.25.17.png](attachment:738b587c-2c9a-4e49-a213-5af26f89ea37:Captura_de_Tela_2025-05-04_as_15.25.17.png)

---

### 🧩 **7. Conclusão**

✔️ Estratégias de desconto devem ser ajustadas conforme o segmento

✔️ Planejamento estratégico anual é fundamental

✔️ Campanhas sazonais nem sempre trazem o retorno esperado

---

### 🧰 **Ferramentas Utilizadas**

| Etapa | Ferramenta |
| --- | --- |
| Extração e Limpeza | Python |
| EDA | Python |
| Dashboard | Power BI |
| Documentação | Notion / GitHub |

---

### 📁 **Links Importantes**

[🔗 **Dashboard Interativo no Power BI**](https://www.notion.so/Dashboard-Interativo-no-Power-BI-1e94a17cfd55808ea5bcffafa7cfe440?pvs=21)

- 💻 **Repositório no GitHub**
