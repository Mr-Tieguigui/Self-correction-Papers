# Self-correction-Papers






## Related Survey Papers
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| When Can LLMs Actually Correct Their Own Mistakes A Critical Survey of Self-Correction of LLMs (PSU 2024)| | [arXiv](https://arxiv.org/abs/2406.01297) |
| Automatically Correcting Large Language Models: Surveying the Landscape of Diverse Automated Correction Strategies (UCSB 2024) | | [TACL](https://aclanthology.org/2024.tacl-1.27/) |



## Reasoning Elevation
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| LILA: A Unified Benchmark for Mathematical Reasoning (ASU 2022) | | [EMNLP](https://arxiv.org/pdf/2210.17517) |
| RATT: A Thought Structure for Coherent and Correct LLM Reasoning (PSU 2024) | | [arXiv](https://arxiv.org/abs/2406.02746) |
| Training Language Models to Self-Correct via Reinforcement Learning (Google 2024) |  | [arXiv](https://arxiv.org/pdf/2409.12917)|
| LLMs cannot find reasoning errors, but can correct them given the error location (Cambridge 2024) | | [ACL](https://arxiv.org/abs/2311.08516) |


## Refining with Responses
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| Small Language Models Need Strong Verifiers to Self-Correct Reasoning (UMich 2024)  |  | [ACL](https://arxiv.org/pdf/2404.17140)|
| Fine-Tuning with Divergent Chains of Thought Boosts Reasoning Through Self-Correction in Language Models (TUDa 2024)  |  | [arXiv](http://arxiv.org/abs/2407.03181)|

## Hallucination Alleviation
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| From Code to Correctness: Closing the Last Mile of Code Generation with Hierarchical Debugging (SJTU 2024) | | [arXiv](https://arxiv.org/pdf/2410.01215) |
| Generating Sequences by Learning to Self-Correct (AI2 2023) | | [ICLR](https://arxiv.org/abs/2211.00053) |
| The Capacity for Moral Self-Correction in Large Language Models (Anthropic 2024) | | [arXiv](https://arxiv.org/abs/2302.07459) |

## Meta Evaluation
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| CriticBench: Benchmarking LLMs for Critique-Correct Reasoning (THU 2024) | | [ACL](https://arxiv.org/abs/2402.14809) |

## Theoretical Perspectives
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| A Theoretical Understanding of Self-Correction through In-context Alignment (MIT 2024)| | [ICML](https://arxiv.org/abs/2405.18634) |
| Large Language Models Cannot Self-Correct Reasoning Yet (ICLR 2024)  |  | [ICLR](https://arxiv.org/pdf/2310.01798)|
| Large Language Models have Intrinsic Self-Correction Ability (UB 2024)| | [arXiv](https://arxiv.org/abs/2406.15673) |
| On the Intrinsic Self-Correction Capability of LLMs: Uncertainty and Latent Concept (MSU 2024) | | [arXiv](https://arxiv.org/abs/2406.02378) |
| SELF-[IN]CORRECT LLMs Struggle with Discriminating Self-Generated Responses (JHU 2024)  |  | [arXiv](https://arxiv.org/pdf/2404.04298v3)|
| Fine-Tuning with Divergent Chains of Thought Boosts Reasoning Through Self-Correction in Language Models (2024)| | [arXiv](https://arxiv.org/abs/2407.03181) |



## Methods

| Method  | Category | Link | Task | Dataset | Model | Open address | Citation|
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |------------- |
| Intrinsic Method | - | - | - | - | - | - |
| CoVe (2023) | (Junran Wu)Intrinsic | [arXiv](https://arxiv.org/abs/2309.11495) | - | - | - | - | 202 |
| CAI Revisions (2022) | (Junran Wu)Intrinsic | [arXiv](https://arxiv.org/abs/2212.08073) | - | - | - | - | 952 |
| Self-Refine (2023) | (Junran Wu)Intrinsic | [arXiv](https://arxiv.org/abs/2303.17651) | - | - | - | - | 789 |
| RCI (2023) | (Chaoran Hu)Oracle | [arXiv](https://arxiv.org/abs/2303.17491) | Reasoning, Computer tasks | SingleEq, AddSub, MultiArith, AQuA, GSM8K, SVAMP, AQuA, CommonSenseQA, StrategyQA, MiniWoB++  | GPT-3, GPT-3.5-turbo, GPT-4, InstructGPT-3 | [代码仓库](https://github.com/posgnu/rci-agent) | 229 |
| Reflexion.1 (2023) | (Chaoran Hu)Oracle | [arXiv](https://arxiv.org/abs/2303.11366) | Decision-making | ALFWorld, WebShop | GPT-3 | [代码仓库](https://github.com/noahshinn/reflexion) | 639 |
| ------------- | ------------- | -------------| ------------- | ------------- | ------------- | ------------- |------------- |
| External Method | - | - | - | - | - | - | - |
| Reflexion.2 (2023) | (Chaoran Hu)Fair-Asym | [arXiv](https://arxiv.org/abs/2303.11366) | Reasoning | HotPotQA | - | [代码仓库](https://github.com/noahshinn/reflexion) | 639 |
| Reflexion.3 (2023) | (Chaoran Hu)Oracle | [arXiv](https://arxiv.org/abs/2303.11366) | Programming | MBPP, HumanEval, LeetcodeHardGym | MultiPL-E, text-davinci-003, GPT-3.5-turbo, GPT-4 | [代码仓库](https://github.com/noahshinn/reflexion) | 639 |
| Self-Debug (2024) | (Tianhe Gu)Fair-Asym | [arXiv](https://arxiv.org/abs/2304.05128) | text-to-SQL generation, code translation, text-to-Python generation | Spider benchmark,TransCoder, MBPP | code-davinci-002(Codex), gpt-3.5-turbo, gpt-4,StarCoder with15.5B | None | 381 |
| CRITIC (2024) | (Tianhe Gu)Fair-Asym | [arXiv](https://arxiv.org/abs/2305.11738) | free-form QA, mathematical program synthesis, toxicity reduction | AmbigNQ, TriviaQA, HotpotQA | ChatGPT, Text-Davinci-003, open-sourceLLaMA-2 variants (7B, 13B, and 70B) | [repo](https://github.com/microsoft/ProphetNet/tree/master) | 147 |
| RARR (2023) | (Tianhe Gu)UnfairAsym | [arXiv](https://arxiv.org/abs/2210.08726) | Measuring attribution，Measuring preservation | QReCC, StrategyQA | PaLM (540B), GPT-3 text-davinci-002, EFEC, LaMDA | [repo](https://github.com/anthonywchen/RARR) | 177 |
| ------------- | ------------- | -------------| ------------- | ------------- | ------------- | ------------- |------------- |
| Fine-tuning Method | - | - |  - | - | - | - | - |
| Self-Critique (2022) | (Ruihang Zhang)Fair-Asym | [arXiv](https://arxiv.org/abs/2206.05802) | QA，Critiqueability，Critique，Helpfulness ，Conditional refinement ，Direct refinement |   six files located at [Dataset](https://openaipublic.blob.core.windows.net/critiques/dataset/):<br/>train.jsonl.gz, base/test.jsonl.gz, critiques/train.jsonl.gz,critiques/test.jsonl.gz, helpfulness/train.jsonl.gz, helpfulness/test.jsonl.gz | GPT-3 | - | 173 |
| SelFee (2023) | (Ruihang Zhang)Fair-Asym | [blogpost](https://lklab.kaist.ac.kr/SelFee/) | Creative Writing,Long-form text generation,Math, Reasoning, Factuality, Coding | [Dataset](https://huggingface.co/datasets/kaist-ai/selfee-train) | LLaMA model (7B, 13B) ,Alpaca, Vicuna，GPT-4 | [代码仓库](https://github.com/kaistAI/SelFee) | 39 |
| Baldur (2023) | (Ruihang Zhang)Fair-Asym | [arXiv](https://arxiv.org/abs/2303.04910) | Proof Generation，Proof Repair，Adding Context | PISA, Isabelle/HOL | Minerva,GPT-4 | - | 78 |
| REFINER (2023) | (Ruihan Gong)Cross-Model | [arXiv](https://arxiv.org/abs/2304.01904) | MWP, SNLR, MS | MAWPs, SVAMP, GSM8K | UQA-base, UQA-large, GPT-3.5-text-DaVinci-003, REFINER | [CODE](https://github.com/debjitpaul/refiner) | 103 |
| RL4F (2023) | (Ruihan Gong)Cross-Model | [arXiv](https://arxiv.org/abs/2305.08844) | Alphabetization | Interscript | GPT-3 | [CODE](https://github.com/feyzaakyurek/rl4f) | 69 |
| Self-Correction (2023) | (Ruihan Gong)Cross-Model | [arXiv](https://arxiv.org/abs/2211.00053) | mathematical program synthesis, lexically-constrained generation,  toxicity control | MultiArith, AddSub, SingleOp, SVAMP, GSM8k | GPT-Neo 1.3B, GPT-3, GPT-2 | - | 30 |
| ------------- | ------------- | -------------| ------------- | ------------- | ------------- | ------------- |------------- |
| Cannot (2023) | Intrinsic | [arXiv](https://arxiv.org/abs/2310.01798) | Reasoning, QA | GSM8K, CommonSenseQA, HotpotQA | GPT-3.5, GPT-4, Llama-2, GPT-4-Turbo | [代码仓库](https://github.com/Mr-Tieguigui/Self-correction-Papers/) | 192 |





## Datasets
| Dataset  | Description | Link |
| ------------- | ------------- | -------------|




## Task
| Task  | Description | Link |
| ------------- | ------------- | -------------|
| Reasoning | | |
| Knowledge | | |
| Context-based Generation| | |
| Oracle information| | |
| Others| | |







## Model Automatically Correction 

### Error types of LLMs to correct
- `Hallucination`: LLMs often hallucinate by making up facts or citing sources that do not exist.
- `Unfaithful Reasoning`: LLMs occasionally make unfaithful reasoning, i.e., the derived conclusion does not follow the previously generated reasoning chain.
- `Toxic, Biased, and Harmful Content`: LLMs have been observed to occasionally generate content that is toxic, biased, or harmful due to biases present in the training data.


### Source of the Feedback
- `Intrinsic Self-Feedback`: The LLM can act as its own feedback provider by iteratively assessing and refining its generated outputs until it meets a certain standard.
- `External Feedback`: External tools, External knowledge, Oracle information


### Format of the Feedback
- `Scalar Value Feedback`:
- `Natural Language Feedback`: 


### Timing of correct
- `Training-time Correction`: rectify a flawed model during training.
- `Generation-time Correction`: It utilizes automated feedback to guide the LLM to correct errors during generation.
- `Post-hoc Correction`: It refines the model output after it has been generated, without updating the model parameters (Self-Correction, Correction with External Feedback, and Multi-Agent Debate).

### Self-Correction






