## Hi, I'm Antoine 👋

I build computer-use agents at [H Company](https://hcompany.ai) in Paris. I wrote the harness the Holo models are evaluated and trained with, and the API and apps built on top.

<p>
  <a href="https://hcompany.ai/newsroom/holo4"><img src="figs/holo4.jpg" width="32%" alt="Holo4"></a>
  <a href="https://build.hcompany.ai"><img src="figs/build.jpg" width="32%" alt="Build with the H Agents API"></a>
  <a href="https://trajectories.hcompany.ai"><img src="figs/trajectories.jpg" width="32%" alt="Holo4 trajectories"></a>
</p>

### Harness engineering with agents

For [Holo4](https://hcompany.ai/newsroom/holo4), agents read our failed OSWorld 2.0 runs, worked out why each task failed and proposed harness fixes. I reviewed and shipped them. In one month, with no finetuning, our score went from 6.1% (Qwen3.6 27B) to 59.8%. On the same Qwen3.8 27B weights: 24.8% → 45.9% → 51.1% → 57.6% → 59.8%, beating the 48.0% Alibaba reports for this model. Two changes mattered most: memory that holds up over hundreds of steps, and a shell on the desktop machine itself.

<a href="https://hcompany.ai/newsroom/holo4"><img src="figs/harness-loop.png" alt="OSWorld 2.0 score across harness iterations"></a>

Holo4 27B (left) and its base model Qwen3.8 27B (right) build the Eiffel Tower in FreeCAD, with the same prompt and harness.

<img src="figs/holo4-vs-qwen.gif" alt="Holo4 27B vs Qwen3.8 27B in FreeCAD">

### Things I built

- [Holo3](https://hcompany.ai/newsroom/holo3) and [Holo3.1](https://hcompany.ai/newsroom/holo3.1) ran on my harness for data collection. I put them in HoloTab and the Agents API, and wrote the Holo3.1 launch post.
- [Agents API](https://hub.hcompany.ai/agents-api/introduction): H's public computer-use API, with SDKs, a CLI and an MCP server. I was lead engineer.
- [HoloBricks](https://bricks.hcompany.ai) and [HoloBlocks](https://blocks.hcompany.ai): describe a model and an agent builds it in LEGO or Minecraft, checking its renders as it goes. Try them.
- [HoloTab](https://hcompany.ai/newsroom/meet-holotab): a browser agent in Chrome.
- [HoloDesktop CLI](https://hcompany.ai/newsroom/holodesktop-cli): a desktop agent in your terminal.
- [Surfer 2](https://arxiv.org/abs/2510.19949): state of the art on OSWorld, WebVoyager, WebArena and AndroidWorld in 2025.

### Open source

| Repo | What |
|---|---|
| [hcompai/hai-agents-python](https://github.com/hcompai/hai-agents-python) | Python SDK and agent harness for Holo models |
| [hcompai/hai-agents-ts](https://github.com/hcompai/hai-agents-ts) | TypeScript SDK for the Agents API |
| [hcompai/holo-desktop-cli](https://github.com/hcompai/holo-desktop-cli) | Desktop agent in your terminal |
| [hcompai/holobricks](https://github.com/hcompai/holobricks) | LEGO builder agent |
| [epfLLM/meditron](https://github.com/epfLLM/meditron) | Open medical LLMs, 2.2k stars |

### Activity

Most of my code lives in private H repos, under my work account [@abonneth](https://github.com/abonneth): 10.9k contributions in the past year.

<a href="https://github.com/abonneth"><img src="https://ghchart.rshah.org/6e40c9/abonneth" alt="@abonneth contribution graph" width="100%"></a>

### Before H

- Meta GenAI, research intern: hierarchical multi-agent systems, and fine-tuning Llama 3.1 70B on its own successful runs.
- [Meditron](https://arxiv.org/abs/2311.16079), data lead at EPFL: open medical LLMs built on Llama 2, plus the [Clinical Guidelines](https://huggingface.co/datasets/epfl-llm/guidelines) dataset. Featured on the [Meta AI blog](https://ai.meta.com/blog/llama-2-3-meditron-yale-medicine-epfl-open-source-llm/).
- [MOOVE](https://jointhemoove.org): a platform where clinicians rate medical LLM answers.

MSc in Computer Science, EPFL. BSc in Math and Computer Science, McGill.

[Google Scholar](https://scholar.google.com/citations?user=Xt__74QAAAAJ) · [LinkedIn](https://www.linkedin.com/in/antoine-bonnet04) · [Resume](CV.pdf)
