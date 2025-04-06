<!-- markdownlint-disable first-line-h1 -->
<!-- markdownlint-disable html -->
<!-- markdownlint-disable no-duplicate-header -->

<div align="center">
  <img src="https://github.com/user-attachments/assets/bae2201a-dfff-4581-8f2e-b949616ff7cd" width="100%" alt="OTA-v1" style="border-radius: 10px;" />
</div>
<br>
<div align="center" style="line-height: 1;">
  <a href="https://www.otatech.ai/ota-agent"><img alt="Homepage"
    src="https://img.shields.io/badge/Home-Page-blue"/></a>
  <a href="https://huggingface.co/OTA-AI/OTA-v1"><img alt="Hugging Face"
    src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-OTA%20AI-ffc107?color=ffc107&logoColor=white"/></a>
  <a href="https://github.com/OTA-Tech-AI/OTA-v1/blob/main/LICENSE"><img alt="Code License"
    src="https://img.shields.io/badge/Code_License-MIT-f5de53?&color=f5deff"/></a>
  <a href="https://github.com/OTA-Tech-AI/OTA-v1/blob/main/LICENSE-MODEL"><img alt="Model License"
    src="https://img.shields.io/badge/Model_License-Model_Agreement-f5de53?&color=945283"/></a>
  <br><br><br>
</div>

# OTA-v1: Observe, Think, Act

**OTA-v1** is a lightweight agent model designed to support browser automation frameworks by understanding browser context, making decisions, and generating action commands. We define OTA-v1 as a **Browser Agent Model (BAM)** — a specialized model trained to perceive the state of a web page and act intelligently within it.
![ota-v1@2x](https://github.com/user-attachments/assets/79c0f18b-3974-4fe3-9cb5-09d0ca1d0e2c)

Built for seamless integration with browser agent systems, OTA-v1 functions as the core reasoning component. It interprets the browser state (e.g., DOM, UI elements), determines appropriate actions, and outputs structured commands.

Optimized for **local deployment**, OTA-v1 enables fast, efficient inference directly on personal machines and GPUs without the need for cloud infrastructure.

## Key Features

- 🧠 **Browser-Aware Reasoning**: Understands web interfaces and user intent through DOM and action analysis.
- ⚡ **Lightweight & Local**: Deployable on individual machines for low-latency, offline use.
- 🎯 **Action-Driven Output**: Produces clear, structured actions for browser interaction.

## Quick Start Using Ollama

``` cli
ollama run hf.co/OTA-AI/OTA-v1
```

## BAM Client: Use OTA-v1 with Browser-Use

(https://github.com/OTA-Tech-AI/BAM-Client/)

## Roadmap

### BAM

- [ ] Support Multi-Modality for visual understanding
- [ ] Extend OTA-v1 to handle more complex tasks with long memory
- [ ] Improve action accuracy through context awareness and inter-element attention 

### Serving

- [ ] Deploy lightweight serving clusters for fast local and remote inference
- [ ] Provide simple APIs for easy model integration

### Datasets

- [ ] Collect browser interactions usage data from human users
- [ ] Build tools to annotate and structure action datasets

### Agent Framework

- [ ] Design an optimized browser agent framework centered around our BAMs
- [ ] Support modular extensions and task-specific plugins
