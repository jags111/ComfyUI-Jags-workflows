##ANIMATE DIFF WORKFLOWS

Install required ComfyUI nodes and models from this repository

https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved

https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet

#AnimateDiff for ComfyUI
Improved AnimateDiff integration for ComfyUI, initially adapted from sd-webui-animatediff but changed greatly since then. Please read the AnimateDiff repo README for more information about how it works at its core.

Examples shown here will also often make use of these helpful sets of nodes:

ComfyUI_FizzNodes for prompt-travel functionality with the BatchPromptSchedule node.
ComfyUI-Advanced-ControlNet for loading files in batches and controlling which latents should be affected by the ControlNet inputs (work in progress, will include more advance workflows + features for AnimateDiff usage later).
ComfyUI-VideoHelperSuite for loading videos, combining images into videos, and doing various image/latent operations like appending, splitting, duplicating, selecting, or counting.
comfyui_controlnet_aux for ControlNet preprocessors not present in vanilla ComfyUI. NOTE: If you previously used comfy_controlnet_preprocessors, you will need to remove comfy_controlnet_preprocessors to avoid possible compatibility issues between the two. Actively maintained by Fannovel16.


