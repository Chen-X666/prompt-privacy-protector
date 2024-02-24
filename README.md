# Privacy-Preserving Prompt Tuning for Large Language Model

⬜️: white-box 

⬛️: black-box
## Attacker

### Inference Attacks
| Paper | Year |  Source         |  Attack Prompt Type  |
|-------|------|-----------------|----------------------|

### Prompt Injection Attacks
| Paper | Year |   Source              |  Attack Prompt Type  |   Tasks   |
|-------|------|-----------------------|----------------------|-----------|
| ⬛️TrojLLM: A Black-box Trojan Prompt Attack on Large Language Models  |  (NeurIPS, 2023)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2306.06815) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/UCF-ML-Research/TrojLLM)  | Instruction prompt |
| ⬛️Ignore Previous Prompt : Attack Techniques For Language Models  |  (NeurIPS, 2022)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2211.09527) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/agencyenterprise/PromptInject)  | Instruction prompt, In-context learning |
| ⬜️BadPrompt: Backdoor Attacks on Continuous Prompts  |  (NeurIPS, 2022)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2211.14719) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/papersPapers/BadPrompt)  | Instruction prompt|
| ⬜️PromptAttack: Prompt-based Attack for Language Models via Gradient Search  |  (NLPCC, 2022)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2209.01882)  | Instruction prompt |

### Model Reverse Engineering


## Protector Methodology

### Differential Privacy (DP)
| Paper | Year |  Source          |  Tasks  |
|-------|------|------------------|---------|
| ⬛️Privacy-Preserving In-Context Learning with Differentially Private Few-Shot Generation  |  (ICLR, 2024)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2309.11765) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/microsoft/dp-few-shot-generation)  | Classification, Information Extraction | 
| ⬛️DP-OPT: Make Large Language Model Your Privacy-Preserving Prompt Engineer  |  (ICLR, 2024)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2312.03724) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/VITA-Group/DP-OPT)  | Sentiment Classification |
| ⬛️Privacy-Preserving In-Context Learning For Large Language Models  |  (ICLR, 2024)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2305.01639)  |  Classification, Document Q&A, Dialog Summarization | 
| ⬛️InferDPT: Privacy-preserving Inference for Black-box Large Language Models  |  2023.12   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2310.12214)  |  Classification, Generation |
| ⬛️Flocks of Stochastic Parrots: Differentially Private Prompt Learning for Large Language Models  | (NeurIPS, 2023)  | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2305.15594)  | Text Classification |
| ⬛️Locally Differentially Private Document Generation Using Zero Shot Prompting  |  (EMNLP, 2023)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://aclanthology.org/2023.findings-emnlp.566) [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/SaitejaUtpala/dp_prompt)  | Text Classification | 
| ⬜️Privacy-Preserving Prompt Tuning for Large Language Model Services  | 2023.05  | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2305.06212)  | Sentiment Classification, Document Q&A |


### Homomorphic Encryption (HE)
| Paper | Year |  Arxiv    |     Source      |
|-------|------|-----------|-----------------|
| Iron: Private Inference on Transformers  |   (NeurIPS, 2022)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://proceedings.neurips.cc/paper_files/paper/2022/hash/64e2449d74f84e5b1a5c96ba7b3d308e-Abstract-Conference.html) |  [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/xingpz2008/Iron) | 
| LLMs Can Understand Encrypted Prompt: Towards Privacy-Computing Friendly Transformers  |   (NeurIPS, 2022)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2305.18396) | unavailable | 


### Secure Multi-Party Computing (SMPC)
| Paper | Year |  Arxiv    | Source     |
|-------|------|-----------|------------|
| SecFormer: Towards Fast and Accurate Privacy-Preserving Inference for Large Language Models  |  2024.01   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2401.00793) | unavailable  | 

### Federated Learning (FL)
| Paper | Year |  Arxiv    | Source     |
|-------|------|-----------|------------|
|  FATE-LLM: A Industrial Grade Federated Learning Framework for Large Language Models  |  2023.10  | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2310.10049) | [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/FederatedAI/FATE-LLM)  |
|  FederatedScope-LLM: A Comprehensive Package for Fine-tuning Large Language Models in Federated Learning  |  2023.09  | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2309.00363) | [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/alibaba/FederatedScope/tree/llm)  |

### Anonymization Techniques
| Paper | Year |  Arxiv    | Source     |
|-------|------|-----------|------------|
| ⬛️Hide and Seek (HaS): A Lightweight Framework for Prompt Privacy Protection  |  2023.09   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2309.03057) | [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/alohachen/Hide-and-Seek)  | 

### Other Methods
| Paper | Year |  Arxiv    | Source     | Method Keyword |
|-------|------|-----------|------------|----------------|
| SentinelLMs: Encrypted Input Adaptation and Fine-tuning of Language Models for Private and Secure Inference  |  (AAAI, 2024)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2312.17342) | [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/abhijitmishra/sentinellm-aaai2024)  | 
| Privatelora For Efficient Privacy Preserving LLM  |  (CoRR, 2023)   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2311.14030) | [![Static Badge](https://img.shields.io/badge/code-black?logo=github)](https://github.com/alipay/private_llm)  |
| Recovering from Privacy-Preserving Masking with Large Language Models  |  2023.12   | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2309.08628) | unavailable  | [MASK] 

#### Fine-tuning
| Paper | Year |  Arxiv    | Source     |。 Tasks |
|-------|------|-----------|------------|---------|
| Differentially Private Model Compression  | (NeurIPS, 2022)  | [![Static Badge](https://img.shields.io/badge/paper-%23B31B1B?logo=arxiv&labelColor=grey)](https://arxiv.org/abs/2206.01838) | unavailable  | 

