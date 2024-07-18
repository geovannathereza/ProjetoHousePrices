# House Prices -  Advanced Regression Techniques

Repostório criado para a participação da competição do Kaggle sobre a previsão do preço das casas na cidade de Ames, Iowa (USA).

Iniciei o projeto importando a base de dados para o treino e entendendo a base de dados, olhando quantas linhas e colunas tinha, vendo quais os tipos de dados havia em cada coluna, como números "int", "object" e "float", quais colunas tinham valores nulos.

Em seguida, limpei os dados, descartando todas as colunas que tinham mais de 10% dos valores nulos, tratei os dados das colunas númericas restantes substituindo os valores nulos por "-1".

A próxima etapa foi criar os modelos, utilizei os algoritmos: Regressão Linear, Árvore de Decisão e KNN. Depois verifiquei as métricas de erro médio absoluto e erro quadrático médio, a partir de um gráfico foi possível visualizar qual dos algoritmos teve um melhor desempenho.

Agora com o algoritmo já definido, importei a base de testes, repetindo o processo de limpeza dos dados e preenchimento dos valores nulos, após aplicar a Regressão Linear nos dados de teste obtive o resultado 0.25 na competição.
