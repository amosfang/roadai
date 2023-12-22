## RoadAI (NORA)
---

1.5% of Norwegian CO 2 emissions comes from construction machines, so trucks transporting construction material and equipment contribute to the industry’s overall carbon footprint. By harnessing truck activity data from a road construction site in Viken county in the Oslo region, this work aims to automate truck activity monitoring and anomaly detection, by collecting kinematic and vibration data, processing big data and training deep learning models. When driving activity is monitored and its inefficiencies are identified, sustainability can be achieved through direct emissions cuts, by understanding operational norms and minimizing non-optimal driving behaviour. This work delivers a combined big data analytics and artificial intelligence solution, applied to a real-world scenario in the road construction context. Kinematic data is inferred from GPS tracking logs, while vibration data is obtained from motion detecting sensors found in iPad edge
devices. Both data sources are reconciled, the vibration data is aggregated at 5 seconds intervals before feeding into an autoencoder neural network where its reconstruction loss is measured. A loss threshold value is set at an arbitrary percentile of all computed losses, and a sequence of observations is identified as abnormal if its loss exceeds this threshold. Finally, the anomaly detection provides new insights to truck operations and informs the decision maker about the vibration anomaly
for any given load-drive-dump cycle.

This work produced an autoencoder that predicted anomalies.

My key takeaways

| Skills    | Status |
| -------- | ------- |
| Pyspark for data ingestion  | Success    |
| Pyspark for data processing | Success     |
| PySpark ML K-means clustering   | Success    |
| PySpark ML Gaussian mixture model    | Success    |
| Keras Tensorflow Autoencoder   | Success    |
| Keras Tensorflow Variational Autoencoder   | Success    |
