# Projeto Film Junky Union - Classificação de Resenhas de Filmes

![Film Junky Union](/img/film.png)

A Film Junky Union está lançando uma nova comunidade para entusiastas de filmes clássicos e está desenvolvendo um sistema para filtrar e categorizar resenhas de filmes. O objetivo é treinar um modelo capaz de detectar automaticamente resenhas negativas. Utilizando um conjunto de dados de resenhas de filmes do IMDB rotuladas com polaridade, o projeto busca criar um modelo para classificar as resenhas como positivas ou negativas, visando atingir um valor F1 de pelo menos 0,85.

## Instruções do Projeto

As instruções para o projeto incluem as seguintes etapas:

1. Carregamento dos Dados: Carregar os dados das resenhas de filmes do IMDB.

2. Pré-processamento dos Dados: Pré-processar os dados, se necessário, para prepará-los para a modelagem.

3. Análise Exploratória de Dados (AED): Conduzir uma análise exploratória de dados para entender o desequilíbrio de classe e outras características dos dados.

4. Modelagem: Treinar pelo menos três modelos diferentes para classificar as resenhas de filmes como positivas ou negativas.

5. Teste dos Modelos: Avaliar o desempenho dos modelos usando um conjunto de dados de teste e comparar os resultados.

6. Avaliação e Conclusões: Escrever resenhas próprias e classificá-las usando os modelos treinados, comparando os resultados e fornecendo conclusões sobre as diferenças observadas.

## Descrição dos Dados

Os dados estão armazenados no arquivo `imdb_reviews.tsv`. (Baixe o conjunto de dados aqui)[https://practicum-content.s3.us-west-1.amazonaws.com/datasets/imdb_reviews.tsv], que inclui o texto das resenhas, a polaridade (positiva ou negativa) e a parte do conjunto de dados (treinamento ou teste). Eles foram fornecidos por Andrew L. Maas, Raymond E. Daly, Peter T. Pham, Dan Huang, Andrew Y. Ng e Christopher Potts em seu trabalho "Vetores de Aprendizado de Palavras para Análise de Sentimentos".

- Aqui estão a descrição de alguns dos campos selecionados:

    - `review`: o texto da resenha

    - `pos`: o objetivo, '0' para negativo e '1' para positivo

    - `ds_part`: 'train'/'test' para a parte de treinamento/teste do conjunto de dados, respectivamente

Existem outros campos no conjunto de dados. Sinta-se à vontade para explorá-los se quiser.

## Avaliação do Projeto

A avaliação do projeto considerará diversos critérios, como a correta preparação dos dados, a definição e treinamento dos modelos, a obtenção de métricas satisfatórias, a organização e limpeza do código, além das conclusões tiradas a partir dos resultados obtidos.

Com estas diretrizes, desejo-lhe sucesso em seu projeto! Estou disponível para oferecer suporte adicional, se necessário. Boa sorte!