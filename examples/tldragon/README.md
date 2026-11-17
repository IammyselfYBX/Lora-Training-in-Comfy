# tldragon example

This example trains and uses a chibi dragon mascot LoRA directly inside ComfyUI.

- Base checkpoint: `SD1.5/2.5D/2.5D_disneyPixarCartoon_v10.safetensors`
- Trigger token: `tldragon`
- Training images: 8 unique images after near-duplicate filtering
- Repeats: 10 per image
- Epochs: 10
- Total steps: 800
- LoRA strength: model `0.88`, CLIP `0.78`

Workflows:

- `01_train_lora.json`
- `02_generate.json`

The workflows contain absolute paths from the original 3090 installation. Change `data_path`, checkpoint names, and output directories if using another machine.
