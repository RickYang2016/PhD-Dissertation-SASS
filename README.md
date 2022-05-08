# Self-Adaptive Swarm Systems (SASS) -- Abstract
<!-- Qin Yang  -->

Multi-agent systems (MAS) could play a pivotal role in realizing future intel- ligent workspaces, especially in building so-called artificial social systems, such as self-driving cars and multi-robot systems (MRS). For example, MAS/MRS cooperates to increase mission performance in many applications, including exploration, surveillance, defense, humanitarian, and emergency missions like urban search and rescue. In such missions, complex environments such as hazardous, dynamic changing, and adversarial surroundings create a significant challenge to the agents in realizing their full potential. Therefore, this thesis addresses some pressing gaps in the literature in realizing an adaptive MAS by proposing a principled MAS cooperation framework, termed the Self-Adaptive Swarm System (SASS), which bridges communication, planning, decision-making and learning in the distributed MAS.

<div align = center>
<img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass.png" height="245" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass.gif" height="250" alt="Hopper-V2 3SABC Video"/>
</div>

<div align = center>
<img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/sass-framework.png" height="245" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/Qin-Yang-PhD-Dissertation-SASS/blob/main/figures/gut.gif" height="250" alt="Hopper-V2 3SABC Video"/>
</div>

## Contributions

The core scientific contributions of this thesis are as follows: 
* 1) We define a novel human-inspired agent (robot) needs hierarchy model to con- sider an agent’s motivation and requirements based on the current status and assigned tasks; 
* 2) We present a priority-based distributed negotiation-agreement algorithm for realizing multi-agent tasks assignment problems, effectively avoiding plan conflicts – Here, we decompose the tasks into atomic operations and achieve MAS cooperation through a series of simple sub-tasks; 
* 3) We introduce a new needs-based agent trust and cooperation mechanism to create needs-driven relationships among multiple agents in challenging environments; 
* 4) We build a new hierarchical utility network --game-theoretic utility tree (GUT) -- to realize game-theoretic solutions for the cooperating MAS in the presence of adversarial opponent agents; 
* 5) We propose a novel Bayesian strategy networks (BSN) applied to deep reinforcement learning by decomposing tasks into multiple sub-level actions and obtaining the optimal agent policies in unknown and challenging environments.

![image](https://github.com/RickYang2016/Bayesian-Soft-Actor-Critic/blob/main/figures/policy_network.png)

<div align = center>
<img src="https://github.com/RickYang2016/Bayesian-Soft-Actor-Critic/blob/main/figures/walker2d.png" height="250" alt="Hopper-V2 3SABC"><img src="https://github.com/RickYang2016/Bayesian-Soft-Actor-Critic/blob/main/figures/biped_robot.gif" height="250" alt="Hopper-V2 3SABC Video"/>
</div>
