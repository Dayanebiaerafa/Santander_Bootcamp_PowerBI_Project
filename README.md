 # Projeto de Análise de Dados em Power BI

- [📄 PDF com os Dashboards](https://github.com/Dayanebiaerafa/Santander_Bootcamp_PowerBI_Project/blob/main/Forma%C3%A7%C3%A3o%20Power%20Bi%20Analyst.pdf)

##  Uma Jornada de Aprendizado: Do Desafio à Análise Estratégica

Este repositório apresenta meu projeto desenvolvido no **Santander Bootcamp 2023 - Ciência de Dados com Python (DIO)**.  
O objetivo foi criar **dashboards estratégicos no Power BI** para analisar vendas e lucro, extraindo **insights valiosos para decisões de negócio**.
A evolução do projeto reflete meu crescimento e proatividade em ir além do desafio proposto.    

---

## Página 1: Sales Report

O dashboard apresenta um **Relatório de Vendas interativo**, com foco em análise detalhada de vendas por segmento, produto e país, ao longo do tempo.

### Componentes e funcionalidades principais:

- **Resumo numérico superior:**  
  - Total de vendas: 118,73 Mi  
  - Unidades vendidas: 1 Mi  
  - Soma de descontos: 9,21 Mi  
  - Soma de COGS: 101,83 Mi  
  - Permite rápida visão dos KPIs financeiros essenciais.

- **Filtro de Data:**  
  - Seleção dinâmica de intervalo de datas para análise temporal.  
  - Permite ao usuário ajustar o período de análise para adequar a visualização.

- **Gráfico de linha (Soma de Sales por Mês):**  
  - Representa a evolução das vendas ao longo dos meses.  
  - Identifica tendências sazonais e picos de vendas.

- **Gráfico de segmento (Sales x Segment):**  
  - Visualização que compara os segmentos de clientes em termos de vendas.  
  - Pode ser visualizado como Gráfico de Barras (Bar Chart) ou Gráfico de Rosca (Pie Chart).  
  - Botões permitem alternar entre essas duas visualizações para melhor compreensão.

- **Gráfico por produto (Sales por Product):**  
  - Barra horizontal que destaca os produtos com maior volume de vendas.  
  - Fácil para identificar os produtos mais vendidos e sua participação relativa.

- **Gráfico de país (Sales x Country):**  
  - Pode ser visualizado em Treemap ou Mapa Geográfico (Map Chart).  
  - Botões permitem alternar entre visualização hierárquica (Treemap) e geográfica (Mapa).  
  - Fornece visão espacial das vendas, mostrando a distribuição por países.

### Comentário:

A alternância entre os gráficos (Bar Chart / Pie Chart e Treemap Chart / Map Chart) oferece flexibilidade para os usuários visualizarem os dados sob diferentes perspectivas, seja por comparação direta, distribuição percentual ou contexto geográfico.

A combinação de KPIs numéricos, gráficos temporais e segmentados permite análises rápidas para decisões táticas e estratégicas, como identificar segmentos ou produtos que merecem maior atenção.

O filtro de data possibilita acompanhar tendências e variações ao longo do tempo, essencial para análises históricas ou para medir impacto de campanhas.

---

## Página 2: Report de Lucro Detalhado

Fornecer uma visão analítica e segmentada do **lucro total (Profit)** ao longo dos anos 2013 e 2014, permitindo identificar padrões, variações e oportunidades de crescimento por país, produto, segmento e período.

### Estrutura e análises implementadas

- **Filtros de Ano:**  
  Botões interativos (2013 e 2014) permitem a análise isolada ou comparativa dos períodos.

- **Análise Hierárquica de Lucro por País:**  
  Gráfico em formato de árvore (drill-down) mostra a soma do Profit total por ano, permitindo detalhar por país.  
  Identifica os países com maior contribuição para o lucro, como Alemanha e Canadá.

- **Análise de Produto (Radar Chart):**  
  Gráfico de radar exibe a distribuição do lucro por categoria de produto (ex.: Paseo, VTT, Arma..., Velo...).  
  Ideal para avaliar equilíbrio ou concentração de vendas em determinados produtos.

- **Segmentação de Mercado (Treemap):**  
  Visual em formato de árvore de retângulos que destaca a participação no lucro por segmento de cliente (ex.: Government, Small Business, Channel Partners, Midmarket).  
  Evidencia quais segmentos dominam o faturamento, com Government sendo o principal.

- **Análise Temporal (Gráfico de Cascata):**  
  Waterfall Chart exibe a variação de lucro por trimestre, destacando aumentos e reduções ao longo do ano.  
  Facilita entender a evolução sazonal do lucro e os períodos de maior contribuição.

### Comentário:

Permite decisões direcionadas para priorizar países, produtos e segmentos mais lucrativos.  
Apoia estratégias sazonais, alinhando campanhas aos trimestres de maior performance.  
Fornece visão macro (total de lucro) e micro (detalhes por país/produto), essencial para otimização de portfólio e alocação de recursos.

---

## Página 3: Análise Estratégica: Desempenho e Tendências 

### Tabela de Margem de Lucro por Produto e País

- Apresenta a margem de lucro percentual por produto em diferentes países (Canadá, França, Alemanha, México e Estados Unidos).
- A última coluna mostra o total médio de margem de lucro por produto, permitindo rápida identificação dos produtos mais rentáveis.
- Produtos como **"Amarilla"**, **"Montana"** e **"VTT"** destacam-se com margens totais acima de 13%, enquanto **"Velo"** apresenta a menor margem total (12,64%).
- A linha "Total" no final mostra a média de margem de lucro para cada país, útil para avaliar o desempenho regional.

### Gráfico de Barras à Direita: Margem de Lucro por Produto

- Complementa a tabela com uma visualização clara e rápida da margem de lucro de cada produto.
- Facilita a comparação direta entre produtos, destacando rapidamente "Amarilla" como o produto com maior margem, seguido por "VTT" e "Paseo".

### Gráfico de Linhas e Barras (embaixo à esquerda): Vendas (Receita) e Volume (Unidades) por Mês

- Apresenta a evolução temporal das vendas em receita (linha) e volume de unidades vendidas (barras) ao longo dos meses.
- Permite identificar tendências sazonais, picos de vendas e correlação entre volume e receita.
- Por exemplo, outubro apresenta um pico significativo em receita (201 Mil), acompanhando um aumento no volume (17,4 Mil unidades).

### Gráfico de Barras Empilhadas (embaixo à direita): Vendas x Lucro por Faixa de Desconto

- Exibe a soma das vendas e do lucro categorizados por diferentes faixas de desconto (Medium, High, Low, None).
- Mostra claramente que faixas com menos ou nenhum desconto apresentam maior proporção de lucro em relação às vendas.
- Indica o impacto do desconto sobre a rentabilidade, ajudando na definição de políticas comerciais.

### Comentário:

- Foco em produtos com maior margem: **"Amarilla"** e **"Montana"** apresentam boas margens e podem ser priorizados em campanhas e estoques.
- Atenção a variações sazonais: Os picos de vendas em meses específicos podem orientar o planejamento de produção e marketing.
- Gestão de descontos: Estratégias de desconto podem ser ajustadas para equilibrar volume de vendas e lucro, reduzindo descontos em produtos/segmentos com baixa margem.
- Análise regional: Identificar países com menor margem para estudar causas e oportunidades de melhoria.

---

## Ferramentas e Habilidades Demonstradas

- **Microsoft Power BI:** Desenvolvimento de dashboards interativos e visualmente claros.  
- **DAX:** Criação de medidas, como Margem de Lucro, para análises aprofundadas.  
- **Storytelling com Dados:** Estruturação de dashboards para contar uma história clara e acionável.  
- **Pensamento Analítico e Proativo:** Iniciativa em ir além do desafio proposto para gerar mais valor.  
- **Interatividade Estratégica:** Uso de Bookmarks e Botões para criar uma experiência de usuário dinâmica e rica em insights.

---



📬 **Conecte-se comigo no LinkedIn:** [dayaneteodoro](https://www.linkedin.com/in/dayaneteodoro/)
