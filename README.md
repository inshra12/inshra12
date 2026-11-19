# Hi 👋, I'm Inshara Liaquat

**MS Software Engineering | AI Researcher | Protein ML → VLA Robotics**

## About Me

I am an MS Software Engineering graduate/researcher working on deep learning and computational biology.

My previous research focused on automated protein function prediction using:

- protein language models such as ESM2 and ProtBERT,
- controlled feature ablations,
- molecular dynamics data,
- explainable AI,
- multi-label Gene Ontology classification,
- reproducible machine learning pipelines.

I am currently expanding my research toward **Vision-Language-Action (VLA) models, robot learning, and embodied AI**.

My current goal is to build reproducible experience in:

- vision-language embodied systems,
- robotic manipulation benchmarks,
- failure analysis,
- multimodal representation learning,
- controlled model evaluation,
- and real-world generalization.

I am seeking a funded MS/PhD or research position in embodied AI or robotics.

## Current VLA Project

### SmolVLA on LIBERO Spatial

I evaluated the pretrained `HuggingFaceVLA/smolvla_libero` model on three tasks from the LIBERO Spatial benchmark.

A pilot run of five episodes per task produced:

| Task | Success / Episodes | Success rate |
|---|---:|---:|
| Task 0 | 3/5 | 60% |
| Task 1 | 4/5 | 80% |
| Task 2 | 5/5 | 100% |

**Overall:** 12/15 episodes succeeded across the selected tasks.

This project demonstrates:

- installing modern LeRobot and VLA environments,
- running SmolVLA in a Google Colab GPU environment,
- evaluating manipulation episodes in simulation,
- preserving rollout logs and videos,
- analyzing unsuccessful episodes,
- and clearly reporting pilot limitations.

Repository: [SmolVLA-LIBERO-Evaluation](https://github.com/inshra12/SmolVLA-LIBERO-Evaluation)

> This is a small pilot study, not a full LIBERO benchmark or publication-level result.

## Protein Function Prediction Research

### GO-Term Prediction and Ablation

- Developed controlled ablation studies for multi-label Gene Ontology prediction.
- Compared ESM2 and ProtBERT sequence representations with molecular dynamics features.
- Evaluated MLP, 1D-CNN, Transformer, and residual architectures.
- Used homology-aware evaluation and multiple feature combinations.
- Applied Integrated Gradients to interpret model predictions.
- Conducted reproducibility and controlled-comparison analysis.

Representative projects:

- [ATLAS-GO-Dynamics](https://github.com/inshra12/ATLAS-GO-Dynamics)
- [protein-go-prediction](https://github.com/inshra12/protein-go-prediction)
- [proteinseek](https://github.com/inshra12/proteinseek)

## Technical Skills

- Python and PyTorch
- Transformers and pretrained representations
- Multi-label machine learning
- Model evaluation and ablation studies
- Explainable AI
- NumPy, Pandas, and Scikit-learn
- Jupyter and Google Colab
- Hugging Face ecosystem
- LeRobot and simulated robot evaluation
- Git and GitHub

## Research Interests

- Vision-Language-Action models
- Embodied AI
- Robot manipulation
- Multimodal learning
- Failure analysis
- Robot generalization
- Model interpretability
- Reproducible benchmark evaluation
- Efficient fine-tuning

## Research Identity

I am a software engineering graduate building from experience in pretrained representation learning toward embodied intelligence.

Rather than presenting VLA research as a completed specialization, I document:

- what I have reproduced,
- what I have measured,
- what I observed,
- what remains uncertain,
- and what I plan to investigate next.

## Contact

- Email: [inshraliaquat@gmail.com](mailto:inshraliaquat@gmail.com)
- LinkedIn: [inshara-liaquat](https://linkedin.com/in/inshara-liaquat)
- GitHub: [inshra12](https://github.com/inshra12)
