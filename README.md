# TrilhaCodersCD

Análise de Vendas de Cursos Online
Descrição
Este projeto tem como objetivo realizar uma avaliação simples das vendas de cursos online. Utilizando bibliotecas como pandas para manipulação de dados e matplotlib para visualização, buscamos compreender como as vendas estão distribuídas ao longo do mês e identificar quais cursos são os mais procurados.

Bibliotecas Utilizadas
pandas: Para estruturação e manipulação dos dados.
matplotlib.pyplot: Para visualização dos dados através de gráficos.
Dados
As informações fornecidas dizem respeito às vendas de cursos online, incluindo:

ID do curso
Nome do curso
Quantidade de vendas
Preço unitário
Data das vendas
Principais Etapas
Conversão da Coluna 'Data':

A coluna de data é convertida para o formato datetime usando pd.to_datetime() para permitir análises temporais.
Cálculo da Receita Total:

A receita total gerada pelas vendas dos cursos é calculada.
Evolução das Vendas:

Um gráfico de linha é criado usando plt.plot() para mostrar a evolução das vendas ao longo do mês de janeiro.
Identificação dos Cursos Mais Populares:

Os cursos são ordenados pela quantidade de vendas em ordem decrescente.
Os três cursos com maior quantidade de vendas são selecionados e destacados.
Conclusões Obtidas
Gráfico de Barras Horizontais:

Destaca os três cursos mais populares com base na quantidade de vendas.
Distribuição das Vendas:

Mostra uma preferência significativa por alguns cursos em comparação com outros, indicando uma maior demanda por determinados temas.
Cursos com preços mais baixos, como "Introdução à Programação em Python" (39.90), podem estar atraindo um maior número de compradores devido ao custo acessível.
