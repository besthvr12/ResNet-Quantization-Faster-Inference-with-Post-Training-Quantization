# ResNet-Quantization-Faster-Inference-with-Post-Training-Quantization
# PyTorch Quantization Showcase

Welcome to the PyTorch Quantization Showcase notebook! Prepare to embark on a journey that unveils the magic of quantization in PyTorch – a journey that will reveal the power of minimizing model size and maximizing speed.

## Overview

🚀 **Speed & Size**: Witness the mesmerizing transformation as quantization defies expectations, drastically reducing model size and accelerating speed. 

🔌 **Hardware Compatibility**: A friendly reminder that quantization's current partner is none other than CPUs. As we venture into the quantization realm, GPUs / CUDA take a graceful step back during training, while CPUs take the lead in testing.

🎯 **Navigating Accuracy**: Delve into the intricate world of complex datasets, where quantization's accuracy prowess may face challenges. Fear not, for we have a secret weapon: a quantization configuration with the power to restore accuracy to its rightful throne.

```python
model.qconfig = torch.quantization.get_default_qconfig('fbgemm')

<p align="center">
  <img src="project-screenshot.png" alt="Project Screenshot" class="project-image">
</p>
</body>
</html>
```
