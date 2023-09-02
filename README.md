# Paineis de dados - dashboards
Scripts e dados utilizados nos paineis da Rede Análise

# Dados de casos e óbitos de covid-19

Os dados mundiais são processados a partir dos dados agregados por país disponíveis em https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv. Os dados do Brasil são processados a partir dos dados agregados por estado disponíveis em https://covid.saude.gov.br 

Para o painel (disponível em http://bit.ly/Rede_CasosObitosTaxa), o script disponibilizado neste repositório faz o processamento e o cálculo da cobertura vacinal dos países (doses aplicadas / população), percentual de crescimento de casos notificados (a cada dia é calculado o número de casos do dia dividido pelo número de casos do dia anterior subtraído de 1)e o percentual de crescimento de óbitos notificados.

Todos os dados são processados de forma voluntária e então enviados para o Power BI através do apoio de MSF (Médicos Sem Fronteiras). 

Para citar o painel:
> SCHRARSTZHAUPT, Isaac; BRAGATTE, Marcelo; ROVATTI, Leonardo (Título: Painel Casos,óbitos e taxa de crescimento). Rede Análise/Serrapilheira. Acessado em XX/XX/XXXX. Disponível em: (http://bit.ly/Rede_CasosObitosTaxa)

# Dados de hospitalizações por covid-19 nos estados de SP (São Paulo) e RS (Rio Grande do Sul)

Os dados de SP são processados a partir dos dados agregados por DRS (Departamento Regional de Saúde) disponíveis em https://repositorio.seade.gov.br/dataset/b4bd5b75-0c6c-44d9-8fc4-9c5d9a480647/resource/6942bd81-a2d8-449b-9749-76f6e23d7ace/download/plano_sp_leitos_internacoes_serie_nova_variacao_semanal.csv.zip. Os dados do RS são processados a partir dos dados agregados por município disponíveis em https://covid.saude.rs.gov.br

Para o painel (disponível em http://bit.ly/Rede_HospitaisRSSP), os dados são enviados para o Power BI e disponibilizados em diversas visualizações. 

Todos os dados são processados de forma voluntária e então enviados para o Power BI através do apoio de MSF (Médicos Sem Fronteiras). 

Para citar o painel:
> SCHRARSTZHAUPT, Isaac; BRAGATTE, Marcelo. (Título: Painel Hospitais RS/SP). Rede Análise/Serrapilheira. Acessado em XX/XX/XXXX. Disponível em: (http://bit.ly/Rede_HospitaisRSSP)

# Dados de mobilidade e de sintomas 

Os dados de sintomas são processados a partir do script disponibilizado por Lucas Loezer em https://github.com/loezerl/covid19-worldsurverydata-brazil. Como os dados de sintomas pararam de ser atualizados em 25/06/2022, esta é a última data disponível. Os dados de sintomas vem da pesquisa CTIS (Covid Trends and Impacts Survey disponibilizada pela Universidade de Maryland em https://covidmap.umd.edu e entregue aos usuários através do Facebook (Meta) Health: https://dataforgood.facebook.com/dfg/tools/covid-19-trends-and-impact-survey

Os dados de mobilidade são processados a partir dos dados agregados por município disponíveis em https://www.google.com/covid19/mobility/. Como os dados de mobilidade pararam de ser atualizados em 15/10/2022, esta é a última data disponível. Mantemos o painel com os dados de legado.

Para o painel (disponível em http://bit.ly/Rede_MobilidadeSintomas), o script disponibilizado em https://github.com/loezerl/covid19-worldsurverydata-brazil faz a busca dos dados de sintomas e gera um CSV (disponível neste repositório) que então é enviado para os Power BI para a geração do painel. Para os dados de mobilidade, os dados são enviados para o Power BI e nele é feito o cálculo da média móvel de sete dias da mobilidade, cujo método de coleta pode ser conferido em https://support.google.com/covid19-mobility/answer/9825414?hl=pt-BR&ref_topic=9822927&sjid=15144141012337749010-SA 

Todos os dados são processados de forma voluntária e então enviados para o Power BI através do apoio de MSF (Médicos Sem Fronteiras). 

Para citar o painel:
> SCHRARSTZHAUPT, Isaac; BRAGATTE, Marcelo. (Título: Painel Google Mobility/Sintomas). Rede Análise/Serrapilheira. Acessado em XX/XX/XXXX. Disponível em: (http://bit.ly/Rede_MobilidadeSintomas)

