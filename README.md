# sm/decide

A lightweight decision advisor for SageMaker customization.

## Why
Teams often start training with the wrong customization path because the decision between SageMaker Model Customization and Nova Forge is not obvious upfront. `sm/decide` helps users choose the right route before they spend time and compute.

## Customer
- ML engineers and applied scientists using SageMaker
- Technical product teams evaluating customization options for domain use cases
- Platform teams standardizing model-tuning decisions across internal teams

## Problems This Solves
- Clarifies when to use SageMaker Model Customization vs. Nova Forge
- Recommends the right fine-tuning method (SFT, DPO, RFT-verifiable, RFT-AI-judge)
- Reduces costly trial-and-error training runs
- Makes decision logic transparent with explainable output and next steps
