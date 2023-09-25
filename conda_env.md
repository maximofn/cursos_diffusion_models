conda create -y -n diffusion_models -y python=3.9
conda activate diffusion_models

pip install --upgrade git+https://github.com/huggingface/diffusers.git transformers accelerate scipy safetensors
mamba install -y -c anaconda ipykernel ipywidgets