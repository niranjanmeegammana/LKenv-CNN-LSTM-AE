# LKenv-CNN-LSTM-AE
  Spatiotemporal Anomaly Detection For Environmental Hazards In Sri Lanka Using Cnn-Lstm Autoencoders

N.W. Meegammana¹*, H. Fernando², N.P. Vishva Kumara²*
¹Faculty of Computing, Sri Lanka Institute of Information Technology, Malabe, Sri Lanka
 ²Faculty of Computing, Sri Lanka Institute of Information Technology, Malabe, Sri Lanka
 

Abstract: Environmental hazards such as floods, cyclones, and landslides pose significant threats to lives and livelihoods in Sri Lanka, particularly under worsening climate conditions. Traditional forecasting methods face challenges due to limited labeled data, high spatiotemporal variability, and the lack of integrated satellite observations. This study introduces an unsupervised spatiotemporal anomaly detection framework based on a Convolutional Long Short-Term Memory (CNN-LSTM) Autoencoder to identify environmental anomalies associated with disaster events. The model is trained exclusively on non-disaster sequences, combining daily weather data with satellite-derived brightness features, aligned using an 8-day sliding window. It demonstrated moderate performance, achieving an F1-score of 0.41, with detected anomaly clusters spatially aligned with known high-risk regions. Unlike supervised models, this approach detects hazards without the need for labeled data, offering practical advantages for early warning in data-scarce environments. The study also highlights key limitations in existing public disaster datasets, such as insufficient spatial resolution and lack of real-time ground-truth data. Future work will focus on acquiring higher-resolution and real-time data sources, integrating attention mechanisms for better temporal modeling, exploring multi-model late fusion strategies, and aligning the system with national early warning infrastructures to enhance disaster resilience and adaptive response.

