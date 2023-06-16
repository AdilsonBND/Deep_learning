# Estudo realizado sobre o gradiente descendente
<br>
<br>
<h1> Caso 1: Gradiente descendente uma variável:</h1><br><br>
Nesse estudo aplicamos a fórmula do gradiente descendente para alcançarmos os melhores pesos w0 e w1 para obtermos o menor custo possível.<br>
<br>
Realizamos os seguintes passos:
<br>
<br>
<pre>
1) Definimos as variáveis X e y. Com base nos valores X e y buscaremos encontrar os melhores pesos w0 e w1 para obtermos a previsão de qualquer outros valores X e y que nao estejam previamente definidos.
2) Definimos alpha (aceleração)
3) definimos pesos iniciais w0 e w1
4) criamos função da hipótese sendo w0 + w1 * X
5) criamos função de custo sendo  função hipótese - y
6) Criamos função que submete as variáveis nas fórmulas do gradiente descendente obtendo novos pesos w0 e w1
7) Criamos função que repete as fórmulas do gradiente descendente até obtermos pesos ajustados
8) Realizamos predição com os pesos obtidos no treinamento
</pre>
<br><br>
<h1>Caso 2: Gradiente descendente multiplas variáveis</h1>
<br>
<br>
Neste estudo, buscaremos encontrar os melhores pesos para definir preço de imóvel com base no tamanho e quantidade de banheiros que possui: <br><br>
<pre>
1) Carregamento dos dados e normalização
2) Preparação dos dados separando os parâmetros do alvo(target) e preenchimento do peso w0 com 1 <br>
para adequar a fórmula de variáveis multiplas
3) Treinamento dos dados com a fórmula: Wj = Wj - (alpha / len(X)) * [W(transposta)*X - Y(i)] * Xj(i)
4) Obteve-se os pesos aprimorados para predição 
