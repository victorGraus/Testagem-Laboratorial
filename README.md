# Testagem-Laboratorial

Inglês
So, in this code that I wrote, you can see an example of how to train and evaluate a logistic regression model to classify samples of rose leaves using popular Python libraries for data analysis, such as numpy, pandas, matplotlib, and seaborn, along with the train-test data split function from sklearn.

In the first part of the code, I generated fictional data for rose leaves by creating a feature matrix (X) with 1000 samples and 4 features each, and a target variable vector (y) with 1000 classes (0 or 1) for the rose leaf samples. In a real scenario, you would replace this part of the code with reading your own dataset of rose leaves.

Next, the data is split into training and test sets using the train_test_split function from sklearn, where 80% of the data is used for training and 20% for testing. I set the random_state parameter to 42 to ensure reproducibility of results.

After that, I created a logistic regression model using the LogisticRegression class from sklearn, and fit the model to the training data using the fit method. The trained model was then used to make predictions on the test data using the predict method, and the predictions were evaluated against the true target variable using the accuracy metric, which is the proportion of correct predictions out of total predictions made.

Finally, a scatter plot of the test samples was generated, where the colors of the samples were encoded according to the classes predicted by the logistic regression model. The plot was made using the matplotlib library, with the x-axis representing the first feature and the y-axis representing the second feature of the test samples. The title of the plot was set as "Test Samples with Predicted Class Colors".


Português BR

Então, nesse código que eu escrevi, você pode ver um exemplo de como treinar e avaliar um modelo de regressão logística para classificar amostras de folhas de rosas usando algumas bibliotecas populares de Python para análise de dados, como o numpy, pandas, matplotlib e seaborn, além da função de divisão de dados de treinamento e teste do sklearn.

Na primeira parte do código, eu criei dados fictícios de folhas de rosas, gerando uma matriz de características (X) com 1000 amostras e 4 características cada, e um vetor de variável alvo (y) com 1000 classes (0 ou 1) para as amostras de folhas de rosas. Em um cenário real, você substituiria essa parte do código pela leitura do seu próprio conjunto de dados de folhas de rosas.

Em seguida, os dados são divididos em conjuntos de treinamento e teste utilizando a função train_test_split do sklearn, onde 80% dos dados são usados para treinamento e 20% para teste. Eu defini o parâmetro random_state como 42 para garantir que os resultados sejam reprodutíveis.

Depois disso, eu criei um modelo de regressão logística utilizando a classe LogisticRegression do sklearn, e ajustei o modelo aos dados de treinamento utilizando o método fit. O modelo treinado foi então utilizado para fazer previsões nos dados de teste utilizando o método predict, e as previsões foram avaliadas em relação à variável alvo verdadeira utilizando a métrica de acurácia, que é a proporção de previsões corretas em relação ao total de previsões feitas.

Por fim, foi gerado um gráfico de dispersão das amostras de teste, onde as cores das amostras foram codificadas de acordo com as classes previstas pelo modelo de regressão logística. O gráfico foi plotado utilizando a biblioteca matplotlib, com o eixo x representando a primeira característica e o eixo y representando a segunda característica das amostras de teste. O título do gráfico foi definido como "Amostras de teste com cores das classes previstas".
