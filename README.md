# FashionAIStudio

👗🤖 FashionAIStudio is an innovative project that combines artificial intelligence with fashion design, allowing users to create virtual fashion designs using the power of AI.

## Description

FashionAIStudio is a virtual fashion design platform that leverages the capabilities of generative AI models to generate unique and creative fashion designs. Users can interact with the platform to explore different styles, experiment with colors and patterns, and generate personalized fashion designs tailored to their preferences.

## Usage

- Run [`fashion_ai_studio.ipynb`](link-to-colab) to start creating your own fashion designs!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](link-to-colab)

## Results

![Fashion Design 1](images/fashion_design_1.jpg)
![Fashion Design 2](images/fashion_design_2.jpg)
![Fashion Design 3](images/fashion_design_3.jpg)

<sub>
Different fashion designs generated with FashionAIStudio using various prompts.
</sub>

## References

[1] Rombach, Robin, et al. [*High-resolution image synthesis with latent diffusion models*][stable-diffusion-paper]. CVPR 2022.
([models][huggingface-models] & [demo][huggingface-demo])

[2] Karras, Tero, et al. [*Elucidating the Design Space of Diffusion-Based Generative Models*][sampler-schedule-paper]. NeurIPS 2022. ([code][edm-implementation])

[3] Luo, Simian, et al. [*Latent Consistency Models: Synthesizing HR Images with Few-Step Inference.*][lcm-paper] arXiv 2023. ([code][lcm-github])

[4] Luo, Simian, et al. [*LCM-LoRA: A Universal Stable-Diffusion Acceleration Module.*][lcm-lora-paper] arXiv 2023.

[stable-diffusion-paper]: <https://openaccess.thecvf.com/content/CVPR2022/html/Rombach_High-Resolution_Image_Synthesis_With_Latent_Diffusion_Models_CVPR_2022_paper.html>
[sampler-schedule-paper]: <https://arxiv.org/abs/2206.00364>
[lcm-paper]: <https://arxiv.org/abs/2310.04378>
[lcm-lora-paper]: <https://arxiv.org/abs/2311.05556>

[huggingface-blogpost]: <https://huggingface.co/blog/stable_diffusion>
[huggingface-lcm-blogpost]: <https://huggingface.co/blog/lcm_lora>
[huggingface-models]: <https://huggingface.co/CompVis/stable-diffusion>
[huggingface-latest-weights]: <https://huggingface.co/stabilityai/sdxl-turbo>
[huggingface-sd2-resolution-512]: <https://huggingface.co/stabilityai/stable-diffusion-2-1-base>
[huggingface-sd2-resolution-768]: <https://huggingface.co/stabilityai/stable-diffusion-2-1>
[huggingface-sd2-examples]: <https://huggingface.co/stabilityai/stable-diffusion-2#examples>
[huggingface-sd21-examples]: <https://huggingface.co/stabilityai/stable-diffusion-2-1#examples>
[huggingface-demo]: <https://huggingface.co/spaces/stabilityai/stable-diffusion>
[dreamstudio-demo]: <http://beta.dreamstudio.ai>
[edm-implementation]: <https://github.com/NVlabs/edm>
[lcm-github]: <https://github.com/luosiallen/latent-consistency-model>
