# Awesome Uncensored AI Models

> A source-tracked guide to low-filter, abliterated, and community-reported AI models across language, image, and video generation.

“Uncensored” is not a standardized technical guarantee. Behavior depends on the exact weights, fine-tune or adapter, inference pipeline, interface, hosted provider, and version. The companion catalogs record evidence and distinguish local weights from hosted access.

**README reviewed:** 2026-10-06. Candidate lists and availability change; verify the detailed catalog and source for each entry.

## Related Projects

- [awesome-uncensored-llms](https://github.com/Anil-matcha/awesome-uncensored-llms) — Detailed language-model catalog, with open-weight and hosted entries separated.
- [Awesome Uncensored Coding Models](https://github.com/Anil-matcha/awesome-uncensored-coding-models) — coding-model candidates, use cases, benchmark runner, and agent setup.
- [awesome-uncensored-ai-agents](https://github.com/Anil-matcha/awesome-uncensored-ai-agents) — setup and safety guidance for using tool-capable models in general-purpose agents.
- [awesome-uncensored-ai-image-models](https://github.com/Anil-matcha/awesome-uncensored-ai-image-models) — Detailed image-generation and image-editing catalog.
- [awesome-uncensored-ai-video-models](https://github.com/Anil-matcha/awesome-uncensored-ai-video-models) — Detailed video-generation and video-editing catalog.

## Contents

- [Language models](#language-models)
- [Image models](#image-models)
- [Video models](#video-models)
- [Use cases and finding a model](#use-cases-and-finding-a-model)
- [Inclusion principles](#inclusion-principles)
- [Contributing](#contributing)
- [Responsible use](#responsible-use)

## Language models

These 20 candidates are a shortlist for evaluation, not a benchmark ranking. Hosted model names may refer to a particular fine-tune or route; they do not prove public weights or common behavior across services. The [LLM catalog](https://github.com/Anil-matcha/awesome-uncensored-llms) tracks provenance, exact sources, access, and caveats. Use the modality catalog before choosing or downloading an entry.

| Candidate | Family / focus |
| --- | --- |
| Abliterated Model Large V2 | GLM-derived large reasoning |
| GLM 5.3 Flash Uncensored | GLM Flash reasoning, coding, tools |
| Qwen 3.8 27B Uncensored | Qwen multimodal general model |
| GLM 5.3 Uncensored | Full-size GLM reasoning |
| Qwen 3.8 27B Obliterated | Qwen refusal-direction ablation variant |
| MiMo V2.6 Flash Uncensored | MiMo fast reasoning and tools |
| MiMo V2.6 Flash Abliterated | MiMo refusal-direction ablation variant |
| Qwen 3.8 27B Uncensored (TEE route) | Alternate hosted route; route properties vary |
| Abliterated Model | GLM-derived multimodal model |
| Abliterated Model Large | Earlier GLM-derived large model |
| Gemma 4 26B A4B Uncensored | Gemma MoE reasoning and multimodal |
| Gemma 4 26B A4B Uncensored (TEE route) | Alternate hosted route; route properties vary |
| Gemma 4 31B Gembrain Uncensored Heretic | Gemma community fine-tune |
| Qwen 3.8 27B Queen | Qwen roleplay fine-tune |
| Qwen 3.8 27B Fable | Qwen storytelling fine-tune |
| Llama 3.3 70B Instruct Abliterated | Llama open-weight checkpoint |
| Qwen2.5 32B Instruct Abliterated | Qwen open-weight checkpoint |
| DeepSeek R1 Distill Llama 70B Abliterated | Reasoning-focused Llama checkpoint |
| DeepSeek R1 Distill Qwen 32B Abliterated | Reasoning-focused Qwen checkpoint |
| NeuralDaredevil 8B Abliterated | Lightweight Llama-family checkpoint |

## Image models

Representative families already documented in the [image catalog](https://github.com/Anil-matcha/awesome-uncensored-ai-image-models). Hosted reports are endpoint-specific; local weights are not automatically low-filter.

| Model / family | Access represented in detailed catalog |
| --- | --- |
| Seedream 2.0 / 3.0 / 4.0 / 4.5 / 5.0 | Hosted endpoint reports |
| Qwen Image 2.0 / 3.0, Edit, Plus, Max, and dated snapshots | Hosted endpoints and local checkpoints |
| Wan 2.1 / 2.2 / 2.5 / 2.6 / 2.7 | Hosted image endpoints and local checkpoints |
| Z-Image, Turbo, Omni-Base, and Edit | Local weights and hosted endpoint reports |
| FLUX.1 [schnell] and [dev] families | Local weights and community variants |
| FLUX.2 [klein] and [dev] families | Local weights, text-encoder adapters, and community variants |
| HiDream-O1-Image | Local weights; filtering status to verify |
| HunyuanImage-3.0 Instruct / Distil | Local weights; filtering status to verify |
| Stable Diffusion XL and Stable Diffusion 1.5 | Established local baselines |
| DreamShaper XL and Animagine XL | Community checkpoints; verify exact version and license |

## Video models

Representative families already documented in the [video catalog](https://github.com/Anil-matcha/awesome-uncensored-ai-video-models). The exact checkpoint, hosted endpoint, and pipeline determine the filtering claim.

| Model / family | Access represented in detailed catalog |
| --- | --- |
| Wan2.1 and Wan2.2 | Local open-weight families |
| Wan 2.5 / 2.6 / 2.7 | Hosted endpoint reports |
| LTX-2 / LTX-2.3 | Local weights; review checkpoint-specific terms |
| HunyuanVideo-1.5 and HunyuanVideo | Local weights; review the custom terms |
| CogVideoX / CogVideoX1.5 | Local weights; checkpoint terms vary |
| Open-Sora and Allegro / Allegro-TI2V | Local research models and pipelines |
| Mochi 1 and AnimateDiff | Local weights, modules, and adapters |
| Stable Video Diffusion and VideoCrafter2 | Local research baselines; verify license and filtering |
| Kling VIDEO 3.0 / 3.0 Omni and 2.6 / O1 | Hosted endpoints; verify exact route |
| Seedance 2.0 / 2.0 Fast | Hosted endpoints; verify exact route |
| Seedance 1.5 Pro and 1.0 Pro / Pro Fast | Hosted endpoints; verify exact route |

## Use cases and finding a model

This repository is an index across model types. Start with the task you want to do, then follow the relevant catalog for exact versions, access, source links, and terms.

| Use case | Start here | What to verify |
|---|---|---|
| **Chat, writing, reasoning, or text generation** | [Awesome Uncensored LLMs](https://github.com/Anil-matcha/awesome-uncensored-llms) | Exact checkpoint or hosted route, prompt format, license or terms, and evidence for behavior claims. |
| **Use a hosted abliterated text API** | [Awesome Abliterated LLMs](https://github.com/Anil-matcha/awesome-abliterated-llms) | Live endpoint ID, request schema, input modalities, capabilities, price, and provider terms. |
| **Coding assistance or repository edits** | [Awesome Uncensored Coding Models](https://github.com/Anil-matcha/awesome-uncensored-coding-models) | Separate code-generation results from coding-agent tool use; test against your own tasks. |
| **Connect a general-purpose agent** | [Awesome Uncensored AI Agents](https://github.com/Anil-matcha/awesome-uncensored-ai-agents) | Agent permissions, supported model protocol, tool-call behavior, workspace isolation, and confirmations. |
| **Generate or edit images** | [Awesome Uncensored AI Image Models](https://github.com/Anil-matcha/awesome-uncensored-ai-image-models) | Exact checkpoint or hosted pipeline, supported edits, model-specific license, and endpoint policy. |
| **Generate or edit video** | [Awesome Uncensored AI Video Models](https://github.com/Anil-matcha/awesome-uncensored-ai-video-models) | Exact model/version, supported video workflow, hosted moderation layer, and model or service terms. |
| **Run models on your own hardware** | The relevant modality catalog’s open-weight entries | Checkpoint files, license, hardware/runtime needs, quantization, and whether the modified weights have their own source. |

### Model, checkpoint, and service are different things

- A **model family** groups related releases; it does not identify the exact weights used by a service.
- A **checkpoint** is a specific set of weights. “Open weight” does not automatically mean unrestricted use or an open-source license.
- A **fine-tune or adapter** changes a base checkpoint and may have distinct provenance, behavior, and terms.
- A **hosted endpoint** is a service route. The route name alone does not prove which checkpoint is served or what moderation layers are applied.
- A **workflow or interface** may add its own prompt, policy, preprocessing, or filtering behavior.

Treat behavior reports as specific to the tested version and setup. Do not transfer a claim about one checkpoint or service to every member of the same model family.

### Before using a model

1. Follow the detailed catalog link and open the primary model card or provider documentation.
2. Confirm that the exact model or route is still available and supports the inputs and outputs you need.
3. Review licenses, service terms, pricing, privacy, and any content or usage rules.
4. Try representative benign tasks and relevant edge cases; inspect outputs rather than relying on the “uncensored” label.
5. For agent or production use, test permissions, error behavior, and cost boundaries in a controlled environment first.

There is no cross-modality quality ranking in this index. A candidate being listed means it is documented in a companion catalog, not that it has been independently tested or recommended for every use.

## Inclusion principles

- Record the exact model/checkpoint or hosted route and the date verified.
- Distinguish open weights, community fine-tunes, adapters, and hosted endpoints.
- Treat “uncensored” as a qualified behavior report, not a promise or a license.
- Link to primary model cards and provider documentation in the modality catalog; do not infer derivative provenance from the base model.
- Track licensing, availability, filtering layers, and reproducibility where known.
- Keep detailed model tables in the modality catalog that owns them; this index gives cross-modality discovery and representative coverage.
- Organize entries by access path and use case; do not imply that a hosted service serves the same weights as a linked public checkpoint unless that is verified.

## Contributing

Open issues or pull requests in the relevant modality catalog. Include a primary source, exact version, access method, licensing information, and reproducible notes. See each catalog's contribution guide for its entry format.

## Responsible use

Use these resources lawfully and responsibly. Do not create or facilitate sexual content involving minors, non-consensual intimate imagery, targeted harassment, fraud, impersonation, or other illegal or abusive material. Follow model licenses, service terms, and applicable law.

## License

The original directory and documentation are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Individual models and linked resources retain their own licenses and terms.
