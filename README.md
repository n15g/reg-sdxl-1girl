# Regularization Images - SDXL - `1girl` Class

Stable Diffusion XL training regularization images. Used during LoRA training to reinforce the underlying model and
reduce overfitting.

![Splash](1_1girl/00000-sd_xl_base_1.0-3e3fe5774ff23a0cc24aba5939aa19c9a3d3270125bbaf1c69037cf640abb54f.jpg)

|             |                                                                                                   |
|-------------|---------------------------------------------------------------------------------------------------|
| Model       | [`stable-diffusion-xl-base-1.0`](https://huggingface.co/stabilityai/stable-diffusion-xl-base-1.0) |
| Class Tag   | `1girl`                                                                                           |
| Tags        | Booru - WD1.4 `*.txt`                                                                             |
| Cardinality | 2020 images                                                                                       |
| VAE         | None                                                                                              |
| Sampler     | DDIM                                                                                              |
| Steps       | 20                                                                                                |

Useful if you're using booru-style tags while training against the SDXL base model. While it isn't specialized
on booru-style tagging, it still works effectively.

## Usage

In the Kohya_SS GUI, select this project directory as the `Regularisation folder` during training.

**Note**: Only use these regularization images if training against the `stable-diffusion-xl-base-1.0` model. Training
with regularization images from a different model will heavily bake that style into the result.
