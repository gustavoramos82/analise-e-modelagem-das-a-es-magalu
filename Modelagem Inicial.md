# Modelagem Inicial

Inicialmente não será feito uma preparação dos dados para servir de *baseline* e comparar os ressultados, sendo que foi aplicado os Modelos Arima e Sarima e sendo usados três métricas para comparar os resultados: **MAPE, MAE e RMSE** para verificar o quão distantante os valores preditos ficaram distantes dos valores do teste.

Sendo que o dataset foi dividido em treino e teste, sendo que o treino foi feito do periodo de 2 de janeiro de 2018 a 29 de dezembro de 2022, e o periodo de teste é dos primeiros 20 dias de 2023

## Arima

Foi aplicado o modelo e tiveram as seguintes métricas

![image](https://user-images.githubusercontent.com/39843884/217269562-297346ab-cddc-4dd2-84ce-4ad3334fb010.png)

![image](https://user-images.githubusercontent.com/39843884/217269915-f3af9253-06bd-461d-81b0-1d9def93b575.png)

Olhando o gráfico podemos ver que o modelo preveu com uma tendência de queda, ao contrário do teste, pelo que foi feito na análise de que nos ultimos anos a ação teve uma queda, logo, o modelo seguiu essa tendência

## Sarima

![image](https://user-images.githubusercontent.com/39843884/217271351-87a439ab-d584-433e-8acd-365c65a5658b.png)

![image](https://user-images.githubusercontent.com/39843884/217271471-7b6cbaaf-cccc-43b8-85f8-f40deb837644.png)

Comparando o Sarima tivemos resultados melhores, entretanto , o comportamento do modelo é de quase uma reta se comparado o valor de teste

## Próximos Passos

Como próximo passo é usar outros modelos e comparar os resultados através de um pré-tratamento dos dados.

