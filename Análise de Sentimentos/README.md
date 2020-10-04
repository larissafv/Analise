# Análise de Sentimentos pelo IBM Tone Analyser

## Resumo
O arquivo de Análise de Sentimentos pelo IBM Tone Analyser foi feito com base no repositório COVID-19_UCD_Chellenge e tweet-mood-analyzer, utilizando o Jupyter Notebook para o Python 3.8.2 64-bit e as bibliotecas: *pandas*, *ibm_watson*, *ibm_cloud_sdk_core.authenticators*, *numpy*, *random*, *re* e *sklearn.model_selection*. Os dados utilizados para análise são provenientes de um arquivo json com 5.000 tweets, todos escritos em português brasileiro no contexto pandêmico atual.

O objetivo desse Notebook foi estudar as possibilidades de se utilizar da ferramenta **IBM Tone Analyser** para a análise de sentimentos dos tweets coletados. Para esse fim, inicialmente foi feita uma limpeza nos textos. Logo após, foram selecionados 2.500 tweets aleatoriamente, uma vez que é a quantidade máxima aceita para o uso gratuito. As tabelas resultantes desses processos podem ser observadas no arquivo [Análise de Sentimento IBM Tone Analyser.ipynb](https://github.com/CDA-EPCWeb/Analise/blob/master/An%C3%A1lise%20de%20Sentimentos/An%C3%A1lise%20de%20Sentimento%20IBM%20Tone%20Analyser.ipynb).

## Execução do Código
Para executar o código, o arquivo 5k_origin.json deve estar na mesma pasta que o Análise de Sentimento IBM Tone Analyser.ipynb.
Ademais, o usuário deve criar uma conta no [IBM Cloud](https://cloud.ibm.com/registration?target=catalog%3fcategory=watson&cm_mmc=Earned-_-Watson+Core+-+Platform-_-WW_WW-_-intercom&cm_mmca1=000000OF&cm_mmca2=10000409&).

<img src="https://imgur.com/E9aqhQJ">

Depois disso, é necessário buscar pelo serviço Tone Analyser e se cadastrar. Dessa forma, o usuário terá a API key e URL para utilizar no código.

<img src="https://imgur.com/K54H8fh">
    
## Resultado
Após a análise da ferramenta, foi concluído que o **IBM Tone Analyser** não é adequado para a finalidade do projeto, uma vez que os tweets utilizados estão em português brasileiro e essa ferramenta, atualmente, só funciona para o inglês.
A possibilidade de se traduzir os textos para o inglês foi considerada, mas logo descartada, já que poderia haver perda de informações que influenciariam nos resultados da análise de sentimento.
