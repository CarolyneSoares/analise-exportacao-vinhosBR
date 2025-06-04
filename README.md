# 🍇🍷Análise da Dados de Vinhos Brasileiros(2010–2024)🍷🍇

Este repositório reúne o **Tech Challenge 1 – Análise de Dados de Vinhos no Brasil de 2010 a 2024**, desenvolvido no curso de Pós-Tech em Data Analytics da FIAP. O projeto investiga quatro dimensões principais do mercado vinícola nacional (exportação, importação, produção e comercialização interna) e compara o cenário brasileiro com indicadores globais.

---

## Equipe

- Carolyne Rafaella Soares Costa (RM361016)  
- Juliana Gomes Maciel (RM363084)  
- Natalia Alexandra Leite Trippo (RM363623)  
- Natane Cezario Barbosa (RM362783)  
- Tainara Covas Nogueira (RM364981)  

---

## Introdução

No contexto de alta competitividade internacional, produzir e exportar vinho sem compreender tendências de mercado pode resultar em perdas significativas. Este estudo utiliza análise de dados para mapear o comportamento do mercado de vinhos brasileiro entre 2010 e 2024, fornecendo subsídios para a tomada de decisão estratégica de produtores e exportadores.

---

## Visão Geral / Entendimento do Negócio

- **Objetivo**: Avaliar volumes e receitas de exportação e importação, entender a evolução da produção interna e da comercialização no mercado interno, e posicionar o Brasil frente ao mercado mundial de vinhos.  
- **KPIs Principais**:  
  - Volume exportado (litros)  
  - Receita de exportação (US$)  
  - Preço médio por litro exportado (US$/L)  
  - Volume importado (litros)  
  - Receita de importação (US$)  
  - Volume produzido (litros)  
  - Volume comercializado internamente (litros)  

---
## Descrição dos Arquivos

### 1. `Análise Exportação de Vinhos Brasileiros/Analise_Vinhos_Brasil_2010_2024.pdf`
- Relatório formal em PDF que reúne:
  1. **Introdução e Contextualização**: motivação para estudar o mercado vinícola brasileiro.
  2. **Metodologia**: fontes de dados, processo de coleta, limpeza e transformação.
  3. **Análise Exploratória – Mercado Nacional**: detalhes sobre exportação, importação, produção interna e comercialização interna de vinhos.
  4. **Análise Comparativa – Mercado Global**: posicionamento do Brasil no contexto mundial de vinho fino (participação, principais produtores e consumidores).
  5. **Conclusões e Recomendações**: insights acionáveis para produtores e exportadores (novos mercados, certificações, estratégias de branding).
  6. **Anexos**: trechos de código Python, tabelas auxiliares e referências bibliográficas.

### 2. `notebooks/Analise_de_Dados_de_Vinhos_no_Brasil.ipynb`
- Notebook Jupyter que detalha, em código Python executável:
  1. **Importação de bibliotecas**: `pandas`, `numpy`, `matplotlib`, `seaborn` etc.
  2. **Leitura dos dados CSV** localizados em `data/`.
  3. **Tratamento e limpeza de cada base**:
     - Padronização de colunas (conversão de unidades, renomeação de campos, normalização de nomes de países).
     - Remoção e/ou imputação de valores nulos.
     - Cálculo de métricas intermediárias (ex.: preço médio por litro).
  4. **Análise Exploratória**:
     - **Exportação**: séries históricas (2010–2024) de volume e receita; top 5 destinos por volume e por receita.
     - **Importação**: séries históricas de volume e receita; principais fornecedores.
     - **Produção Interna**: evolução da produção nacional (litros); impacto de fatores climáticos.
     - **Comercialização Interna**: evolução do volume comercializado (2009–2023) por categoria de vinho.
     - **Comparativo Global**: participação do Brasil no mercado mundial de vinho fino; mapas de dispersão e gráficos comparativos.
  5. **Blocos de Markdown explicativos**: cada etapa de código vem acompanhada de comentários sobre lógica e interpretação dos resultados.

### 3. `relatorios_complementares/visuais_individuais_pbi.pbix`
- Relatórios em Power BI que complementa o PDF para as análises.

### 4. `relatorios_complementares/visuais_individuais_ppt.pptx`
- Apresentação em PowerPoint que contém cada visual gerado no Power BI em slides separados.

---
## Conclusão

Com base na análise dos últimos quinze anos de exportação de vinhos brasileiros, foi possível identificar os principais mercados, as variações de preço e volume, e os destinos com maior potencial de crescimento. O uso de técnicas de análise de dados revelou insights valiosos que podem orientar decisões estratégicas de forma mais eficiente e assertiva. Esse estudo marca o início da atuação analítica dentro da empresa e fundamenta planos de ação voltados à expansão internacional do vinho brasileiro.

Destaca-se o grande potencial de performance da indústria de viticultura brasileira no mercado externo, especialmente nos mercados globais de alto nível. Com ajustes e direcionamento estratégico das exportações, é possível aumentar a penetração do vinho fino nacional em mercados mais maduros e de maior demanda, mantendo a percepção de alta qualidade do produto brasileiro. A segmentação da estratégia em fases também permite maior flexibilidade para ampliar a receita das exportações sem comprometer a expansão da capacidade produtiva.




