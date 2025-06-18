# 📊 Análise de Vendas - Power BI

Este projeto apresenta um **Dashboard Interativo de Vendas** desenvolvido no **Power BI**, com foco na **análise de desempenho comercial, acompanhamento de metas e geração de insights estratégicos** para apoiar a tomada de decisões.

---

## 🖼️ Visual do Relatório

![Exemplo do Dashboard](relatório.png)

> 🔍 O relatório conta com visualizações intuitivas, KPIs, segmentações dinâmicas e gráficos interativos para análise profunda das vendas.

---

## 🎯 Objetivos do Projeto

O principal objetivo deste projeto é transformar dados brutos de vendas em **informações valiosas e acionáveis**, permitindo que gestores e analistas possam:

- 📈 Avaliar o desempenho por período, produto, região, canal e equipe de vendas;
- 🎯 Acompanhar metas e resultados em tempo real;
- 🔎 Identificar padrões de comportamento e tendências de consumo;
- 💡 Apoiar a gestão comercial e estratégica com indicadores relevantes;
- 🚀 Facilitar a tomada de decisões baseada em dados.

---

## 🧠 Funcionalidades do Relatório

- ✔️ **Filtros e segmentações interativas** (Ano, Mês, Região, Produto, Vendedor, Canal de Vendas);
- ✔️ **KPIs Essenciais**, como:
  - Faturamento
  - Ticket Médio
  - Crescimento vs. período anterior
  - Margem de Lucro
  - Meta x Realizado
- ✔️ **Análises comparativas**: mês a mês, ano a ano, por produto, região ou vendedor;
- ✔️ **Dashboard gerencial** com visão macro e detalhada;
- ✔️ Gráficos de tendência, mapas, barras, pizza, indicadores e cartões;
- ✔️ Alertas visuais para **desvios de metas** e **identificação de oportunidades**.

---

## 🧱 Arquitetura e Modelagem de Dados

- 🔗 Modelagem Estrela (Star Schema), com:
  - `Fato_Vendas` (quantidade, faturamento, custo, lucro, datas, vendedor, etc.)
  - `Dim_Produto`
  - `Dim_Cliente`
  - `Dim_Vendedor`
  - `Dim_Tempo`
  - `Dim_Região` / `Dim_Canal`
- 📊 Transformações via **Power Query (ETL)**;
- 🧠 Cálculos e KPIs desenvolvidos com **DAX**.

---

## 🛠️ Tecnologias e Ferramentas Utilizadas

- [Power BI Desktop](https://powerbi.microsoft.com/)
- Power Query
- DAX (Data Analysis Expressions)
- Modelagem Relacional
- Excel / CSV (como fonte de dados)

---

## ▶️ Como Usar este Projeto

1. Faça o download do arquivo `Analise de Venda.pbix`;
2. Abra no **Power BI Desktop**;
3. Se necessário, atualize os caminhos das fontes de dados:
   - Menu **"Transformar Dados" → "Gerenciar Fontes"**;
4. Clique em **Atualizar** para recarregar os dados;
5. Explore o relatório navegando pelas abas, filtros e segmentações.

> 💡 *Dica:* Para publicação online, utilize o **Power BI Service (cloud)**.

---

## 🚀 Possíveis Evoluções Futuras

- Integração com banco de dados em nuvem (Azure, AWS, SQL Server);
- Criação de alertas automáticos via Power BI Service;
- Previsão de vendas com IA;
- Versão mobile-friendly do dashboard;
- Integração com APIs externas (ERP, CRM).

---

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👤 Autor

**Tiago Fonseca**
