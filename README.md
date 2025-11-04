![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/ComicDeath/Proton-Collision-Classifier/blob/main/Figuras/ilum_colorida.png)

<h1 align="center"> PCC - Proton Collision Classifier</h1>

O projeto PCC (Proton Collision Classifier) foi desenvolvido como projeto final da disciplina Aprendizado de Máquina por estudantes da Ilum - Escola de Ciências. O PCC é um sistema de aprendizado de máquina criado para prever o número de jatos de hádrons (nJets) produzidos em colisões de prótons, a partir de dados experimentais do detector CMS (Compact Muon Solenoid), localizado no CERN.

O projeto tem como objetivo explorar diferentes abordagens de classificação supervisionada, aplicando técnicas de pré-processamento, ajuste de hiperparâmetros e avaliação de desempenho para determinar o modelo mais eficiente.

# Modelos utilizados

Além de um modelo baseline simples utilizado como referência de desempenho, foram treinados e comparados cinco modelos de Machine Learning.

### `Árvore de Decisão (Decision Tree)`
Modelo interpretável que divide o espaço de decisão com base em limiares sucessivos das variáveis físicas

### `K-Nearest Neighbors (KNN)`
Modelo que classifica as amostras com base na proximidade entre elas no espaço multidimensional das variáveis experimentais.

### `Regressão Logística (Logistic Regression)`
Modelo estatístico utilizado para classificação, que calcula a probabilidade de cada classe com base em uma combinação linear das variáveis de entrada

### `Floresta Aleatória (Random Forest)`
Modelo estilo comitê composto de múltiplas árvores de decisão treinadas de forma aleatória

### `SVM (Support Vector Machine)`
Modelo que busca o melhor hiperplano de separação entre classes, utilizando diferentes kernels para capturar relações não lineares

# Instalação e como usar
Para usar o projeto, deve-se clonar esse repositório em sua máquina e abri-lo em uma IDE compatível com arquivos do tipo ipynb. Depois, basta abrir o arquivo `Proton-Collision-Classifier.ipynb` para ler o notebook contendo a introdução teórica, o tratamento de dados, o treino dos modelos, discussão dos resultados e a conclusão que obtivemos nesse trabalho.

Caso seja do seu interesse, a pasta `Dataset` contém o conjunto de dados utilizado neste projeto, a pasta `Estudos do Optuna` reúne os arquivos .db referentes à otimização de hiperparâmetros, e a pasta `Figuras` armazena as imagens do trabalho.

# Construído com
- **Python** - linguagem de programação principal do projeto;
- **HTML** - linguagem utilizada no markdown do trabalho;
- **ScikitLearn** - biblioteca de aprendizado de máquina usada para criação, treinamento e avaliação dos modelos; 
- **Optuna** - framework de otimização de hiperparâmetros; 
- **Pandas** e **Numpy** -  bibliotecas empregadas para tratamento dos dados;  
- **Seaborn** e **Matplotlib** - bibliotecas de visualização utilizadas para gerar gráficos e análises dos resultados.

# Equipe
O projeto foi desenvolvido pela equipe **Os Apanhadores no Campo de Hádrons**, composta por uma dupla de estudantes cursando o segundo semestre do bacharelado em Ciência e Tecnologia oferecido pela Ilum Escola de Ciências - instituição de ensino superior do CNPEM.

- [**Brenda Laube Abrunhosa**](https://github.com/blabrunhosa)
* Responsável pelos modelos KNN, Regressão Logística e Floresta Aleatória;
* Responsável pela conclusão;
* Auxiliou na discussão dos resultados e no processo de guiar o leitor.

- [**João Henrique de Lima Gasquez**](https://github.com/ComicDeath)
* Responsável pelos modelos de Árvore de Decisão, SVM e Baseline;
* Responsável pela introdução;
* Responsável pelo tratamento de dados;
* Auxiliou na discussão dos resultados e no processo de guiar o leitor;
* Escreveu o README.

![Brasão da Guilda](https://github.com/ComicDeath/Proton-Collision-Classifier/blob/main/Figuras/brasao.png)

“Cada colisão conta uma história!”
  
# Docente
A matéria de Aprendizado de Máquina foi ministrada por:
- **Profº Dr. Daniel Roberto Cassar**
  
# Licença
Distribuído sob a licença GNU General Public License 3.0, cheque `LICENSE` para mais informações.

## Referências para a construção do README
 ROCKETSEAT. **Como fazer um bom README.** Disponível em: https://blog.rocketseat.com.br/como-fazer-um-bom-readme/. Acesso em: 2 de novembro de 2025.

![ILUM, CNPEM, MINISTÉRIO DA EDUCAÇÃO](https://github.com/ComicDeath/Proton-Collision-Classifier/blob/main/Figuras/ilum.png)
