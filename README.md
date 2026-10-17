## Hi, I'm Antoine 👋

Member of Technical Staff, Agents at [H Company](https://hcompany.ai) in Paris. I build computer-use agents end to end: the harness, evals and environments behind the Holo models, and the API and products that ship them.

<p>
  <a href="https://hcompany.ai/newsroom/holo4"><img src="figs/holo4.jpg" width="32%" alt="Holo4"></a>
  <a href="https://build.hcompany.ai"><img src="figs/build.jpg" width="32%" alt="Build with the H Agents API"></a>
  <a href="https://trajectories.hcompany.ai"><img src="figs/trajectories.jpg" width="32%" alt="Holo4 trajectories"></a>
</p>

### Agent-driven harness engineering

For [Holo4](https://hcompany.ai/newsroom/holo4), agents read failed OSWorld 2.0 runs, tagged why each task failed and proposed harness fixes; I reviewed and shipped them. In one month, with no finetuning, our score went from 6.1% (Qwen3.6 27B) to 59.8%. On the same Qwen3.8 27B weights: 24.8% → 45.9% → 51.1% → 57.6% → 59.8%, beating the 48.0% Alibaba reports for this model by 11.8 points. The two biggest levers: memory that holds up over hundreds of steps, and a shell on the desktop machine itself.

<a href="https://hcompany.ai/newsroom/holo4"><img src="figs/harness-loop.png" alt="OSWorld 2.0 score across harness iterations"></a>

Same prompt, same harness: Holo4 27B (left) vs its base model Qwen3.8 27B (right), building the Eiffel Tower in FreeCAD.

<img src="figs/holo4-vs-qwen.gif" alt="Holo4 27B vs Qwen3.8 27B in FreeCAD">

### Things I built

- 🤖 **[Holo3](https://hcompany.ai/newsroom/holo3) and [Holo3.1](https://hcompany.ai/newsroom/holo3.1)**: harness, trace collection and product integration (HoloTab, Agents API); wrote the Holo3.1 launch post. Holo3: 78.9% on OSWorld-Verified.
- 🔌 **[Agents API](https://hub.hcompany.ai/agents-api/introduction)** (lead engineer): H's public computer-use API, with SDKs, CLI and MCP server.
- 🧱 **[HoloBricks](https://bricks.hcompany.ai) and [HoloBlocks](https://blocks.hcompany.ai)**: describe a model, an agent builds it brick by brick (or block by block) and fixes it from renders. Try them.
- 🌐 **[HoloTab](https://hcompany.ai/newsroom/meet-holotab)**: a browser agent in Chrome.
- 💻 **[HoloDesktop CLI](https://hcompany.ai/newsroom/holodesktop-cli)**: a desktop agent in your terminal.
- 🏄 **[Surfer 2](https://arxiv.org/abs/2510.19949)**: state of the art on OSWorld, WebVoyager, WebArena and AndroidWorld (2025).

### Open source

| Repo | What |
|---|---|
| [hcompai/hai-agents-python](https://github.com/hcompai/hai-agents-python) | Python SDK and agent harness for Holo models |
| [hcompai/hai-agents-ts](https://github.com/hcompai/hai-agents-ts) | TypeScript SDK for the Agents API |
| [hcompai/holo-desktop-cli](https://github.com/hcompai/holo-desktop-cli) | Desktop agent in your terminal |
| [hcompai/holobricks](https://github.com/hcompai/holobricks) | LEGO builder agent |
| [epfLLM/meditron](https://github.com/epfLLM/meditron) | Open medical LLMs (2.2k ⭐) |

### Activity

Most of my work lives in private H repos, on my work account [@abonneth](https://github.com/abonneth): 10.9k contributions in the past year.

<a href="https://github.com/abonneth"><img src="https://ghchart.rshah.org/6e40c9/abonneth" alt="@abonneth contribution graph" width="100%"></a>

### Before

- 🧠 **Meta GenAI** (research intern): hierarchical multi-agent orchestration, rejection-sampling fine-tuning of Llama 3.1 70B.
- 🧬 **[Meditron](https://arxiv.org/abs/2311.16079)** (data lead, EPFL): open medical LLMs on Llama 2, [Clinical Guidelines](https://huggingface.co/datasets/epfl-llm/guidelines) dataset, featured on the [Meta AI blog](https://ai.meta.com/blog/llama-2-3-meditron-yale-medicine-epfl-open-source-llm/).
- 🩺 **[MOOVE](https://jointhemoove.org)**: clinician feedback platform for evaluating medical LLMs.

🎓 MSc CS, EPFL · BSc Math and CS, McGill

[Google Scholar](https://scholar.google.com/citations?user=Xt__74QAAAAJ) · [LinkedIn](https://www.linkedin.com/in/antoine-bonnet04) · [Resume](CV.pdf)
