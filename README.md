# RTXStableDiffusionXL
In this repository we use the Hugging Face Stable Diffusion XL (SDXL) model to create images from text prompts, based on a Jupiter Notebook installed using [NVIDIA AI Workbench](https://www.nvidia.com/en-us/deep-learning-ai/solutions/data-science/workbench/). We are also going to fine-tune the SDXL model based on our own images, using DreamBooth.

## System Requirements:
* Operating System: Ubuntu 22.04 or Windows 10/11, tested on Windows 11
* CPU requirements: None, tested with AMD Ryzen 7 7800x3D @ 5.05GHz
* GPU requirements: Any NVIDIA GPU, tested with NVIDIA RTX 4070
* NVIDIA AI Workbench: Last tested on version 0.44.8.2142
* NVIDIA driver requirements: Latest driver version
* Memory: At least 32GB of RAM
* Storage requirements: At least 50GB

# Quickstart
First install , and then:
1. Download and Install NVIDIA AI Workbench

   ```
   https://www.nvidia.com/en-us/deep-learning-ai/solutions/data-science/workbench/
   ```
   
2. When asked what type of container runtime software you would like to use, I have selected Docker (but Podman should also work)
 
3. After the AI Workbench is installed and running, clone the Nvidia SDXL main project into your projects

   ```
   https://github.com/NVIDIA/workbench-example-sdxl-customization
   ```
   
4. Open the Project
 
5. Start JupyterLab

6. Navigate to the ```code``` folder of the project. Then, open the notebook titled ```FineTuning-SDXL.ipynb``` and get started.

## License
This NVIDIA AI Workbench example project is under the [Apache 2.0 License](https://github.com/nv-edwli/sdxl-customization/blob/main/LICENSE.txt)

This project will utilize additional third-party open source software projects. Review the license terms of these open source projects before use. Third party components used as part of this project are subject to their separate legal notices or terms that accompany the components. You are responsible for confirming compliance with third-party component license terms and requirements. 
