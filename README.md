# 🏎️ Dashboard Executivo de Vendas Porsche Brasil

> **Projeto desenvolvido por Jean Dael Edouard para a comunidade e desafios da DIO (Digital Innovation One).**

Uma solução analítica de alta performance e interface luxuosa voltada para a gestão executiva de vendas da **Porsche Brasil**. Este dashboard interativo foi construído para transformar dados operacionais em insights estratégicos em tempo real, mantendo a identidade visual elegante e refinada da marca oficial da Porsche.

---

## 🔗 Link de Acesso ao Dashboard

Clique no link abaixo para visualizar a aplicação interativa publicada via **GitHub Pages**:

👉 **[Acessar Dashboard Porsche Brasil](https://jeandaedouard1009-eng.github.io/dashboard-vendas-porsche/)**

---

## 📌 Funcionalidades Principais

* **Interface Responsiva & Tema Porsche:** UI/UX inspirada no portal oficial da Porsche Brasil, combinando os tons *Carmine Red (`#D5001C`)*, *Dark Carbon* e componentes interativos avançados.
* **Filtros Dinâmicos em Tempo Real:**
  * 🚘 Modelo do Veículo (Porsche Model)
  * 📅 Ano do Modelo (Model Year)
  * 🏙️ Cidade de Destino (City)
  * 💳 Método de Pagamento (Pay Method)
* **Visualização Analítica Interativa:** Gráficos desenvolvidos em **Chart.js** responsivos com *tooltips* detalhados em BRL (R$).

---

## 📊 Respostas às Perguntas de Negócio (KPIs)

O dashboard responde de forma dinâmica às 5 principais perguntas do conselho executivo:

1. **Modelos mais vendidos por cidade:** Identificação dos modelos com maior volume de entregas e aceitação regional.
2. **Ano de modelo mais vendido no período:** Análise de distribuição por ano de fabricação/modelo dos carros comercializados.
3. **Insights de popularidade urbana:** Análise dos modelos *bestsellers* e tendências de demanda específica por cidade.
4. **Faturamento total por modelo de carro:** Ranking de receita gerada por cada linha de produto (ex: *911*, *Taycan*, *Cayenne*, *Macan*, *718*).
5. **Análise Combinada de Quilometragem e Métodos de Pagamento:** Média de quilometragem percorrida (veículos novos vs. seminovos) e distribuição das modalidades financeiras preferidas pelos clientes.

---

## 🛠️ Tecnologias Utilizadas

* **Frontend / UI:** HTML5, CSS3 (Modern Flexbox/Grid, Glassmorphism, CSS Variables), JavaScript (ES6+ Vanilla).
* **Data Visualization:** [Chart.js](https://www.chartjs.org/) (Bar Charts, Doughnut Charts, Dual-Axis Composite Charts).
* **Base de Dados:** Excel Sanitizado (`porsche_database_sanitizada.xlsx`) integrado diretamente ao client-side para resposta instantânea.
* **Hospedagem:** GitHub Pages.

---

## 📂 Estrutura do Repositório

```text
dashboard-vendas-porsche/
│
├── index.html                       # Aplicação principal (Dashboard interativo em HTML/CSS/JS)
└── porsche_database_sanitizada.xlsx  # Base de dados original utilizada
