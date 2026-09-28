# 🏎️ Porsche Brasil | Executive Intelligence Dashboard

Dashboard de desempenho comercial desenvolvido com base na análise e higienização de dados de vendas de veículos Porsche. O projeto foi concebido com foco em um design **Dark Theme Premium**, alinhado à identidade visual oficial da Porsche.

## 📊 Perguntas de Negócio Escolhidas e Justificativa

1. **Desempenho de Receita por Modelo:**
   - *Por quê:* Identificar quais linhas de veículos (*911, Cayenne, Taycan, etc.*) geram maior faturamento bruto e sustentam a margem de receita da marca.
2. **Eficiência da Equipe de Vendas:**
   - *Por quê:* Avaliar o volume financeiro fechado por cada consultor/vendedor para otimizar comissões e metas comerciais.
3. **Distribuição Geográfica de Mercado:**
   - *Por quê:* Mapear quais estados e regiões concentram a maior concentração de clientes e poder de compra.
4. **Acompanhamento Operacional e Logístico:**
   - *Por quê:* Monitorar o status das entregues (*Delivered, In Transit, Pending*) para garantir eficiência e reduzir gargalos logísticos.
5. **Preferências Financeiras por Modalidade de Pagamento:**
   - *Por quê:* Entender o comportamento de compra dos clientes em relação aos métodos de pagamento utilizados (*Wire Transfer, Financing, Cash, etc.*).

---

## 🛠️ Evolução do Prompt e Construção

- **Prompt Inicial:** Focado apenas em listar os filtros básicos e KPIs textuais.
- **Evolução Iterativa:** Nas versões intermediárias, integramos gráficos interativos com **Chart.js** e refinamos o layout com **Tailwind CSS** utilizando um estilo *glassmorphism*.
- **Versão Final:** Incorporação rigorosa do UI/UX inspirado no site oficial da Porsche Brasil (`#0A0A0A` fundo preto metálico, detalhes em vermelho Porsche `#D5001C`, fontes elegantes e cartões flutuantes).

---

## 🛠️ Ferramentas, Tecnologias e Materiais Utilizados

Para o desenvolvimento completo deste projeto de Business Intelligence e visualização de dados, foram empregues os seguintes materiais e ferramentas ao longo do pipeline:

* **Microsoft Excel**
  * **O que é:** Ferramenta de folha de cálculo.
  * **Por que foi usado:** Utilizado para a estrutura primária, armazenamento e validação inicial da base de dados de vendas de veículos (`porsche_vendas_database_sanitizada.xlsx`).

* **Claude AI**
  * **O que é:** Assistente de Inteligência Artificial avançado.
  * **Por que foi usado:** Empregue na fase inicial para realizar o tratamento, saneamento e correção programática da base de dados (resolução de datas inválidas e padronização dos registos).

* **Gemini AI**
  * **O que é:** Modelo multimodal de Inteligência Artificial generativa.
  * **Por que foi usado:** Utilizado para gerar a arquitetura lógica, o design visual de alta performance (*Dark Theme* inspirado no site oficial da Porsche Brasil) e o código iterativo da dashboard em HTML, CSS e JavaScript.

* **Notas (Bloco de Notas / Editores de Texto)**
  * **O que é:** Utilitários de texto simples.
  * **Por que foi usado:** Utilizados como repositórios de documentação provisória para armazenar, estruturar e refinar os prompts enviados às IA (`prompt_gemini_dashboard_porsche.txt`) e os scripts de código fonte bruto (`index_code.txt`).

* **HTML5, Tailwind CSS & Chart.js**
  * **O que é:** Stack de desenvolvimento web frontend e gráficos dinâmicos.
  * **Por que foi usado:** Responsáveis por renderizar a interface de utilizador (UI/UX) minimalista, desportiva e responsiva, bem como os gráficos interativos de receita, vendas e logística.

* **GitHub & GitHub Pages**
  * **O que é:** Plataforma de controlo de versões e alojamento web estático.
  * **Por que foi usado:** Utilizados para o armazenamento público do código-fonte e publicação imediata do projeto em produção (`Live Preview`), tornando a dashboard acessível para portfólio profissional.

---

## 🧹 Tratamento e Higienização da Base de Dados

Antes de alimentar a dashboard com a IA, a base de dados passou por etapas críticas de saneamento (realizadas via Python/Pandas):
- **Correção de Datas Inválidas:** Registros com marcações `INVALID` na coluna de data de venda (`SaleDateSanitized`) foram limpos e interpolados chronologicamente com base no ID da transação. E outros campos com valores não idênticos foram corrigidos para evitar erros e deixar todos os informações uniformes.
- **Padronização de Nomes:** Normalização de strings nas colunas de nomes de vendedores (`salesperson`), cidades, estados e modelos para evitar duplicações por divergência de maiúsculas/minúsculas. E deixar os informações mais clara para facilitar a leitura das informacoes.

---

## 🤖 Prompt e Código de Implementação

Para garantir a transparência do desenvolvimento assistido por IA, os artefatos de código e comandos estão disponíveis no repositório:
- **Prompt Utilizado ![dashboard-vendas-porsche](prompt_gemini_dashboard_porsche.txt) :** O prompt estruturado enviado à inteligência artificial para conceber o layout minimalista, desportivo e alinhado ao site oficial da Porsche Brasil.
- **Código Fonte ![dashboard-vendas-porsche](index_code.txt) :** O código textual completo em HTML, Tailwind CSS e Chart.js utilizado para renderizar os gráficos e tabelas interativas.

---

## 🚀 Acesso à Dashboard Publicada

- **URL do GitHub Pages:** [Clique aqui para aceder a Dashboard](https://jeandaedouard1009-eng.github.io/dashboard-vendas-porsche/)

---

> ## 📸 Evidências Visuais (Dashboard Preview) e Planilha Excel

Abaixo está uma pré-visualização da dashboard executiva com o tema Porsche aplicados:

![Dashboard Porsche Preview](dashboard_porsche.jpeg)

Baixar a planilha : ![dashboard-vendas-porsche](porsche_vendas_database_sanitizada.xlsx)
