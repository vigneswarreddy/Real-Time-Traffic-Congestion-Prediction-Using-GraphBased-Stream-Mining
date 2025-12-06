Predicting congestion in urban traffic in real time involves processing data streams in
real time, finding features that appear to be time-consistent, and assessing models that
must be deployed in realistic situations. The current work builds a streaming congestion
forecasting model based on the NYC Yellow Taxi Trip data, in which pickup events of
taxis are mapped to a spatial grid tile and grouped into time fixed windows. To maintain
causal integrity, leakage-free temporal attributes such as lagged duration, exponential
moving averages, past frequency of congestion and contextual time are calculated. The
congestion states are considered dynamic and adaptive in every window basing on
dynamically accepted percentile threshold to accommodate the changes in the traffic
patterns. Various machine learning models are trained and simulated and then a
sequential and window based deployment simulation is carried out. Logistic
Regression shows the most consistent real-time performance, with an approximate F1-
score of 0.458 and it is better than an online baseline model. The results indicate that
temporal causality and streaming assessment are vital in the application of scalable
congestion forecast systems to support smart transport systems.
Keywords: Real-Time Congestion Prediction, Streaming Machine Learning, Spatial
Tiling, Temporal Feature Engineering, Leakage-Free Modeling, Urban Traffic
Analytics.
