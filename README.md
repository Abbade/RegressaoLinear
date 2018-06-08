 0-Crie um cabeçalho com nome e matrícula
1-Mostre os primeiros registros da tabela
	mostrado
2-Observações(linhas) possui nessa base? Quantas Colunas?
	506. 13.
3-Quantas Features Possui?
	13
4-Qual é o campo Target(respostas) dessa base?
	 LSTAT
5-Usando a biblioteca de visualização seaborn, plote o gráfico que mostra a relação entre as features e responses
	feito
6-Prepare X e y usando o pandas
 	feito	
7-Qual o tipo de dados de X e y?
X  = pandas.core.frame.DataFrame
	y = 'pandas.core.series.Series
8-Sobre o que se trata essa base de dados? Que tipo de informações ela guarda?
	preços de casas em boston
9-Gere um X de treino e y de treino, X de teste e y da base (Split Train/Test)
	feito
10-Qual o percentual gerado para criar o conjunto de treino e o conjunto de teste?
	75%
11-Usando modelo de regressão linear do sklearn, treine o modelo com o X e y de treino
	FEITO
12-Imprima os atributos de "intercept" e "coefficients" que foram gerados
28.2087872575
[  9.93402744e-02   1.64900594e-02   9.04088124e-02  -4.71607773e-01
   5.47812506e+00  -4.35334293e+00   1.01378220e-01   2.50707215e-01
   5.85624938e-04   1.21538839e-01  -8.44969483e-03]

13-imprima o par "feature names" com os "coefficients"
[('CRIM', 0.099340274407543824),
	 ('ZN', 0.016490059382672565),
 	('INDUS', 0.090408812373183933),
 	('CHAS', -0.4716077726795751),
 	('NOX', 5.4781250550417333),
 	('RM', -4.3533429279412683),
 	('AGE', 0.10137822043241936),
 	('DIS', 0.2507072151539837),
 	('TAX', 0.00058562493844640379),
 	('PTRATIO', 0.12153883861301121),
 	('B', -0.0084496948329787318)]

14-Faça uma previsão usando o conjunto de X de teste
	Feito
15-Mostre a margem de error, usando o método "Root Mean Squared Error (RMSE)"
	feito
16-Existe uma forma de melhorar essa margem para que fique menor? Se sim, como seria?
	Sim, verificar os dados e utilizar os gráficos onde os dados estão mais pertos da reta
