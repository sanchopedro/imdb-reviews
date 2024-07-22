# Projeto Film Junky Union - Classificação de Resenhas de Filmes

![Film Junky Union](/img/film.png)

## Índice

1. [Como usar](#1-como-usar)
2. [Sobre o projeto](#2-sobre-o-projeto)
    - [Instruções do Projeto](#instruções-do-projeto)
    - [Descrição dos Dados](#descrição-dos-dados)
    - [Avaliação do Projeto](#avaliação-do-projeto)

## 1. Como usar

- Primeiramente, instale todas as dependências do projeto rodando no terminal o comando:

    ```bash
    pip install -r requirements.txt
    ```

- O arquivo [nltk-imdb.ipynb](nltk-imdb.ipynb) contém os códigos utilizados para a conclusão do projeto.
- O dataset do projeto pode ser encontrado na pasta [dataset](./datasets/imdb_reviews_part). 
    - **OBS:** Devido ao tamanho dos datasets, eles foram divididos em partes. O código realiza a concatenação dos dados.

## 2. Sobre o projeto

A Film Junky Union está desenvolvendo um sistema para filtrar e categorizar resenhas de filmes. O objetivo é criar um modelo capaz de detectar automaticamente resenhas negativas a partir de um conjunto de dados de resenhas do IMDB. O projeto visa classificar as resenhas como positivas ou negativas, com o objetivo de alcançar um valor F1 de pelo menos 0,85.

### Instruções do Projeto

1. **Carregamento dos Dados:** Carregar os dados das resenhas de filmes do IMDB.

2. **Pré-processamento dos Dados:** Pré-processar os dados, se necessário, para prepará-los para a modelagem.

3. **Análise Exploratória de Dados (AED):** Conduzir uma análise exploratória dos dados para entender o desequilíbrio de classe e outras características dos dados.

4. **Modelagem:** Treinar pelo menos três modelos diferentes para classificar as resenhas como positivas ou negativas.

5. **Teste dos Modelos:** Avaliar o desempenho dos modelos usando um conjunto de dados de teste e comparar os resultados.

6. **Avaliação e Conclusões:** Escrever resenhas próprias e classificá-las usando os modelos treinados, comparar os resultados e fornecer conclusões sobre as diferenças observadas.

### Descrição dos Dados

Os dados estão armazenados no arquivo `imdb_reviews.tsv`. (Baixe o conjunto de dados aqui)[https://practicum-content.s3.us-west-1.amazonaws.com/datasets/imdb_reviews.tsv]. O arquivo inclui o texto das resenhas, a polaridade (positiva ou negativa) e a parte do conjunto de dados (treinamento ou teste). Esses dados foram fornecidos por Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng e Christopher Potts em seu trabalho "Vetores de Aprendizado de Palavras para Análise de Sentimentos".

#### Campos Selecionados:

- `review`: Texto da resenha
- `pos`: Polaridade, '0' para negativo e '1' para positivo
- `ds_part`: 'train'/'test' para a parte de treinamento/teste do conjunto de dados

Existem outros campos no conjunto de dados. Sinta-se à vontade para explorá-los.

### Avaliação do Projeto

A avaliação do projeto considerará:

- Preparação correta dos dados
- Definição e treinamento dos modelos
- Obtenção de métricas satisfatórias
- Organização e limpeza do código
- Conclusões tiradas a partir dos resultados obtidos

Com estas diretrizes, desejo-lhe sucesso em seu projeto! Estou disponível para oferecer suporte adicional, se necessário. Boa sorte!
