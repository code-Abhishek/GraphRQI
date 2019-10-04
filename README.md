# GraphRQI
Codebase for our ICRA 2020 submission, [**GraphRQI: Classifying Driver Behaviors Using Graph Spectrums**](https://gamma.umd.edu/graphrqi).<br>
Authors: Rohan Chandra, Uttaran Bhattacharya, Trisha Mittal, Xiaoyu Li, Aniket Bera, Dinesh Manocha.

<img src="img/cover.png">

#### Abstract

We present a novel algorithm (GraphRQI) to identify driver behaviors from road-agent trajectories. Our approach assumes that the road-agents exhibit a range of driving traits, such as aggressive or conservative driving. Moreover, these traits affect the trajectories of nearby road-agents as well as the interactions between road-agents. We represent these inter-agent interactions using unweighted and undirected traffic graphs. Our algorithm classifies the driver behavior using a supervised learning algorithm by reducing the computation to the spectral analysis of the traffic graph. Moreover, we present a novel eigenvalue algorithm to compute the spectrum efficiently. We provide theoretical guarantees for the running time complexity of our eigenvalue algorithm and show that it is faster than previous methods by 2 times. We evaluate the classification accuracy of our approach on traffic videos and autonomous driving datasets corresponding to urban traffic. In practice, GraphRQI achieves an accuracy improvement of up to 25% over prior driver behavior classification algorithms. We also use our classification algorithm to predict the future trajectories of road-agents.
