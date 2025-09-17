---
title: "Time-series forecasting of microbial fuel cell energy generation using deep learning"
collection: publications
permalink: /publication/2025-time-series-forecasting
excerpt: "Promising work on predicting energy generation in microbial fuel cells. [Read the paper here](https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1447745/full)."
date: 2025-01-20
venue: 'Frontiers in Computer Science, Human-Media Interaction'
paperurl: 'http://stevegtaylor.github.io/files/time-series-forecasting.pdf'
---

Soil microbial fuel cells (SMFCs) are an emerging technology which offer clean and renewable energy in environments where more traditional power sources, such as chemical batteries or solar, are not suitable. With further development, SMFCs show great promise for use in robust and affordable outdoor sensor networks, particularly for farmers. One of the greatest challenges in the development of this technology is understanding and predicting the fluctuations of SMFC energy generation, as the electro-generative process is not yet fully understood. Very little work currently exists attempting to model and predict the relationship between soil conditions and SMFC energy generation, and we are the first to use machine learning to do so. In this paper, we train Long Short Term Memory (LSTM) models to predict the future energy generation of SMFCs across timescales ranging from 3 min to 1 h, with results ranging from 2.33 to 5.71% Mean Average Percent Error (MAPE) for median voltage prediction. For each timescale, we use quantile regression to obtain point estimates and to establish bounds on the uncertainty of these estimates. When comparing the median predicted vs. actual values for the total energy generated during the testing period, the magnitude of prediction errors ranged from 2.29 to 16.05%. To demonstrate the real-world utility of this research, we also simulate how the models could be used in an automated environment where SMFC-powered devices shut down and activate intermittently to preserve charge, with promising initial results. Our deep learning-based prediction and simulation framework would allow a fully automated SMFC-powered device to achieve a median 100+% increase in successful operations, compared to a naive model that schedules operations based on the average voltage generated in the past.

[Download Paper](http://stevegtaylor.github.io/files/time-series-forecasting.pdf)

*Adam Hess-Dunlop, Harshitha Kakani, **Stephen Taylor**, Dylan Louie, Jason Eshraghian, Colleen Josephson*