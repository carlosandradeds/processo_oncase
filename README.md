# Processo Seletivo Oncase
Este repositório contém as resoluções do teste do processo seletivo Oncase.

Cada pasta contém a resolução para as questões a seguir



## 1.0 Análise descritiva dos dados (EDA)




Construa uma análise descritiva extraindo conhecimento das variáveis e apresentando quais insights podem ser obtidos a partir delas;

Mostre-nos um caminho para selecionar graficamente as variáveis mais ou menos importantes para cada problema, como elas se relacionam e porquê.

Em cada problema descreva quais outras técnicas poderiam ser aplicadas e porquê você não as escolheu.

Utilize os dados: eda_receitas_data.zip




## 2.0 Teste técnico de modelagem

Nessa parte, será necessário implementar um algoritmo de acordo com o paradigma do problema. Cada problema tem um conjunto de métricas que são requeridas. A variável alvo sempre será a coluna de nome “target”, exceto para os problemas não-supervisionados.

 - 1 Construa um classificador e identifique quais variáveis exercem maior impacto sobre o “target” e informe o porquê interpretando os resultados obtidos. 

Métricas: precision, recall e F1-score;



- 2 Selecione um sku (produto) e realize uma previsão da demanda do mesmo nos próximos 4 intervalos de tempo de sua escolha (dia, semana, mês, etc) 

Métricas: rmse, mape;



- 3  Construa um regressor e identifique quais variáveis exercem maior impacto sobre o “target” e informe o porquê interpretando os resultados obtidos. 

Métricas: RMSE, R2 e cor(target_observado, target_predito);

