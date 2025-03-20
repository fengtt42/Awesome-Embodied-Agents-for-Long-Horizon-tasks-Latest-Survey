# Awesome-Autonomous-Embodied-AI-from-Scratch


Start your journey in Autonomous Embodied AI with a curated roadmap of foundational papers. Updated regularly.

---
This repository provides a structured learning path for <font color=yellow>beginners</font> in Autonomous Embodied AI, offering a <font color=yellow>handpicked list of classic papers</font> and a <font color=yellow>recommended study order</font>. Thank you for forking and giving a ⭐.


##  📚 Embodied AI Paper Lists

The list is designed to help you build a solid worldview of the field, guiding you from foundational concepts to advanced topics, and from broad perspectives to specific technical challenges. <font color=yellow>Please read in order.</font>


__`[1] Survey`__

- Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI __`Arxiv 2024`__; [Paper](https://arxiv.org/abs/2407.06886), [Paper List](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List), __`✨ 1.3K`__

- A Survey on Vision-Language-Action Models for Embodied AI __`Arxiv 2025`__; [Paper](https://arxiv.org/pdf/2405.14093), [Paper List](https://github.com/yueen-ma/Awesome-VLA), __`✨ 22`__

__`[2] Indoor Robotics`__
- Semantic Mapping in Indoor Embodied AI – A Comprehensive Survey and Future Directions __`TMLR 2025 Reviewing`__; [Paper](https://arxiv.org/abs/2501.05750), [Paper List to be release]()

__`[3] Autonomous Driving`__

- End-to-End Autonomous Driving: Challenges and Frontiers __`TPAMI 2024`__; [Paper](https://ieeexplore.ieee.org/abstract/document/10614862), [Paper List to be release](https://github.com/OpenDriveLab/End-to-end-Autonomous-Driving), __`✨ 2.9K`__

__`[4] Cross Domain`__
- A Comprehensive Survey of Cross-Domain Policy Transfer for Embodied Agents __`IJCAI 2024`__; [Paper](https://arxiv.org/pdf/2402.04580), [Paper List](https://github.com/t6-thu/awesome-cross-domain-policy-transfer-for-embodied-agents), __`✨ 45`__


##  🗺️ World Model Paper Lists

The world model architectures of autonomous embodied agents include RSSM, JEPA, Transformer, Diffusion, and Hierarchical.

__`[1] Survey`__
- Is Sora a World Simulator? A Comprehensive Survey on General World Models and Beyond __`Arxiv 2024`__; [paper](https://arxiv.org/abs/2405.03520), [Paper Lists](https://github.com/GigaAI-research/General-World-Models-Survey), __`✨ 370`__
- World Models for Autonomous Driving:An Initial Survey __`TIV 2024`__; [Paper](https://arxiv.org/abs/2403.02622), [Paper Lists](https://github.com/HaoranZhuExplorer/World-Models-Autonomous-Driving-Latest-Survey), __`✨ 273`__

__`[2] RSSM Structure`__
- Mastering Diverse Domains through World Models __`Arxiv 2023`__; [Paper](https://arxiv.org/pdf/2301.04104), [Paper Code](https://github.com/danijar/dreamerv3), __`✨ 1.6K`__

__`[3] JEPA Structure`__
- A Path Towards Autonomous AI __`Open Review 2022`__;[Video](https://www.youtube.com/watch?v=DokLw1tILlw), [Paper](https://openreview.net/pdf?id=BZ5a1r-kVsf), __`✨ 687`__

__`[4] Transformer Structure`__
- Transformers are Sample Efficient World Models __`ICLR 2023`__; [Paper](https://arxiv.org/pdf/2209.00588), [Paper Code](https://github.com/eloialonso/iris), __`✨ 832`__

__`[5] Diffusion Structure`__
- Diffusion for World Modeling: Visual Details Matter in Atari __`NeurIPS 2024 Spotlight`__; [Paper](https://arxiv.org/pdf/2405.12399), [Paper Code](https://github.com/eloialonso/diamond) , __`✨ 1.8K`__

__`[6] Hierarchical Structure`__
- Hierarchical World Models as Visual Whole-Body Humanoid Controllers __`ICLR 2025`__; [Paper](https://arxiv.org/abs/2405.18418), [Paper Code](https://github.com/nicklashansen/puppeteer) , __`✨ 169`__

| Structure  | Key Ideal | Strengths | Pioneering Work |
|------------|-----------|-----------|--|
|**RSSM (Recurrent State Space Model)**|Combines deterministic RNNs with stochastic latent variables for long-horizon prediction|Handles partial observability, balances memory and uncertainty.|Model-based reinforcement learning (e.g., Dreamer series)|
|**JEPA (Joint Embedding Predictive Architecture)**|Predicts latent representations of future states rather than pixels/raw observations|Sample-efficient, enables abstract reasoning|Introduced in Yann LeCun's self-supervised learning frameworks|
|**Transformer-based Models**|Leverages attention mechanisms for global context modeling|Parallelizable, excels at long-range dependencies|Decision Transformers, State Sequence Prediction|
| **Diffusion Models**|Iteratively denoises latent states to model complex distributions|High-fidelity generation, handles multimodal predictions|Planning in continuous action spaces|
|**Hierarchical Architectures** |Decomposes tasks into temporal/abstract hierarchies|Scalability, enables subgoal-based planning|Temporal Abstraction (HiP), Manager-Worker frameworks|


##  🚀 Long-Horizon Task Paper Lists

__`[1] MLLM-based`__
- Optimus-2: Multimodal Minecraft Agent with Goal-Observation-Action Conditioned Policy __`CVPR 2025`__; [Paper](), [Paper Code](https://github.com/dawn0815/Optimus-2) , __`✨ 8`__
- Describe, Explain, Plan and Select: Interactive Planning with Large Language Models Enables Open-World Multi-Task Agents __`NeurIPS 2024`__; [Paper](https://arxiv.org/pdf/2302.01560), [Paper Code](https://github.com/CraftJarvis/MC-Planner) , __`✨ 270`__
- Steve-Eye: Equipping LLM-based Embodied Agents with Visual Perception in Open Worlds __`ICLR 2024`__; [Paper](https://arxiv.org/pdf/2310.13255), [Paper Code](https://github.com/BAAI-Agents/Steve-Eye) , __`✨ 7`__
- 
__`[2] Knowledge-Graph-based`__
- Optimus-1: Hybrid Multimodal Memory Empowered Agents Excel in Long-Horizon Tasks __`NeurIPS 2024`__; [Paper](https://openreview.net/pdf?id=XXOMCwZ6by), [Paper Code](https://github.com/JiuTian-VL/Optimus-1) , __`✨ 70`__
- Active Reasoning in an Open-World Environment __`NeurIPS 2023`__; [Paper](https://arxiv.org/abs/2311.02018), [Paper Code](https://github.com/ariesssxu/Conan-Active-Reasoning) , __`✨ `__


##  🎯 Announcement

Besides the wonderful papers we list above, we are very happy to announce that our group, THU-Swarm Laboratory, recently released a preprint titled: [EvoAgent: Agent Autonomous Evolution with Continual World Model for Long-Horizon Tasks](https://arxiv.org/pdf/2502.05907), the first autonomous-evolution agent with a continual World Model, which can autonomously complete various long-horizon tasks across environments through self-planning, self-control, and self-reflection, without human intervention. If this paper inspires you, you may consider cite it via:
```bibtex
@article{feng2025evoagent,
  title={EvoAgent: Agent Autonomous Evolution with Continual World Model for Long-Horizon Tasks},
  author={Tongtong Feng and Xin Wang and Zekai Zhou and Ren Wang and Yuwei Zhan and Guangyao Li and Qing Li and Wenwu Zhu},
  journal={arXiv preprint arXiv:2502.05907},
  year={2025}
}
```


## Other Related Repos
[Awesome-World-Model](https://github.com/LMD0311/Awesome-World-Model),
[Awesome-World-Models-for-AD ](https://github.com/zhanghm1995/awesome-world-models-for-AD?tab=readme-ov-file#Table-of-Content),
[World models paper list from Shanghai AI lab](https://github.com/OpenDriveLab/End-to-end-Autonomous-Driving/blob/main/papers.md#world-model--model-based-rl),
[Awesome-Papers-World-Models-Autonomous-Driving](https://github.com/chaytonmin/Awesome-Papers-World-Models-Autonomous-Driving).
    
