## RoadAI
---

1.5% of Norwegian CO 2 emissions comes from construction
machines, so trucks transporting construction material and
equipment contribute to the industry’s overall carbon foot-
print. By harnessing truck activity data from a road con-
struction site in Viken county in the Oslo region, this work
aims to automate truck activity monitoring and anomaly de-
tection, by collecting kinematic and vibration data, process-
ing big data and training deep learning models. When driving
activity is monitored and its inefficiencies are identified, sus-
tainability can be achieved through direct emissions cuts, by
understanding operational norms and minimizing non-optimal
driving behaviour. This work delivers a combined big data
analytics and artificial intelligence solution, applied to a real-
world scenario in the road construction context. Kinematic
data is inferred from GPS tracking logs, while vibration data
is obtained from motion detecting sensors found in iPad edge
devices. Both data sources are reconciled, the vibration data
is aggregated at 5 seconds intervals before feeding into an au-
toencoder neural network where its reconstruction loss is mea-
sured. A loss threshold value is set at an arbitrary percentile of
all computed losses, and a sequence of observations is identi-
fied as abnormal if its loss exceeds this threshold. Finally, the
anomaly detection provides new insights to truck operations
and informs the decision maker about the vibration anomaly
for any given load-drive-dump cycle.
