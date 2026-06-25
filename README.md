# SILAS_2025-2026
Repository containing the final presentation for the courses of Learning for Autonomous Systems and Simulation Intelligence at UniTs 2025/2026.

---

## Paper A — UAV Trajectory Planning with DDQN

This paper addresses the problem of 3D trajectory planning for an unmanned aerial vehicle (UAV) tasked with collecting data from ground-based IoT devices in an urban environment with static obstacles and wireless jammers. The problem is formulated as a Markov Decision Process (MDP) and solved using a Double Deep Q-Network (DDQN) agent, which learns an autonomous, energy-efficient flight strategy without prior knowledge of channel conditions or device locations. The approach is evaluated across three scenario configurations and compared against Q-learning, PPO, DQN, and Dueling DQN baselines.

**Reference:**
Wang, S., Qi, N., Jiang, H., Xiao, M., Liu, H., Jia, L., & Zhao, D. (2024).
*Trajectory Planning for UAV-Assisted Data Collection in IoT Network: A Double Deep Q Network Approach.*
Electronics, 13(8), 1592.
https://doi.org/10.3390/electronics13081592

---

## Paper B — Physics-Informed Neural Networks for Lithium-Ion Battery Degradation

This paper proposes a Physics-Informed Neural Network (PINN) for stable modeling and prognosis of lithium-ion battery State of Health (SOH). The architecture consists of two coupled networks: a solution network F(·) that maps input features to SOH estimates, and a dynamics network G(·) that encodes the underlying degradation PDE. The model is trained on large multi-chemistry source datasets and fine-tuned on small target samples, enabling cross-scenario transfer learning with significantly reduced data requirements compared to purely data-driven baselines.

**Reference:**
Wang, J., et al. (2024).
*Physics-informed neural network for lithium-ion battery degradation stable modeling and prognosis.*
Nature Communications, 15, 4332.
https://doi.org/10.1038/s41467-024-48779-z

