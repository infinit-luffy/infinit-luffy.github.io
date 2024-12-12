---
title: "Stock Trading Strategies Based on Predictive Reinforcement Optimization and Past Historical Event Trends"
collection: publications
excerpt: 'This paper is about the Stock trading and reinforcement learning'
date: 2024
venue: 'Expert Systems With Applications'

---

This work is under review on Expert Systems With Applications

Abstract:
Stock trading with deep reinforcement learning has gained widespread attention due to its ability to dynamically make decisions by simply looking into the stock data.
Typically, stock trading agents use a short-term window of recent data as the state to keep the freshness of information and reduce processing time. 
However, without fully exploiting the prior information from market data makes this approach is susceptible to market fluctuations.
While incorporating predictive losses to constrain reinforcement learning algorithms can help reduce such fluctuations to some extent, current methods rely on a single vector for both prediction and decision-making, which limits the decision vector space.
Also, predictive information is not taken into account which can give us a future insight and help exploration.
To solve those problems, this paper presents a novel stock trading framework that integrates patterns analysis of long-term past data and supervised prediction constraints into deep recurrent Q-learning to achieve robust decision-making. 
Firstly, considering the stationary of data, we adopt a Short-time Fourier transform along with a convolutional neural network to extract the frequency features of the long-term past stock price as the initial hidden state for the recurrent neural network. 
This alleviates fluctuations by regulating the model with past patterns.
Second, considering the limitation of the decision vector, we derive predictions from the RNN's outputs at each time step and use a separate vector for decision-making.
By separating the prediction and decision vectors, our model enhances environmental perception under supervisory constraints while reducing limitations on the decision vector space.
Finally, considering the lack of utilization of predictive information, we incorporate predicted data for decision-making to give the model a future insight, while using prediction loss as an intrinsic curiosity-driven reward to encourage exploration.
Compared to the state-of-the-art methods, our method demonstrates superior performance in 49 out of 52 datasets and yields higher returns.



