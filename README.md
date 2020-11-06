# Pima Indians Diabetes Database
## Predict the onset of diabetes based on diagnostic measures

O objetivo geral do problema é prever se a pessoa possui ou não diabetes mellitus, com base em uma série de variáveis preditoras. O desafio foi posto declaradamente como um problema de aprendizagem.

O banco de dados possui todas suas observações constituídas de pessoas do gênero feminino, com idade superior a 21 anos, de ascendência do povo Pima (grupo de nativos norte-americanos). Os dados, que são atualmente abertos e gratuitos para download CC0 1.0, são provenientes do Instituto Nacional de Diabetes e Distúrbios Digestivos e do Rim (NIDDK) dos EUA e mantidos pela UC Irvine Machine Learning Repository (University of California-Irvine).	

Em essência, o conjunto de dados será analisado como um problema de inferência (dado que se tem uma variável resposta disponível), mas pode eventualmente ser tratado com um problema de predição, caso se queira utilizar o modelo para prever a condição de novos indivíduos, conforme entendimento de JAMES, HASTIE \& TIBSHIRANI (2013). 

Considerando a natureza categórica da variável resposta, o problema será, em princípio, um problema de classificação (em contraste com os problemas de regressão). No entanto, como reconhecem JAMES, HASTIE \& TIBSHIRANI (2013), essa distinção pode não ser muito clara quando se trabalha com variáveis resposta dicotômicas e se deseja estimar, por exemplo, probabilidades esperadas em um modelo de regressão logístico, ao invés de se desejar uma classificação/discriminação. Nesse sentido, como a utilização de modelos de regressão com respostas categóricas é uma das possibilidades a serem consideradas para a análise desses dados, o problema poderia ser tanto de classificação quanto de regressão. 

No que se refere ao tipo de aprendizagem, o conjunto das possíveis técnicas a serem utilizadas direciona o problema para que seja do tipo supervisionado. Dentre as muitas possibilidades, pode-se citar a própria regressão logística e a máquina de suporte vetorial support vector machine. Mas, como se tem disponível uma variável resposta, será também possível utilizar técnicas tipicamente não-supervisionadas (tais como a análise de agrupamentos ou clusters) com apoio de uma validação cruzada.


#####################################################

Endereço da Página do Problema

O conjunto dos dados, bem como outras informações, podem ser obtidos em:

https://www.kaggle.com/uciml/pima-indians-diabetes-database
