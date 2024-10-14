# Self-correction-Papers






## Related Survey Papers
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
| When Can LLMs Actually Correct Their Own Mistakes A Critical Survey of Self-Correction of LLMs (PSU 2024)| | [arXiv](https://arxiv.org/abs/2406.01297) |
| Automatically Correcting Large Language Models: Surveying the Landscape of Diverse Automated Correction Strategies (UCSB 2024) | | [TACL](https://aclanthology.org/2024.tacl-1.27/) |



## Reasoning Elevation
| Paper  | Description | Link |
| ------------- | ------------- | -------------|
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
()
| Method  | Category | Link | Task | Dataset | Model | Open address | Citation|
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |------------- |
| Intrinsic Method | - | - | - | - | - | - |
| CoVe (2023) | Intrinsic | [arXiv](https://arxiv.org/abs/2309.11495) | - | - | - | - | - |
| CAI Revisions (2022) | Intrinsic | [arXiv](https://arxiv.org/abs/2212.08073) | - | - | - | - | - |
| Self-Refine (2023) | Intrinsic | [arXiv](https://arxiv.org/abs/2303.17651) | - | - | - | - | - |
| RCI (2023) | Oracle | [arXiv](https://arxiv.org/abs/2303.17491) | - | - | - | - | - |
| Reflexion.1 (2023) | Oracle | [arXiv](https://arxiv.org/abs/2303.11366) | - | - | - | - | - |
| ------------- | ------------- | -------------| ------------- | ------------- | ------------- | ------------- |------------- |
| External Method | - | - | - | - | - | - | - |
| Reflexion.2 (2023) | Fair-Asym | [arXiv](https://arxiv.org/abs/2303.11366) | - | - | - | - | - |
| Reflexion.3 (2023) | Oracle | [arXiv](https://arxiv.org/abs/2303.11366) | - | - | - | - | - |
| Self-Debug (2024) | Fair-Asym | [arXiv](https://arxiv.org/abs/2304.05128) | - | - | - | - | - |
| CRITIC (2024) | Fair-Asym | [arXiv](https://arxiv.org/abs/2305.11738) | - | - | - | - | - |
| RARR (2023) | UnfairAsym | [arXiv](https://arxiv.org/abs/2210.08726) | - | - | - | - | - |
| ------------- | ------------- | -------------| ------------- | ------------- | ------------- | ------------- |------------- |
| Fine-tuning Method | - | - |  - | - | - | - | - |
| Self-Critique (2022) | Fair-Asym | [arXiv](https://arxiv.org/abs/2206.05802) | - | - | - | - | - |
| SelFee (2023) | Fair-Asym | [blogpost](https://lklab.kaist.ac.kr/SelFee/) | - | - | - | - | - |
| Baldur (2023) | Fair-Asym | [arXiv](https://arxiv.org/abs/2303.04910) | - | - | - | - | - |
| REFINER (2023) | Cross-Model | [arXiv](https://arxiv.org/abs/2304.01904) | - | - | - | - | - |
| RL4F (2023) | Cross-Model | [arXiv](https://arxiv.org/abs/2305.08844) | - | - | - | - | - |
| Self-Correction (2023) | Cross-Model | [arXiv](https://arxiv.org/abs/2211.00053) | - | - | - | - | - |
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






