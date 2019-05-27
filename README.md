# Guia-Analise-de-dados-com-SKLearn
Guia para análise de dados, utilizando sklearn

##### Códigos baseados na formação de Machine Learning da Alura Cursos online. Cada arquivo representa uma aula e seus ensinamentos 

## Aula 1

### "Predições Simples.ipynb"

#### Requisitos: 
<code> pip install scikit-learn </code>, biblioteca utilizada na análise de dados

#### Importações: 
<code>from sklearn.svm import LinearSVC</code> (fit, predict)
<code>from sklearn.metrics import accuracy_score</code> (accuracy_store)
#### Objetivos: 
<ul> <li>Criar um algoritomo que treine com base em termos booleanos 1-Verdadeiro, 0-Falso</li>
  <li>Indentificar se Animal é cachorro ou porco (nesse código), com base no treinamento</li>
  <li>Treinamento feito passando caracteristicas por listas para o aprendiza da biblioteca,
  cada item da lista representa uma caracteristica</li>
</ul> 
  
#### Comandos utilizados da biblioteca:
<ul>
<li><code>.fit(CARACTERISTICAS A SEREM TREINADAS , OBJETOS QUE SERÃO INDENTIFICADOS)</code> Treinamento da inteligencia</li>
<li><code>.predict([OBJETO A SER ADIVINHADO])</code> Verifica qual o tipo do objeto</li>
<li><code>accuracy_score(TESTE , PREVISÕES)</code> Utiliza o material de teste e o compara com o que foi já foi testado (predict) 
e retorna a taxa de acerto</li>
</ul>
