# EcoCooler

PROBLEM STATEMENT: Minimizing Costs in Energy Consumption of a Data Center
In this case study, the primary objective is to minimize energy consumption costs in the cooling and heating systems of a data center. Data centers, known for their high energy demands, rely heavily on cooling systems to maintain optimal operating temperatures for servers and equipment. Inspired by DeepMind's achievement in reducing Google's data center cooling costs by 40% using a Deep Q-Learning (DQN) AI model in 2016, this case study aims to replicate a similar approach.

•	Capstone project for the course CS 541: Artificial Intelligence under Prof. Jie Shen.

•	Developed a reinforcement learning business solution that minimizes cooling energy costs in server environments. Engineered an environment simulating atmospheric conditions and user demands, generating realistic scenario simulations. 

•	Implemented Deep Q-Learning (DQN) with 30-70 exploration-exploitation strategy; identified relevant states (like temperature, server load) as well as actions (like changing fan speed) to be optimized. Integrated Experience Replay through a memory system that stores and recalls past transitions.

•	Conducted simulations for 1000 epochs (with early stopping) in training mode and for 12 months in inference mode, achieving up to 87% energy savings compared to traditional methods.

