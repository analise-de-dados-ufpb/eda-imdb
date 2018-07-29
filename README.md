# Análise exploratória de dados de filmes e seriados do IMDB

## Descrição da atividade

Você deve usar os dados de séries do IMDB para fazer uma análise exploratória de dados em uma série de sua escolha. A série deve ter pelo no mínimo 4 temporadas e 30 episódios. A análise deve ser um relatório em Rmarkdown, a partir do arquivo `R/eda-minha-serie.Rmd`. O relatório já possui algumas perguntas a serem respondidas. Use as perguntas como base, mas não fique preso a elas. Você pode fazer novas perguntas e novas análises à vontade.

O relatório deve ser legível e compreensível por alguém que não está na disciplina. Não precisa explicar como ler cada gráfico, mas tente ajudar a ver os resultados que você quer mostrar, e caso você use conceitos como IQR e desvio padrão, dê uma ajuda ao leitor.

Você deve fazer um Pull Request do arquivo Rmd e do HTML com o relatório até o prazo final da atividade.

## Descrição dos dados

O arquivo usado para avaliação está em `data/episodios_series_top.csv`. Estes dados foram gerados a partir de [dados disponíveis no IMDB](https://datasets.imdbws.com/). Cada linha do arquivo possui dados a respeito de um episódio de uma série. As colunas são as seguintes:

- `id_serie`: identificador da série.
- `id_episodio`: identificador do episódio.
- `nome_serie`: nome da série.
- `nome_episodio`: nome do episódio.
- `num_episodio`: número do episódio.
- `num_temporada`: número da temporada.
- `ano`: ano do episódio.
- `duracao_minutos`: duração do episódio em minutos.
- `generos`: gêneros do episódio.
- `avaliacao_media`: avaliação média do episódio pelos usuários do IMDB.
- `num_votos`: quantidade de votos (avaliações) pelos usuários do IMDB.


## Data source acknowledgement

Information courtesy of IMDb (http://www.imdb.com).
Used with permission.
Non-commercial use only.

Downloaded at: https://datasets.imdbws.com/
