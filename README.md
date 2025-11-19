🌦️ Análise Climática de São Paulo – Data Science Project
---------------------------------------------------------------
🔍 Explorando tendências históricas, padrões meteorológicos e previsões futuras para a cidade de São Paulo.
-----------------------------------------------------------------------------------------------------------------
📘 Descrição do Projeto

Este projeto realiza uma análise detalhada dos dados climáticos históricos da cidade de São Paulo, utilizando ferramentas essenciais de análise de dados, visualização e modelagem preditiva.

O foco principal é compreender padrões de temperatura e precipitação ao longo dos anos, identificar extremos históricos e avaliar tendências futuras utilizando o modelo Prophet.

Todo o fluxo de trabalho foi desenvolvido em Python dentro de um Jupyter Notebook

🔧 Tecnologias Utilizadas

Python 3.x

Pandas

NumPy

Matplotlib

Prophet

Jupyter Notebook

---------------------------------------------------------------
📥 Dataset
O conjunto de dados utilizado contém informações meteorológicas, incluindo:

Temperatura (°C)

Índice de chuva (rain)

Data das observações

----------------------------------------------------------------------------------------
Processo de Análise
--------------------------------
 1. Carregamento e inspeção inicial

Verificação de colunas, padrões e integridade dos dados.

 2. Limpeza e tratamento

Foram encontrados valores nulos em rain, devidamente tratados.
Tipos ajustados, datas convertidas, outliers observados.

 3. Análise Exploratória (EDA)

Incluindo:
Estatísticas descritivas
Distribuições
Tendências ao longo dos anos
Boxplots mensais
Média anual de temperatura e chuva

 4. Extremos históricos identificados
    
Maior temperatura registrada
Menor temperatura
Maior volume de chuva
Menor chuva positiva registrada

5. Previsão com Prophet
   
Modelagem para projeção futura de temperatura e precipitação.

--------------------------------------------------------------------------

Conclusão da Análise (Modelo para prever os próximos 365 dias)
-----------------
A partir da modelagem com o Prophet, observamos tendências claras para os próximos anos na cidade de São Paulo:

🔺 Temperatura tende a aumentar
-
O modelo indica um crescimento gradual da temperatura média ao longo do tempo, refletindo um possível aquecimento contínuo na região.
<img width="885" height="588" alt="image" src="https://github.com/user-attachments/assets/cc172fc8-48c1-42c9-b8e5-0a6757e27b26" />


🔻 Precipitação tende a diminuir
-
A quantidade de chuva projetada mostra um padrão de queda, sugerindo períodos mais secos e menor frequência de precipitações intensas.
<img width="883" height="582" alt="image" src="https://github.com/user-attachments/assets/09b85aa4-8593-44e2-bef2-ae0f90e6765b" />


Essas tendências combinadas apontam para um cenário climático mais quente e menos úmido, alinhado com padrões globais de mudanças climáticas.
