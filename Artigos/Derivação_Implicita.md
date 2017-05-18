# Derivação Implícita

Em algumas funções obter uma equação onde o Y está isolado é um trabalho bem dificil, por exemplo as funções

![x^2 + x^2 = 25](https://raw.githubusercontent.com/josenberg/MA111/master/Artigos/Images/Deriva%C3%A7%C3%A3o_Implicita/01.png)

![x^3 + x^3 = 6xy](https://raw.githubusercontent.com/josenberg/MA111/master/Artigos/Images/Deriva%C3%A7%C3%A3o_Implicita/02.png)


Pode ser que até seja possível isolar o Y e determinar uma ou mais funções que expressão essa equação graficamente, porém existem mais jeitos de resolvermos esse tipo de problema; Para encontrar as equações para y' dos exemplos acima basta usarmos a *derivação implicita*.

## Exemplo 1
**Se x² + x³ = 25, obtenha y';**

(1) O primeiro passo é derivar os dois lados da função,
d(x² + y²)/dx = d(25)/dx
d(x²)/dx + d(y²)/dx = 0

(2) Encontrar a derivada do primeiro elemento dessa soma
f(x) = x²
f'(x) = 2x

(3) Notando que y está é uma função dependende de x podemos usar a regra da cadeia para deriva-la:

d(y²)/dx = d(y²)/dy * d(y)/dx = 2y * dx/dy

- Isolamos a variavel dx/dy e obteremos

dy/dx = -x/y

(4) Trocando algebricamente esses dois fatores na função da derivada que queremos encontrar podemos fazer:

2x + (2y * dy/dx) = 0
dy/dx = -2x/2y = -x/y

## Exemplo 2
**Encontre y' da função x³ + y³ = 6xy**

(1) Vamos derivar ambos os lados da equação e considerar a regra da cadeia para obter y³ e a regra do produto para obtermos 6xy;

3x² + 3y*y' = 6xy' + 6y  ou x² + y²*y' = 2xy' + 6y

(2) Agora isolamos o y' e teremos:

y' = (2y - x²)/y² - 2x.

##Resumindo
- Deriva ambos os lados
- Resolva o máximo possivel ambos os lados
