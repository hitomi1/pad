# Processamento Analítico de Dados
----------
| Alunso | Nusp |
| -------------- | --------------- |
| Gustavo Hitomi da Silva | 11801202 |
| Carlos Filipe De Castro Lemos | 12542630 |
| Thiago Heenrique dos Santos Cardoso | 11796594 | 
| Vinicius de Moraes | 13749910 | 



[Dataset - Brazilian E-commerce by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
Possíveis segundos datasets:

IBGE - cruzar os dados dos clientes com informações de renda, escolaridade e população por estado ou cidade.

IDH - análises sobre comportamento de consumo por nível de desenvolvimento das cidades. 

Frete - comparar o tempo de frete entre loja e consumidor e cotar o frete nos correios ou qualquer outro serviço de frete e descobrir possíveis gargalos financeiros e/ou de tempo de entrega

- Tema geral do trabalho.
Análise de Ecommerce no Brasil

- Pelo menos 3 assuntos de interesse (ou processos de negócio).
o Sinônimos para assuntos de interesse: foco de interesse, métrica ou
medida numérica (no nível conceitual), fatos (no nível lógico). 

1 - Entender qual o estado que consome mais (ROLL UP)
2 - Entender qual o local que possui o frete mais caro (caso formos usar os dados de frete)
3 - Entender se há relação entre IDH com pedidos online
4 - Entender se há relação de pedidos online X dados demográficos (idade, sexo, localização, classe social, etc)
5 - Quais são os meses com mais consumo (DRILL DOWN)

Tentar conseguir dados demográficos por cidade.

- Pelo menos 2 esquemas estrela, usando como base os assuntos de interesse. Na
proposta dos esquemas estrela, deve-se ter em mente a posterior criação de
pelo menos 1 constelação de fatos.

Criar depois


- Pelo menos 2 fontes de dados, os quais representam fontes de dados que serão
usados para popular a aplicação a ser desenvolvida. É permitida a geração de
dados sintéticos caso necessário. Entretanto, é fortemente indicado o uso de
dados reais e volumosos.
o É necessário usar, pelo menos, duas fontes de dados.
o As fontes de dados podem ser obtidas da mesma plataforma/repositório. 

https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9088-produto-interno-bruto-dos-municipios.html?=&t=downloads
https://www.kaggle.com/datasets/silveiragustavo/ibge-censo-cep-coordenadas-renda-per-capita?select=cep_coordinates_per_capita_income.csv
https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce/data?select=olist_orders_dataset.csv

- Pelo menos 5 principais consultas a serem respondidas.
o As consultas devem ser especificadas de acordo com os aspectos
dinâmicos do modelo de dados multidimensional. 
• Pelo menos 2 consultas roll-up ou drill-down.
• Pelo menos 1 consulta slice and dice, podendo ser apenas slice, apenas dice
ou slice and dice.
• Pelo menos 1 consulta pivot.
• Pelo menos 1 consulta drill-across.
