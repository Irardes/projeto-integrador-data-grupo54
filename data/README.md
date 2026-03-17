# Base de Dados

No momento, arquivo documenta as partes 1 e 2 do projeto.

## Arquivo local

- Nome do arquivo: `base_dados.csv`
- Local: data\base_dados.csv
- Situacao atual: base organizada

## Validacao da estrutura

- Quantidade de linhas: 6234
- Quantidade de colunas: 12

### Colunas identificadas

- `show_id`: identificador único de cada título na base.
- `type`: tipo do conteúdo.
- `title`: nome do filme ou da série.
- `director`: diretor ou diretores do título.
- `cast`: elenco principal.
- `country`: país ou países associados à produção.
- `date_added`: data em que o título foi adicionado à plataforma.
- `release_year`: ano de lançamento original do conteúdo.
- `rating`: classificação indicativa.
- `duration`: duração do conteúdo. Em filmes, está em minutos; em séries, em número de temporadas.
- `listed_in`: categoria/gêneros do título.
- `description`: resumo curto do conteúdo.

## Procedencia do arquivo local

Para viabilizar, o placeholder anterior foi substituido por um CSV baixado do Kaggle.
Link utilizado para download: https://www.kaggle.com/datasets/shivamb/netflix-shows?resource=download

## O que ja foi feito

- O placeholder anterior em `data/base_dados.csv` foi substituido por uma base real em CSV
- A estrutura do arquivo foi validada
- A base foi mantida em estado bruto, sem alteracoes no conteudo
- Documentaão foi criada para registrar a situação da base

## O que ainda nao foi feito

- Limpeza de dados
- Tratamento de valores nulos
- Padronizacao de formatos
- Transformacao de colunas
- Analise exploratoria
- Geracao de graficos
- Analise de metricas
- Construcao do dashboard

## Proximas etapas previstas

- Verificar valores nulos e inconsistencias
- Padronizar formatos relevantes para analise
- Preparar recortes por tipo, genero e ano
- Desenvolver as metricas e visualizacoes planejadas