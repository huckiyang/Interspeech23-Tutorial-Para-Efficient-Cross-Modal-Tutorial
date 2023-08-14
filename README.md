# Interspeech 2023 Tutorial

(Now) Interspeech 23 - `Resource Efficient and Cross-Modal Learning Toward Foundation Modeling Tutorial`

- ICASSP 22 Tutorial `Neural Model Reprogramming and Prompting for Speech Modeling` - [Video](https://www.youtube.com/watch?v=-iirkbYkyXI) | [Slide](https://docs.google.com/presentation/d/1sXcxYiTHY_URovr2irb6QvQj7xFIQd1tzObz4SpyEfo/edit) 
- ICASSP 23 Tutorial `Parameter-Efficient Learning (PEL) for Speech and NLP: Adapters, Prompts, and Reprogramming` [Slide](https://docs.google.com/presentation/d/16ypY73W0xC0WQxkPUtjchxjhzY8XehTEgRSuMJD4QdM/edit?usp=sharing)

## Part 1. Overview of Resource Efficient Learning

### 1.1. Parameter-Efficient Learning

- Background of Frozen Model Adaptation
- Neural Adapter, Reprogramming, Prompting, and Low-Rank Adaptation (LoRA) 

| Title | Authors | Code | Year |
| ----- | ------- | -------- | ---- |
|[Differentially Private Adapters for Parameter Efficient Acoustic Modeling](https://arxiv.org/abs/2305.11360)|C.-W. Ho et al.|[code](https://github.com/Chun-wei-Ho/)|Interspeech 2023|
|[Parameter-Efficient Learning for Text-to-Speech Accent Adaptation](https://arxiv.org/abs/2305.11320)|L.-J. Yang et al.|[code](https://tts-research.github.io/)|Interspeech 2023|
|[A Parameter-Efficient Learning Approach to Arabic Dialect Identification with Pre-Trained General-Purpose Speech Model](https://arxiv.org/pdf/2305.11244)|S. Radhakrishnan et al.|[code](https://github.com/Srijith-rkr/KAUST-Whisper-Adapter)|Interspeech 2023|

### 1.2. Memory-Efficient Learning

- Reduce to GPU / TPU Memory During the Training (e.g., the Memory of Activation)
- Model Serialization
- Efficient On-Device Learning via Feature Reprogramming (CVPR 2022)
- Ladder-Side Tuning (NeurIPS 2022)

#### 1.3 How to Estimate which Layer or which Model to Tune?

- Universal Approximation Theory (IEEE TIP 1993)
- LogME: Practical Assessment of Pre-trained Models for Transfer Learning (ICML 2021)
- Latent Space Alignment in "Reprogramming Acoustic Models for Time Series Classification" (ICML 2021)

| Title | Authors | Code | Year |
| ----- | ------- | -------- | ---- |
|[How to Estimate Model Transferability of Pre-Trained Speech Models?](https://arxiv.org/pdf/2306.01015.pdf)|Z.-C. Chen et al.|[code](https://github.com/virginiakm1988/LogME-CTC)|Interspeech 2023|

#### 1.4 Advanced Low-Rank Adaptation (LoRA) Techniques

- Cross-Modal Merging
- Low-Rank Adaptation (LoRA) for Foundation Modeling and Pre-Training

#### 1.5 Community Service

- Special Session in ICASSP 2024: In-Context Learning for Speech and Language Processing
- icassp24-icl-sp@googlegroups.com

#### Break: Hand-on Session 1 (5 min)

- How to Train Your Whisper with Neural Adapter and LoRA


## Part 2: Multi-Modal and Cross-Modal Learning

## Part 3: Neural Model Reprogramming and On-Device Tuning




