# Análise e Modelagem da Ação da Magalu (MGLU3)

Neste repositório será feita uma análise e modelagem de séries temporais das ações da magalu, o dataset foi extraido através da blibioteca yahoo finance com dados de 22 de janeiro de janeiro 2018 ate 20 de janeiro de 2023.

## Análise Exploratória

Colocando os preço das ação do Magalu em um gráfico, verifica-se:

![image](https://user-images.githubusercontent.com/39843884/214046516-40f1ca21-edab-4719-b0d5-9cf1a7e42e49.png)

- de 2018 até janeiro de 2020 podemos ver um crescimento no valor da ação;
- De feveiro até março de 2020, temos uma queda do valor, provavelmente devido a pandemia que deve ter afetado as vendas nas lojas fisicas;
- Depois disso tem uma aumento no valor da ação até novembro de 2020, onde alcançou o maior valor desse periodo, que foi em torno de 25 reais;
- Após isso observa uma queda.

Para ficar mais fácil de visualizar, vereos esse *boxplot* do valor da ação e comparado durante os anos

![image](https://user-images.githubusercontent.com/39843884/214047681-16b0a34a-6b6e-4d01-b1a5-6025ccf3125f.png)

Em 2018 não teve uma grande variação e o preço da ação estava em torno de 5 reais, em 2019, observa-se uma maior variação com valores chegando em torno de 12 reais sendo que a maior parte do preço do ano esta maior que cinco reais, 2020 e 2021 vemos uma maior variação nos preços, cuja maior parte dos preço estava em torno de 15 em 2020 e 20 reais em 2021 (como pode ser observado no gráfico anterior, foi nesse periodo que a ação teve o valor mais alto no momento em que se estsendo observado. 

![image](https://user-images.githubusercontent.com/39843884/214049170-e9c33234-8e7f-4649-9a26-99b3b345cb7e.png)

Aplicando uma média móvel de 30 dias nos valores das ações pode perceber uma tendência ao longo dos anos (2018-2022) percebe-se uma tendencia ao longo dos anos, sendo que:

- 2018: Crescimento
- 2019: Crescimento
- 2020: Crescimento
- 2021: Queda
- 2022: Queda

Ou seja, pode ver que de 2018 até 2020 tem tido tido um crescimento nos valores, mas, a partir de 2021 os valores da ações tem obtido uma queda, isso pode ser visto se for aplicado o teste de Mann-Kendall, utilizado para determinar se determinadasérie de dados possui uma tendência temporal de alteração estatisticamente significativa (para mais informações verificar [aqui](https://www.alice.cnptia.embrapa.br/alice/bitstream/doc/981998/1/CMK.pdf))

Teste aplicado para o ano de 2018

![image](https://user-images.githubusercontent.com/39843884/214050996-5a805550-945b-43ba-b90a-c6319ae88344.png)

Teste aplicado para o ano de 2019

![image](https://user-images.githubusercontent.com/39843884/214051095-a2485828-0f92-4c47-b132-75abe92b8da5.png)

Teste aplicado para o ano de 2020

![image](https://user-images.githubusercontent.com/39843884/214051305-576ae240-975e-414d-b90d-f667747a2b35.png)

Teste aplicado para o ano de 2021

![image](https://user-images.githubusercontent.com/39843884/214051399-0aff6549-152b-44e4-83d3-43d08e05aee4.png)

Teste aplicado para o ano de 2022

![image](https://user-images.githubusercontent.com/39843884/214051572-a4dd54b6-60bd-48bd-8b39-5c2743e95c3b.png)



## Modelagem

🚧 Em Construção 🚧

