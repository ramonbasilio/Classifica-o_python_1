# Classificacao_python_1 - Machine Learning
Olá! Nesse repertório demonstrará o principio básico de funcionamento de classificação utilizando a biblioteca Sklearn e suas ferramentas com um exemplo de classificação de usuários que acessam de um site de cursos de programação.

Exemplos de classificação:
- Classificar usuários que acessam determinado site para predizer se um usuário tem probabilidade finalizar uma compra 
- A partir de dados de exame, classificar se um paciente tem probabilidade de ter determinada doença, auxiliando o médico no diagnóstico
- Determinar se o valor de venda de um carro está adequado em comparação com os dados de venda de carros 
- Identificar se um e-mail é spam ou não

Dentro do mundo de Machine Learning, que é o emprego de algoritmo para analisar dados afim de construir métodos modelos analíticos e insights, com o mínimo de intervenção humana, existem diversas ferramentas para lidar com os diversos tipos de dados conforme o problema a ser trabalhado.

O problema em questão a ser tratado é analisar os dados referentes a usuários de um determinado site de cursos de programação. O dados informam se o usuário acessou a página home, o tipo de busca (qual linguagem o usuário buscou), se o usuário estava logado ou nao e por fim, se o usuário comprou ou não o curso. 

O algoritmo a ser utilizado nesse case é de classificação, pois é necessário diferenciar o usuário entre duas classes distintas, aqueles que COMPRAM e aqueles que NÃO COMPRAM, e predizer se um determinar usuário tem probabilidade de finalizar uma compra comparando com os dados.

As ferramentas utilizadas nesse notebook são as relacionada abaixo:

Linguagem: Python 3

Bibliotecas: pandas, sklearn, collections

Algoritmos de classificação: MultinomialNB (Naive Bayes) e AdaBoost

Os dados foram extraídos do site www.alura.com.br
