# 🎬 Talk2Traffic

**Talk2Traffic** is a **multimodal large language model (MLLM)-powered framework** for **interactive and editable traffic scenario generation**. It enables users to create simulation-ready traffic scenes through **text**, **speech**, and **sketches**, lowering the barrier to designing diverse and safety-critical scenarios for autonomous driving.

![Talk2Traffic Overview](https://zihaosheng.github.io/Talk2Traffic/static/images/fig1.svg)

## 🧠 What is Talk2Traffic?

Autonomous vehicles need to be tested in diverse, often rare, traffic scenarios—but collecting real-world data is expensive and time-consuming. **Talk2Traffic bridges this gap** by using **multimodal input and human-in-the-loop feedback** to generate **executable traffic scenarios** for simulators like **CARLA**.

### 🔧 Key Features

* **Multimodal input support**: Users can describe scenes using natural language, voice commands, and sketches.
* **Interactive editing**: Iteratively refine scenarios with human feedback—no coding required.
* **RAG-powered code generation**: Uses retrieval-augmented generation to produce valid Scenic code.
* **Simulator ready**: Outputs are directly compatible with CARLA simulator.

![Editing Workflow](https://zihaosheng.github.io/Talk2Traffic/static/images/fig2.svg)

## 📢 Code Release

We are actively cleaning up and organizing the code for public release.
**Stay tuned!** 🔧✨

## 📄 Citation

```bibtex
@inproceedings{sheng2025talk2traffic,
  title={Talk2Traffic: Interactive and Editable Traffic Scenario Generation for Autonomous Driving with Multimodal Large Language Model},
  author={Sheng, Zihao and Huang, Zilin and Qu, Yansong and Leng, Yue and Chen, Sikai},
  booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) Workshops},
  year={2025}
}
```
