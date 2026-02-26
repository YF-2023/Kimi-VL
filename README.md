<div align="center">
  <a href="Kimi-VL.pdf">KIMI-VL TECHNICAL REPORT</a>
</div>

<div align="center">
  <a href="https://arxiv.org/abs/2504.07491"><img src="figures/logo.png" height="16" width="16" style="vertical-align:middle"><b> Tech Report</b></a>  |  
  <a href="https://huggingface.co/collections/moonshotai/kimi-vl-a3b-67f67b6ac91d3b03d382dd85"><img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" height="16" width="16" style="vertical-align:middle"><b> HuggingFace</b>
  </a> |
  <a href="https://huggingface.co/spaces/moonshotai/Kimi-VL-A3B-Thinking/">4ac<b>Chat with Latest Kimi-VL (2506)</b></a>
</div>


## 1. Introduction

We present **Kimi-VL**, an efficient open-source Mixture-of-Experts (MoE) vision-language model (VLM) that offers **advanced multimodal reasoning, long-context understanding, and strong agent capabilities**all while activating only **2.8B** parameters in its language decoder (Kimi-VL-A3B).

Kimi-VL demonstrates strong performance across challenging domains:
as a general-purpose VLM, Kimi-VL excels in multi-turn agent interaction tasks (e.g.,OSWorld), achieving state-of-the-art results comparable to flagship models.
Furthermore, it exhibits remarkable capabilities across diverse challenging vision language tasks, including college-level image and video comprehension, optical character recognition (OCR), mathematical reasoning, multi-image understanding, and etc.

In comparative evaluations, it effectively competes with cutting-edge efficient VLMs such as GPT-4o-mini, Qwen2.5-VL-7B, and Gemma-3-12B-IT, while surpassing GPT-4o in several specialized domains.

Kimi-VL also advances the pareto frontiers of multimodal models in processing long contexts and perceiving clearly: Equipped with a 128K extended context window, Kimi-VL can processes long and diverse inputs, achieving impressive scores of 64.5 on LongVideoBench, and 35.1 on MMLongBench-Doc; Its native-resolution vision encoder, MoonViT, further allows it to see and understand ultra-high-resolution visual inputs, achieving 83.2 on InfoVQA and 34.5 on ScreenSpot-Pro, while maintaining lower computational cost with common visual inputs and general tasks.

Building on this foundation, we introduce an advanced long-thinking variant: **Kimi-VL-Thinking**. Developed through long chain-of-thought (CoT) supervised fine-tuning (SFT) and reinforcement learning (RL), this model exhibits strong l



---



## References

1. related project [Qwen2.5-VL](https://github.com/phildougherty/qwen2.5-VL-inference-openai)
2. related project [DeepSeek-VL2](https://github.com/deepseek-ai/DeepSeek-VL2)
3. related project [Aria](https://github.com/tomkat-cr/vitexbrain)
