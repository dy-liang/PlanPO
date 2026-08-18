<h3 align="center">
<b>PlanPO: PlanPO: Group Planning-Aware Policy Optimization for Multi-Turn Agentic LLMs.</b>
<br>
<b>arXiv Preprint</b>
</h3>


<p align="center">
  <a href="https://arxiv.org/abs/2505.10978">
    <img src="https://img.shields.io/badge/arXiv-Paper-red?style=flat-square&logo=arxiv" alt="arXiv Paper"></a>
  &nbsp;
  <a href="https://github.com/langfengQ/verl-agent">
    <img src="https://img.shields.io/badge/GitHub-Project-181717?style=flat-square&logo=github" alt="GitHub Project"></a>
  &nbsp;
  <a href="https://huggingface.co/collections/langfeng01/verl-agent-684970e8f51babe2a6d98554">
    <img src="https://img.shields.io/badge/HuggingFace-Models-yellow?style=flat-square&logo=huggingface" alt="HuggingFace Models"></a>
  &nbsp;
</p>

`verl-agent` is an extension of [veRL](https://github.com/volcengine/verl), specifically designed for training **large language model (LLM) agents via reinforcement learning (RL)**. 

Unlike prior approaches that simply concatenate full interaction histories, `verl-agent` proposes **step-independent multi-turn rollout mechanism**, which allows for **fully customizable** per-step input structures, history management, and memory modules. This design makes `verl-agent` **highly scalable for very long-horizon, multi-turn RL training** (e.g., tasks in ALFWorld can require up to 50 steps to complete).

`verl-agent` provides a **diverse set of RL algorithms** (including our new algorithm GiGPO) and a **rich suite of agent environments**, enabling the development of reasoning agents in both visual and text-based tasks.
# PlanPO: PlanPO: Group Planning-Aware Policy Optimization for Multi-Turn Agentic LLMs.
