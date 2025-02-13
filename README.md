# Deep Multi-Agent Reinforcement Learning
## Abstract
With the rapid advancement of communication technology and the exponential growth of mobile users, improving network coverage quality and throughput has become increasingly important. In particular, large-scale base station (BS) cooperative optimization has become a highly significant topic. BSs can adjust various parameters for high-quality communication, but automating this optimization remains challenging due to environmental sensitivity and interdependencies. Traditional methods for network optimization are constrained by the intricate nature of real-world environments. Further, reinforcement learning (RL) techniques, which are effective for configuration policies, encounter difficulties in intricate, high-dimensional wireless communication networks, especially in multi-agent cooperative optimization.
To overcome these challenges, this paper proposes the Enhanced Multi-Agent Proximal Policy Optimization (EMAPPO), which utilizes the capabilities of the UNet network to extract multi-spatial relationships among a massive number of network elements and employs the DiffPool network to efficiently depict the impact of large-scale action coordination among massive agents on coverage performance. To facilitate evaluation in communication optimization, we further introduce a high-fidelity digital twin-driven mobile network. Extensive experiments validate the effectiveness and superior performance of EMAPPO by utilizing the network digital twin. The results demonstrate significant improvements in signal coverage rate and network throughput compared to the competing methods.
## Instructions
### algorithms
Implentment of our algorithm EMAPPO
### envs
RL environment of our algorithm
### train
Execute the train.py file to start the algorithm training process
