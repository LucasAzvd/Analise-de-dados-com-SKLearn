# Guia-Analise-de-dados-com-SKLearn
Guia para análise de dados, utilizando sklearn

##### Códigos baseados na formação de Machine Learning da Alura Cursos online. Cada arquivo representa uma aula e seus ensinamentos 

## Aula 1

### "Predições Simples.ipynb"

#### Requisitos: 
<code> pip install scikit-learn </code>, biblioteca utilizada na análise de dados

#### Importações: 
<code>from sklearn.svm import LinearSVC</code> (fit, predict)<br>
<code>from sklearn.metrics import accuracy_score</code> (accuracy_store)

#### Objetivos: 
<ul> <li>Criar um algoritomo que treine com base em termos booleanos 1-Verdadeiro, 0-Falso</li>
  <li>Indentificar se Animal é cachorro ou porco (nesse código), com base no treinamento</li>
  <li>Treinamento feito passando caracteristicas por listas para o aprendiza da biblioteca,
  cada item da lista representa uma caracteristica</li>
</ul> 
  
#### Comandos utilizados da biblioteca:
<ul>
<li><code>.fit(CARACTERISTICAS_A_SEREM_TREINADAS , OBJETOS_QUE_SERÃO_INDENTIFICADOS)</code> Treinamento da inteligencia</li>
<li><code>.predict([OBJETO_A_SER_ADIVINHADO])</code> Verifica qual o tipo do objeto</li>
<li><code>accuracy_score(TESTE , PREVISÕES)</code> Utiliza o material de teste e o compara com o que foi já foi testado (predict) 
e retorna a taxa de acerto</li>
</ul>

## Aula 2

### "Guia-Analise-de-dados-com-SKLearn.ipynb"

#### Requisitos: 
<code> pip install scikit-learn </code>, biblioteca utilizada na análise de dados<br>
<code> pip install pandas </code>, biblioteca para tratamentod e dados

#### Importações: 
<code>from sklearn.svm import LinearSVC</code> (fit, predict)<br>
<code>from sklearn.metrics import accuracy_score</code> (accuracy_store)<br>
<code>from sklearn.model_selection import train_test_split </code> (train_test_split)<br>
<code>import pandas as pd </code>

#### Objetivos: 
<ul> <li>Ampliar conhecimneto no tratamento de dados</li>
  <li>ler um Dataframe (nesse caso um csv)</li>
  <li>Organizar o Dataframe</li>
  <li>Ampliar conhecimento no tratamento de dados, como divisão de dados para análises mais esfetivas</li>
</ul> 
  
  
#### Comandos utilizados da biblioteca:
 ##### Pandas <ul>
<li><code>pd.read_csv(SEU_DATAFRAME)</code> ->Leitura do Dataframe</li>
<li><code>.rename(columns = LISTA_COM_OS_NOVOS_NOMES_DA_COLUNA)</code> ->Recebe uma lista com os novos nomes e os substitui</li>
</ul>

 ##### SKLearn <ul>
<li><code>.fit(CARACTERISTICAS_A_SEREM_TREINADAS , OBJETOS_QUE_SERÃO_INDENTIFICADOS)</code> ->Treinamento da inteligencia</li>
<li><code>.predict([OBJETO_A_SER_ADIVINHADO])</code> ->Verifica qual o tipo do objeto</li>
<li><code>accuracy_score(TESTE , PREVISÕES)</code> ->Utiliza o material de teste e o compara com o que foi já foi testado (predict) 
e retorna a taxa de acerto</li>
 <li><code>treino_x, teste_x, treino_y, teste_y = train_test_split(TREINAMENTO_X, TREINAMENTO_Y, random_state = SEMENTE, test_size = PORCENTAGEM_DE_ELEMENTOS_QUE_SERVIRÁ_PARA_TESTE)</code> ->Divide o material para treinamento e teste mais "precisão", a semente é criada para que a divisão não seja "aleatória"</li>
</ul>

