Para identificar a coluna mais adequada para regressão, vamos usar a análise de correlação de Spearman com a coluna home_team_shots_on_target_dirty, que é o alvo da imputação. Em seguida, verificaremos quais colunas têm uma correlação significativa (acima de 0.3) com home_team_shots_on_target_dirty. Essa abordagem ajudará a identificar as colunas que têm uma relação linear mais forte com o alvo.

Passos para Identificar a Coluna Ideal para Regressão
Calcular a Correlação de Spearman:
Calcular a correlação de Spearman entre home_team_shots_on_target_dirty e outras colunas para identificar quais delas têm uma correlação significativa.

Selecionar a Coluna com a Maior Correlação Significativa:
Selecionar a coluna com a maior correlação significativa, pois ela será a melhor candidata para regressão.

separar dados em treinamento validação e teste

escolher 4 algoritmos de regressao

adicionar um mlflow: para registrar e rastrear a execução dos modelos

executar uma ferramenta de hiper parametros sobre conjunto de validação

realizar diagnostigos do melhor modelo geral da etapa 5: fazer mais de um e ver qual é melhor


