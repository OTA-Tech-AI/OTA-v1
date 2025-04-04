<!-- markdownlint-disable first-line-h1 -->
<!-- markdownlint-disable html -->
<!-- markdownlint-disable no-duplicate-header -->

<div align="center">
  <img src="https://github.com/OTA-Tech-AI/OTA-v1/blob/main/figures/OTA-Beholder.png?raw=true" width="20%" alt="OTA-v1" style="border-radius: 10px;" />
</div>
<div align="center" style="line-height: 1;">
  <a href="https://www.otatech.ai/ota-agent"><img alt="Homepage"
    src="https://img.shields.io/badge/Home-Page-blue"/></a>
  <a href="https://huggingface.co/OTA-AI/OTA-v1"><img alt="Hugging Face"
    src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-OTA%20AI-ffc107?color=ffc107&logoColor=white"/></a>
</div>

# OTA-v1: Observe, Think, Act

**OTA-v1** is a lightweight agent model designed to support browser automation frameworks by understanding browser context, making decisions, and generating action commands. We define OTA-v1 as a **Browser Agent Model (BAM)** — a specialized model trained to perceive the state of a web page and act intelligently within it.

Built for seamless integration with browser agent systems, OTA-v1 functions as the core reasoning component. It interprets the browser state (e.g., DOM, UI elements), determines appropriate actions, and outputs structured commands.

Optimized for **local deployment**, OTA-v1 enables fast, efficient inference directly on personal machines and GPUs without the need for cloud infrastructure.

## Key Features

- 🧠 **Browser-Aware Reasoning**: Understands web interfaces and user intent through DOM and action analysis.
- ⚡ **Lightweight & Local**: Deployable on individual machines for low-latency, offline use.
- 🎯 **Action-Driven Output**: Produces clear, structured actions for browser interaction.


## Roadmap

### BAM

- [ ] Extend OTA-v1 to handle more complex tasks
- [ ] Improve action accuracy through better context understanding

### Serving

- [ ] Deploy lightweight serving clusters for fast local and remote inference
- [ ] Provide simple APIs for easy model integration

### Datasets

- [ ] Collect real human browser interaction data for training
- [ ] Build tools to annotate and structure action datasets

### Agent Framework

- [ ] Design an optimized agent framework centered around our BAMs
- [ ] Support modular extensions and task-specific plugins