### PROBLEMA

Uma gestora de uma empresa de tecnologia deseja promover maior igualdade salarial entre os funcionários e elaborar planos de carreira individuais. Nesse contexto, a gestora solicitou análises específicas sobre as disparidades salariais, com ênfase na equidade de gênero, níveis de senioridade e anos de experiência.

Entregue as seguintes informações para a gestora:

✔ Distribuição do nº de funcionários, de acordo com gênero, nível de senioridade e nível de formação<br>
✔ Evolução média salarial ao longo do tempo, com base na data de último aumento<br>
✔ Distribuição salarial por nível de senioridade e gênero<br>
✔ Distribuição salarial por anos de experiência e gênero<br>

Com base nisso, ela tomará decisões importantes para a empresa. 

Fonte dos dados: 
State of Data Brazil 2021 - O maior e mais completo mapeamento do mercado brasileiro de dados.

### EXECUÇÃO

##### Arquivos

data/raw.csv: Base de dados original.<br>
exploratory.ipynb: Notebook para explorar os dados, assim como verificar tipagens e tratativa de valores nulos.<br>
analysis.ipynb: Notebook contendo o código para analisar os dados de acordo com a demanda da gestora de RH.<br>
reports/reports.md: Visualização os gráficos gerados, junto com a conclusão final da análise.<br>

##### Ferramentas/Requerimentos
Python<br>
Pandas<br>
Matplotlib<br>
Seaborn<br>

### CONCLUSÃO

De acordo com os dados informados e com a análise realizada, foi possível identificar que:

70% dos funcionários são do gênero masculino;<br>
35,74% são pós-graduados, sendo a maior parcela de formação;<br>
31,76% são gestores, enquanto 11,98% são de senioridade Junior.<br>

Apenas a média salarial Masculina recebeu um avanço considerável (+18,7%) de 2021 para 2022, recuando novamente em 2023.<br>
Por outro lado, a média salarial Feminina recuou -3,75%, tornando o príodo de 2022 com a maior desigualdade salarial entre gêneros.<br>

A senioridade que mais apresenta desigualdade na remuneração é na cadeira Senior, com uma média de R$ 14.592,19 para os homens e R$ 12.386,36 para as mulheres, tendo uma diferença de 17,80% a mais para os Seniors masculinos.<br>

Na mesma linha, a maior desigualdade está presente aos profissionais com mais de 10 anos de mercado (tempo condizente com a desigualdade encontrada no nível Senior). Para esse cenário, a média feminina é de R$ 15.083,33 enquanto a masculina é de R$ 17.449,43, representando uma diferença de 15,68% a mais na folha de pagamento.

### Créditos

Atividade criada e proposta por Luani R. O. Piva - https://www.linkedin.com/in/luanipiva/
