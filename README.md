# SG161222/RealVisXL_V2.0 LoRA inference Cog model

This is an implementation of the [SG161222/RealVisXL_V2.0](https://huggingface.co/SG161222/RealVisXL_V2.0) as a Cog model. [Cog packages machine learning models as standard containers.](https://github.com/replicate/cog)

First, download the pre-trained weights:

    cog run script/download-weights

Then, you can run predictions:

    cog predict -i lora_url="https://replicate.delivery/pbxt/u9MoIWBBRL44KJ1HstsdBNVwQJ1BR3BTeeFvbfHXuMkUu1sjA/trained_model.tar" -i prompt="a photo of TOK"

## Example:

"a photo of TOK"

![alt text](output.0.png)