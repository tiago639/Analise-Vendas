# 📊 Análise de Vendas - Power BI

Este projeto apresenta um **Dashboard Interativo de Vendas** desenvolvido no **Power BI**, com foco em **análise de desempenho comercial, acompanhamento de metas e geração de insights estratégicos** para apoiar a tomada de decisões.

---

## 🖼️ Visual do Relatório

![Exemplo do Dashboard](relatório.png)

> 🔍 O relatório conta com visualizações intuitivas, KPIs, segmentações dinâmicas e gráficos interativos para análise profunda das vendas.

---

## 🎯 Objetivo do Projeto

O principal objetivo deste projeto é transformar dados brutos de vendas em **informações valiosas e acionáveis**, permitindo que gestores e analistas possam:

- 📈 **Avaliar o desempenho** por período, produto, região, canal e equipe de vendas.
- 🎯 **Acompanhar metas e resultados em tempo real.**
- 🔎 **Identificar padrões de comportamento e tendências de consumo.**
- 💡 **Apoiar a gestão comercial e estratégica** por meio de indicadores relevantes.
- 🚀 **Facilitar a tomada de decisão rápida e baseada em dados.**

---

## 🧠 Principais Funcionalidades do Relatório

- ✔️ **Filtros e segmentações interativas** (Ano, Mês, Região, Produto, Vendedor, Canal de Vendas, etc.).
- ✔️ **KPIs Essenciais**, como:
  - Faturamento
  - Ticket Médio
  - Crescimento vs. Período Anterior
  - Margem de Lucro
  - Meta x Realizado
- ✔️ **Análise Comparativa:** mês a mês, ano a ano, por produto, região ou vendedor.
- ✔️ **Dashboard Gerencial** com visão macro e detalhada.
- ✔️ **Gráficos de Tendência, Mapas, Barras, Pizza, Indicadores e Cartões.**
- ✔️ Alertas visuais para **desvios de metas** e **análise de oportunidades.**

---

## 🔗 Arquitetura e Modelagem de Dados

- 🔗 Modelagem Estrela (Star Schema):
  - **Fato_Vendas** (quantidade, faturamento, custo, lucro, data, vendedor, etc.)
  - **Dim_Produto**
  - **Dim_Cliente**
  - **Dim_Vendedor**
  - **Dim_Tempo**
  - **Dim_Região / Dim_Canal**

- 📊 Dados tratados e transformados via **Power Query**.
- 🧠 Cálculos desenvolvidos com **DAX** para KPIs, análises temporais e métricas avançadas.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- [**Power BI Desktop**](https://powerbi.microsoft.com/)
- **Power Query** (ETL)
- **DAX (Data Analysis Expressions)**
- **Modelagem de Dados Relacional**
- **Excel / CSV** como fonte de dados (ou outra conforme necessidade)

---

## ▶️ Como Usar este Projeto

1. Faça o download do arquivo **`Analise de Venda.pbix`**.
2. Abra no **Power BI Desktop**.
3. Caso apareça erro de fonte de dados, atualize os caminhos:
   - Menu **"Transformar Dados" → "Gerenciar Fontes"**.
4. Clique em **Atualizar** para carregar os dados.
5. Explore o relatório através das abas, filtros e segmentações.

> 💡 *Dica:* Caso queira publicar na web ou compartilhar, pode usar o **Power BI Service (cloud)**.

---

## 🚀 Possíveis Evoluções Futuras

- Integração com banco de dados em nuvem (Azure, AWS, SQL Server, etc.).
- Criação de alertas automáticos via Power BI Service.
- Aplicação de IA para previsão de vendas.
- Desenvolvimento de relatórios mobile-friendly.
- Conexão com APIs externas (ERP, CRM).

---
## 📄 Licença

Este projeto está sob a licença **MIT** – veja o arquivo [LICENSE](LICENSE) para mais detalhes
## 👤 Autor

- **Tiago Fonseca **

---
## 💬 Contribuições e Feedbacks

Fique à vontade para abrir um **Issue** ou um **Pull Request** caso tenha sugestões, melhorias ou queira colaborar! 🚀
