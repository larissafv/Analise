# Unigramas e Bigramas

## Resumo
Os arquivos de análise de unigramas e/ou bigramas foram feitos utilizando o Jupyter Notebook para o Python 3.8.2 64-bit e, em geral, as bibliotecas: *pandas*, *nltk*, *string*, *IPython.display*, *collections* e *re*. Os dados utilizados para análise são provenientes de diferentes arquivos json com um número variado de tweets, todos escritos em português brasileiro no contexto pandêmico atual.

Esses códigos foram estruturados a fim de observar a frequência de unigramas ou bigramas. Para isso, além da contagem de ocorrências, também é feita uma limpeza nos tweets.

### distanciamentosocial_por_dia.ipynb
Esse Notebook faz o levantamento da frequência do bigrama “distanciamento social” nos 5.000 tweets avaliados.

### retweets_unigramas_bigramas.ipynb
Esse Notebook faz o levantamento da frequência de unigramas e bigramas mais recorrentes nos retweets avaliados. Na última versão rodada do código, 100.000 dos retweets do arquivo fonte foram utilizados.

### tweets-bigramas.ipynb
Esse Notebook faz o levantamento da frequência de bigramas mais recorrentes nos tweets avaliados. Na última versão do código, foi utilizado um arquivo fonte teste, por isso, é necessário fazer a troca do nome na primeira célula antes de rodá-lo.

```
dados = pd.read_json('nomedoarquivo.json', convert_dates = False, lines = True, chunksize = 50)
```

## Execução do Código
Para executar o código, os arquivos a serem lidos devem estar na mesma pasta que o Notebook em questão.

## Resultado
Após a execução do código, os resultados serão registrados em arquivos csv.

Vale ressaltar que nem todos os arquivos por nós utilizados contêm uma quantidade suficiente de dados para uma análise mais apropriada.
