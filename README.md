# TrilhaCodersCD

##Análise de Vendas de Cursos Online

##Descrição

Este projeto tem como objetivo realizar uma avaliação simples das vendas de cursos online. Utilizando bibliotecas como pandas para manipulação de dados e matplotlib para visualização, buscamos compreender como as vendas estão distribuídas ao longo do mês e identificar quais cursos são os mais procurados.

Bibliotecas Utilizadas
pandas: Para estruturação e manipulação dos dados.
matplotlib.pyplot: Para visualização dos dados através de gráficos.
Dados


Dados:

As informações fornecidas dizem respeito às vendas de cursos online, com informações como ID do curso, nome do curso, quantidade de vendas, preço unitário e data da vendas.


Principais Etapas:

Conversão da Coluna 'Data': A coluna foi  convertida para o formato datetime usando pd.todatetime() para realização do desafio proposto.
Calcular a receita total gerada pela venda dos cursos.
Um gráfico de linha é criado usando plt.plot() para mostrar a evolução das vendas do mês de janeiro.
Identificação dos cursos mais populares: Os cursos são ordenados pela quantidade de vendas em ordem decrescente e os três cursos com maior quantidade de vendas são selecionados.

Conclusões Obtidas:
O gráfico de barras horizontais destaca os três cursos mais populares com base na quantidade de vendas.
A distribuição de vendas mostra uma preferência significativa por alguns cursos em comparação com outros, o que pode indicar uma demanda maior por determinados temas.
Curso com preço mais baixo como "Introdução à Programação em Python" (39.90,, pode estar atraindo um maior número de compradores devido ao custo acessível.

