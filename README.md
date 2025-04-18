📈 Regressão Linear com Python e NumPy

Este projeto implementa uma classe simples de Regressão Linear utilizando apenas a biblioteca NumPy, com o objetivo de realizar previsões a partir de um conjunto de dados numéricos correlacionados.

🚀 Funcionalidades
- Cálculo do coeficiente de correlação de Pearson

- Cálculo da inclinação da reta (coeficiente angular)

- Cálculo da interceptação com o eixo y (coeficiente linear)

- Previsão de valores utilizando a equação da reta

🧠 Conceitos aplicados
Este projeto reforça os fundamentos da Regressão Linear Simples:


  y=a⋅x+b
Onde:

𝑎
a é a inclinação da reta

𝑏
b é o ponto de interceptação

𝑥
x é o valor de entrada

𝑦
y é o valor previsto

🧾 Exemplo de uso

    from numpy import array
    from linear_regression import LinearRegression

    x = array([1, 2, 3, 4, 5])
    y = array([2, 4, 6, 8, 10])

    lr = LinearRegression(x, y)
    previsao = lr.previsao(5)

    print(previsao)  # Saída esperada: 10.0
📦 Requisitos

Python 3.x

NumPy

Instale o NumPy com:

    pip install numpy

📁 Estrutura da Classe

__correlacao(): calcula o coeficiente de correlação.

__inclinacao(): calcula a inclinação da reta de regressão.

__interceptacao(): calcula o ponto de interceptação da reta.

previsao(valor): retorna o valor de y estimado para um valor de x.

👨‍💻 Autor
Desenvolvido por Bertrand Otoniel – em processo de aprendizado de Machine Learning e Ciência de Dados.
