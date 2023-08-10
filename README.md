## TweetParser
TweetParser é um conjunto de notebooks para análise de tweets. Inclui a leitura e preparação dos dados, contagem de tweets por usuário e filtragem de notícias e bots. Realiza limpeza de texto, conversão de emojis e remoção de palavras-chave. A modelagem de tópicos é feita usando LDA, com visualização interativa. 

### Bibliotecas
- NLTK;
- Gensim;
- WordCloud;
- spaCy;
- pyLDAvis;
- botometer;
- emoji.

### Bases de Dados
A base de tweets coletados e utilizados no projeto está no diretório data. 

### Notebooks
tweets_scraping: Raspagem de tweets com a biblioteca snscrape.<br>
botometer_analysis: Verifica se as contas de usuários no Twitter são robôs ou pessoas reais. Retorna uma nota para cada conta, que mostra o quão provável é que seja um robô.<br>
emoji_analyzer: Analisa emojis, conta a ocorrência de palavras alegres e tristes em cada tweet.<br>
tweets_analyzer: Analisa os tweets coletados realizando pré-processamento, filtragem de notícias e bots, modelagem de tópicos com LDA e visualização interativa.




