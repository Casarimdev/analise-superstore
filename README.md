# 📊 Projeto: Análise de Vendas Superstore

Este repositório contém um script Python para análise exploratória de dados de vendas da Superstore. O objetivo é limpar, explorar e gerar recomendações a partir de padrões de vendas, lucro e categorias de produtos.

---

## 💼 Contexto do Projeto

- **Caso real**: Rede de lojas de material de escritório e utilidades domésticas.
- **Fonte de dados**: Dataset público “Superstore Sales” com 8.399 registros.
- **Formato**: CSV com encoding ISO-8859-1.
- **Objetivo**: Identificar padrões de venda e rentabilidade para suporte a decisões estratégicas.

---

## 🛠️ Tecnologias Utilizadas

- **Python 3.9+**
- **Pandas** para tratamento e análise de dados
- **Matplotlib** e **Seaborn** para geração de gráficos e visualizações

---

## 🚀 Como Executar o Projeto

1. Clone o repositório:
   git clone https://github.com/seu-usuario/analise-superstore.git

2. Navegue até a pasta do projeto:
  cd analise-superstore

3. Instale as dependências:
  pip install pandas matplotlib seaborn
  
4. Execute o script:
   python analise_superstore.ipynb

--- 

## 📈 Análises Realizadas
1️⃣ Vendas por Região
Gráfico de barras que identifica as regiões com maior volume de vendas.

2️⃣ Lucro vs. Vendas
Gráfico de dispersão para entender a relação entre lucro e volume de vendas.

3️⃣ Vendas por Categoria de Produto
Gráfico de barras horizontal com comparação de desempenho entre categorias.

---

## 📊 Principais Descobertas
- A Região Oeste lidera em volume de vendas, mas também apresenta alta variabilidade no lucro.

- Existe uma correlação positiva entre lucro e vendas, com algumas exceções de alto volume e baixo lucro, indicando possíveis perdas com frete ou descontos excessivos.
  
- A categoria Technology é a mais lucrativa, enquanto Furniture tem desempenho mais mediano.

---

## 💡 Recomendações de Negócio
- Revisar políticas de desconto e frete, especialmente para pedidos de alto valor com lucro negativo.

- Expandir estratégias de marketing em regiões como o Centro, que apresentam potencial de crescimento.

- Focar em produtos de alta margem na categoria Technology.

- Analisar mix de produtos por região para adaptar o portfólio à demanda local.

