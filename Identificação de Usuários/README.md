# Identificação de Usuários

## Resumo
Os arquivos de identificação de usuários foram feitos utilizando o Jupyter Notebook para o Python 3.8.2 64-bit e as bibliotecas: *pandas* e *datetime*. Os dados utilizados para análise são provenientes do arquivo *tweets_222_23abr2020.json*, sendo todos tweets escritos em português brasileiro no contexto pandêmico atual.

Esses códigos foram estruturados a fim de apontar os usuários que mais tweetaram ou retweetaram em um determinado dia escolhido.

## Execução dos Códigos
Para executar os códigos, basta que o arquivo a ser lido esteja na mesma pasta que o Notebook em questão.

O usuário pode tomar a liberdade de escolher o dia e a quantidade de pessoas que gostaria de ver no resultado. Isso pode ser feito ao alterar as variáveis y e x na seguinte célula do código:
```
x = número inteiro de usuários
y = "data escolhida no formato ano-mês-dia"

# AVISANDO CASO UM DIA NÃO ESTEJA DISPONÍVEL NO CONJUNTO CARREGADO
if y not in days:
    print(y + ' não está disponível no conjunto de tweets analisados.')
    y = days[0]
    print('Definindo y como o primeiro dia disponível no banco de dados: ' + y)
```

## Resultado
Após a execução do código, os resultados serão apresentados em tabelas, logo abaixo das células executadas.
