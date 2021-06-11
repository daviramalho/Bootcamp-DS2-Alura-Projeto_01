![Capa README](reports/figures/projeto_01/Capa_README.png "Capa do README")

### Resumo:

O módulo 01 do Bootcamp de Data Science Aplicada da Alura nos aproximou da análise de dados reais do DATASUS com a ajuda do Python e Pandas para limpeza e tratamento dos dados, possibilitando então a análise exploratória dos mesmos com o suporte do Matplotlib.

No módulo investigamos as despesas do SUS no território nacional a partir dos registros dos atendimentos e do processamento dos mesmos. As oscilações recorrentes desses registros nos levaram a investigar se havia alguma relação entre os picos de despesas e os picos de ocorrências de dengue. Afinal constatamos que existe uma aparente relação entre entre as despesas e as ocorrências sazonais de picos de dengue. Também foi possível perceber, em paralelo, como se manifestavam as despesas quando relacionadas com o tamanho da população de cada estado.

Nesse cenário preliminar surgiram algumas questões de interesse para investigação e aprofundamento:
- Qual o cenário **GERAL**, nos últimos anos, da relação entre despesas do SUS e o registro da população efetivamente atendida em cada Estado e Região do País? Qual a média de custo por habitante atendido em cada estado e região? Qual o comportamento dos dados quando comparamos os dados do Ceará com os 5 estados com maiores despesas do Brasil? Como se comporta o Ceará em relação a média do Nordeste?

------
### Fontes de dados:

- [DATASUS](http://www2.datasus.gov.br/DATASUS/index.php?area=0202&id=11633&VObj=http://tabnet.datasus.gov.br/cgi/deftohtm.exe?sih/cnv/qi)
- [IntegraSUS-CE](https://integrasus.saude.ce.gov.br/#/indicadores) (Dicionário dos dados: [GitHub](https://github.com/integrasus/api-covid-ce))
- [Brasil.IO](https://brasil.io/home/)
- IBGE - [Dados quantitativos](https://ftp.ibge.gov.br/) e [Dados Geoespaciais](https://geoftp.ibge.gov.br/)

------
### Objetivos:

O presente estudo busca identificar o tipo de ocorrência que levou a mais despesas do SUS no país nos últimos 10 anos, comparando com as despesas promovidas pelo Covid-19 entre fevereiro de 2011 e fevereiro de 2021, buscando espacializar esses dados no território da Região Metropolitana de Fortaleza.

------
### Conclusões:

Por restrições de tempo e de modo a não prejudicar o andamento dos módulos seguintes do Bootcamp decidiu-se interromper o presente projeto. Nos dados analisados percebeu-se que o estado do Ceará teve um aumento de despesas com saúde entre os anos de 2011 e 2016 de 18% enquanto os registros apresentam uma redução de despesas entre 2016 e 2021 na ordem de 26%.

Os atendimentos realizados em fevereiro de 2011 totalizavam 41.111 atendimentos, tendo posteriormente apresentado uma redução de 7% em atendimentos realizados no mês de fevereiro de 2016, com 38.528 atendimento, e mais uma redução de 39% do número de atendimentos entre fevereiro de 2016 e fevereiro de 2021, totalizando 23.559 atendimentos nesse último período.

É necessário salientar que as bases de dados mais recentes podem não estar completamente atualizadas, o que justificaria a grande redução de despesas e atendimentos registrados no último ano. Pesquisas posteriores poderão explicitar melhor as razões para estes resultados bem como atender às espectativas iniciais da pesquisa.

------

<div align = "center">
<div>
<img src = "reports/figures/alura_logo.jpeg" alt = "Logo_Alura" width = "50" /></div>
</div>

by Davi Ramalho
