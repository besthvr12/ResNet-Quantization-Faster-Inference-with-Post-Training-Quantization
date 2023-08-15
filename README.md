# ResNet-Quantization-Faster-Inference-with-Post-Training-Quantization
# PyTorch Quantization Showcase

Welcome to the PyTorch Quantization Showcase notebook! Prepare to embark on a journey that unveils the magic of quantization in PyTorch – a journey that will reveal the power of minimizing model size and maximizing speed.

## Overview

🚀 **Speed & Size**: Witness the mesmerizing transformation as quantization defies expectations, drastically reducing model size and accelerating speed. 

🔌 **Hardware Compatibility**: A friendly reminder that quantization's current partner is none other than CPUs. As we venture into the quantization realm, GPUs / CUDA take a graceful step back during training, while CPUs take the lead in testing.

🎯 **Navigating Accuracy**: Delve into the intricate world of complex datasets, where quantization's accuracy prowess may face challenges. Fear not, for we have a secret weapon: a quantization configuration with the power to restore accuracy to its rightful throne.

```python
model.qconfig = torch.quantization.get_default_qconfig('fbgemm')
```
Watch as this line works its magic, reviving accuracy while preserving efficiency.

🔮 Strategies Unveiled: Our journey doesn't stop there. We'll retrace our steps with a recommended quantization configuration tailored for x86 architectures. Brace yourself for the unveiling of strategies, including:

Quantizing weights channel by channel, a precision dance.
Embracing a histogram observer that captures activation stories, paving the way for optimal quantization parameter selection.
The stage is set, the strategies poised – immerse yourself in the world of quantization wizardry!
