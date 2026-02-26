🛒 Análise de Vendas Amazon com Pandas
Análise exploratória de um dataset com 50.000 registros de vendas da Amazon, utilizando Python e Pandas.

📋 Sobre o Projeto
Este projeto foi desenvolvido como exercício prático de análise de dados, aplicando conceitos de filtragem, agrupamento e manipulação de colunas com a biblioteca Pandas.
Dataset obtido no Kaggle.

📂 Estrutura do Dataset
ColunaDescriçãoorder_idID do pedidoorder_dateData do pedidoproduct_categoryCategoria do produtopricePreço originaldiscount_percentPercentual de descontodiscounted_pricePreço com descontoquantity_soldQuantidade vendidacustomer_regionRegião do clientepayment_methodMétodo de pagamentoratingAvaliação do produtototal_revenueReceita total

🔍 O que foi analisado

Carregamento e visualização dos dados
Ranking de categorias mais vendidas
Filtro de pedidos com alto rating e alto desconto
Criação de coluna com valor do desconto em reais
Receita total por região — identificando qual região fatura mais
Classificação de performance dos produtos por avaliação
Método de pagamento mais utilizado
Filtro de livros acima da média geral de receita


💡 Principais Insights

📦 Beauty é a categoria com mais pedidos (8.465)
⭐ Produtos classificados com np.where em: Excelente, Bom e Ruim
💳 O método de pagamento mais usado foi identificado com value_counts()
🌍 A receita foi agrupada por região com groupby


🛠️ Tecnologias utilizadas

Python 3
Pandas
NumPy
