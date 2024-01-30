---
title: "Terrain Identification using Machine Learning"
excerpt: "Machine Learning - Terrain Identification using Long-Short-Term-Memory Network"
collection: portfolio
tags:
  - machine learning
  - artificial intelligence
  - healthcare
  - lstm
  - sequential modeling
---

![ImuData](/images/imu_data.png){: .align-center width="400px"}
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/vikrampande7/terrain-detection){:target="_blank"}

The ability to walk efficiently, safely, and attentively is a natural human trait that is disrupted by lower limb amputations. To restore basic walking function, amputees often rely on prosthetic devices. This project focuses on developing a system that identifies the terrain using data from inertial measurement units (IMUs) in the prosthetic leg.

The training data includes the following 4 classes: (0) indicates standing or walking on solid ground, (1) indicates going down the stairs, (2) indicates going up the stairs, and (3) indicates walking on grass. For different users, multiple sessions were conducted with a start time of 0. We combined all labels for visualization. It can be observed that there is a class imbalance with class 0 having the maximum number of instances.

Classification using sequential data was done using LSTM and its variants.


*Please refer to the GitHub repository for more details*
