# Grupo 1 (Exploração de Dados)

O script "grupo_selec.ipynb" realiza o treinamento utilizando KFold Cross Validation do grupo 1 utilizando os modelos (LinearSVC, Logistic Regression e Random Forest) <br>
O script "Grid_RandomForest_grupo_selec.ipynb" realiza o GridSearchCV utilizando a Random Forest do grupo 1 na base de treinamento e retorna o arquivo cv_grid.csv com os resultados. 
Para a reprodução dos experimentos é necessário a alteração do path de salvamento do arquivo (cv_grid.csv) <br>
O script "Análise Grid.ipynb" realiza a análise do cv_grid.csv para encontrar os parâmetros da Random Forest que obtiveram o melhor desempenho na etapa de GridSearchCV <br>
O script "teste.ipynb" realiza o treinamento na base de treinamento e a avaliação na base de teste.
