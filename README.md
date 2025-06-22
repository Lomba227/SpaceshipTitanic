# SpaceshipTitanic
Repositório criado para a competição do Kaggle para prever se um passageiro foi transportado para outra dimensão

Primeiro foi feito o tratamento dos dados, substituindo todos os valores nulos, transformando as colunas categóricas importantes para a previsaão em numéricas e descartando as colunas categóricas que não eram importantes

Após o tratamento, foi feita divisão entre os dados de treino e os dados de teste, e a aplicação de três modelos (Árvore de decisão, KNN e regressão logística).

Foi feita a comparação da acurácia (métrica pedida pelo desafio) e analisado que a regressão logística foi o modelo que conseguiu a melhor acurácia (77,7%)

Como última análise, foi feita uma normalização dos dados para ver se a acurácia melhorava, porém, nos três casos, a acurácia piorou, sendo mais interessante trabalhar sem a normalização dos dados

Por fim, o mesmo trabalho foi feito com a base de teste, e o resultado obtido foi de 78%
