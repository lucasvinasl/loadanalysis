# Load Analysis / Análise de memória de massa

**Por motivos de segurança, não estou disponibilizando os arquivos xls que foram disponibilizados pela concessionária de energia.**

**For security reasons, I am not making available the xls files that were made available by the energy company.**


ENG:

**Mass memory/load analysis of a university. Load analysis of a university.**

_The xls file looks like this_:

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/c980e75f-3934-45be-a5c3-8f01d8c08547)


This code was developed with the aim of carrying out a simple data analysis based on mass memory reports for the months of 2022 issued by the energy concessionaire Neoenergia COSERN for the Federal Rural University of the Semiarid - UFERSA East campus, this report contains information such as active and reactive power, in addition to the variation in the power factor throughout the day, readings are taken every 15 minutes, so for a month of 30 days we have approximately 2880 records.

From the report it was possible to carry out two analyses: Load behavior and Power Factor behavior.

The objective of this analysis was based on:
- Check demand behavior throughout the day: Plot a graph of every day of the month, for each month, for
- Check any demand/load pattern: Peak load times, where the load is lower during the day, etc.
- Check the curve W x Var Ind x Var Cap x Time
- Tip and Off-tip power factor

The project was simple, I used the basic libraries: Pandas and Matplotlib.

I leave below some graphs that were obtained from the analysis. I will soon post the formatted article that will be better for the understanding and objectives of this analysis.

**P(kW) x Hour:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/d6a50e00-6eaf-4746-bcf4-84981fce4669)

**P(kW) - Inside Hour:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/e2e20371-c081-41a2-bab1-c2c84f9992cb)

**P(kW) - Outside Hour:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/d4da1207-a970-40b0-92db-0ed652114cd0)

**P(kW) x x Q(kVar):**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/72bcfbab-88d8-4d43-a368-927bc1e9371a)


PR-BR:

**Análise de memória de massa/carga de uma universidade. Load analysis of a university.**

_O arquivo xls tem essa cara_ :

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/c980e75f-3934-45be-a5c3-8f01d8c08547)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
**PT-BR**
Esse código foi desenvolvido com o intuito de fazer uma simples análise de dados tendo como base relatórios de memória de massa dos meses de 2022 emitidos pela concessionária de energia Neoenergia COSERN para a Universidade Federal Rural do Semiárido - UFERSA campus Leste, esse relatório contém informações como potência ativa e reativa, além da variação do fator de potêncai ao longo do dia, as leituras são realizadas a cada 15 minutos, então para um mês de 30 dias temos aproximadamente 2880 registros.

A partir do relatório foi possível realizar duas análises: O comportamento da Carga e o comportamento do Fator de potência.

O objetivo dessa análise se baseou em: 
- Verificar o comportamento da demanda ao longo do dia: Plotar o gráfico de todos os dias do mês, para cada mês,para
- Verificar algum padrão de demanda/carga: Horários de pico de carga, onde a carga é menor durante o dia, etc.
- Verificar a curva W x Var Ind x Var Cap x Tempo
- Fator de potência Ponta e Fora ponta

O projeto foi simples, utilizei as bibliotecas básicas: Pandas e Matplotlib.

Deixo abaixo alguns gráficos que foram obtidos a partir da análise. Em breve irei postar o artigo formatado que será melhor para o entendimento e objetivos dessa análise.

**P(kW) x H:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/d6a50e00-6eaf-4746-bcf4-84981fce4669)

**P(kW)  - Ponta:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/e2e20371-c081-41a2-bab1-c2c84f9992cb)

**P(kW)  - Fora Ponta:**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/d4da1207-a970-40b0-92db-0ed652114cd0)

**P(kW) x  x Q(kVar):**

![image](https://github.com/lucasvinasl/loadanalysis/assets/74206824/72bcfbab-88d8-4d43-a368-927bc1e9371a)


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
