# Desafio-Data-Science

**Parte 1 - Diagramação de Dashboard e Widgets**
  - Crie uma representação visual de uma plataforma que tenha dashbords e widgets, usando alguma ferramenta do tipo.
Ex: Figma, Adobe XD ou outro.

  - Na representação deverá ter a exibição das seguintes INDICADORES:
    - Corrente Total;
    - Potência Reativa Fase;
    - Potência Reativa Total;
    - Potência Ativa Fase;
    - Potência Ativa Total;
    - Fator de potência Fase;
    - Fator de potência Total;
    - Energia Ativa Total;
    - Energia Reativa Total.

  - Poderá ser interativo ou estático, seja criativo(a).

  - A representação visual foi criada com Figma, e pode ser acessada através do link: https://www.figma.com/proto/Ss26c2Ci0pIqdLU0Aq4aPS/Untitled?node-id=8%3A228&scaling=scale-down&page-id=0%3A1&starting-point-node-id=8%3A228&show-proto-sidebar=1
  
**Parte 2 - Análise de Vibração**

  - Vibração e temperatura são variáveis que possibilitam identificar comportamentos de um equipamento, para esse desafio, usaremos um conjunto de dados de vibração e temperatura.

  - O documento para essa atividade consiste das seguintes condições:
    - 20 arquivos .csv
    - Dados de vibração e temperatura são de um motor tamanho pequeno
    - Potência do equipamento é 250 W
    - Ranger de armazenamento é de 1 em 1 hora
    - Tempo entre cada medição é menos de 1 minuto
    - Titulo do documento é composto de dois Timestamp (Início) - (Fim)

  - Os dados estão distribuídos em 4 colunas sendo elas:
    - Aceleração X
    - Aceleração Y
    - Aceleração Z
    - Temperatura

  - Utilizando os dados fornecidos de vibração e temperatura resolva os 3 pontos:

  1. Fazer a Análise Espectral do equipamento e identificar padrões entre coletas:
    1. Fast Fourier transform (FFT)   
    2. Harmônicos    

  2. Fazer um Algoritmo que calcula automaticamente:
    1. Quanto tempo o equipamento ficou **ligada (UPTIME)**
    2. Quanto tempo o equipamento ficou **desligada (DONWTIME)**
    
  3. Fazer sua análise sobre a condição do equipamento:
    1. Está desbalanceado? 
    2. Desalinhado? 
    3. Que condição se encontra ?

**Desafio Bônus - Montar gráfico com HTML, CSS e Javascript puro.**

  - Justificativa: A criação e personalização de gráficos no meio web é um diferencial importante no desenvolvimento e manutenção de dashboards.

  - Crie, utilizando apenas HTML, CSS e JS puro um gráfico de barras inspirado no gráfico abaixo. Não utilizar bibliotecas de gráficos Javascript ou CSS, como Echarts ou Chart.js.

  - Exibir dados:
    - 2015: 
      - Amazônia: 320,
      - Cerrado: 220,
      - Pantanal: 150,
      - Sertão: 98.
    - 2016: 
      - Amazônia: 332,
      - Cerrado: 182,
      - Pantanal: 232,
      - Sertão: 77.
  
  - Não é necessário consumir dados via API ou outros meios, apenas a exibição estática é suficiente.
  - Você é livre para definir as cores e tamanhos do gráfico, desde que os dados sejam exibidos proporcionalmente aos seus valores.
  - Deverá ser enviado os códigos HTML, CSS e JS via GitHub ou através do envio digital dos arquivos via formulário de entrega.
 
