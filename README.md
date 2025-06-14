# Flux-LoRATrainer
A standalone Flux trainer that I needed for experimenting.

Planned:
1. https://arxiv.org/abs/2402.02347 LoRA preconditioning. Ablate and see convergence on Flux LoRA training
2. Losses: AuraFace (person lora's), CSD (style lora's), Prior preservation loss
3. Are layers 9 and 25 enough ? Or should I use the layers as painters results to pick the layers ?
4. Reward training. imscore + DRaFT. https://arxiv.org/abs/2309.17400
