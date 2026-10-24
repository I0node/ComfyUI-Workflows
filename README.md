# ComfyUI-Workflows
Custom workflows made by me to identify nodes that should be together into one custom node pack.

## Dependencies
- ComfyUI Impact Pack
- ComfyUI-Custom-Scripts
- efficiency-nodes-comfyui
- WAS Node Suite (Revised)
- ComfyUI-Metadata-Extractor
- XENodes

## Workflow json schemas

- **batch_emptylatent.json**:  Creates multiple images from empty latent using txt2img techniques.
- **img2img_batch_pnginfo.json**:  Creates multiple images using img2img techniques and extracting metadata from each image.
- **img2img_clipv-blip.json**:  Creates multiple images using img2img techniques and using clip vision/blip as guidance tools.
- **img2img_promptrefiner_pnginfo.json**:  Creates multiple images using img2img techniques and using llm clip to refine extracted prompts.
- **llm_qwen3vl_img2txt.json**:  Text encoder llm centric img2txt workflow.
- **model_latent_upscale.json**:  Creates a single upscaled image using txt2img techniques.
- **sd3_5medium-t5-fp8.json**:  Stable Diffusion 3.5 (with clip) centric txt2img workflow.
- **txt2img_highresfix.json**:  Shrinking upscaled img2img technique using highres fix script.
- **dynamic_checkpoint.json**: Random checkpoint selector using primitive randomization of index fixed range with seed generator.
- **rand_lora.json**: Random lora selector using primitive randomization of index fixed range with uses a seed generator.
- **img2img_promptrefiner_pnginfo_logging.json**: Creates a llm to refine a prompt from prompt+image reference from a folder, with logging.
- **txt2img_highresfix.json**: Creates multiple images (not suggested) from empty latent using txt2img, upscaling and downscaling techniques.
  
