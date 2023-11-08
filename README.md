# Previsao-de-Fluxo-de-Trafego

Dataset: https://archive.ics.uci.edu/dataset/734/traffic+flow+forecasting-1

O objetivo desse conjunto de dados é prever o volume de tráfego espaço-temporal com base no volume de tráfego histórico e outras características em locais vizinhos. Especificamente, <b>o volume de tráfego é medido a cada 15 minutos em 36 locais de sensores</b> ao longo de duas rodovias principais na região norte da Virgínia/Washington D.C. A região da capital dos Estados Unidos.

As 47 características incluem: 
- 1) a sequência histórica do volume de tráfego detectado nos 10 pontos de amostragem mais recentes (10 características),
- 2) dia da semana (7 características), 
- 3) hora do dia (24 características), 
- 4) direção da estrada (4 características), 
- 5) número de faixas (1 característica) e 
- 6) nome da estrada (1 característica).

O objetivo é prever o volume de tráfego 15 minutos no futuro para todos os locais de sensores. Com uma rede viária fornecida, conhecemos a conectividade espacial entre os locais de sensores.
