## Brief  
This repo contains fine tuning scripts for [Flux](https://github.com/black-forest-labs/flux) which can be run on Amazon Sagemaker.

## How to use  
You don't need to git clone the whole repo, just pick up a notebook which you want to use and download it to your local computer then upload to SageMaker notebook instance and run codes to go.  

## Notes
### Lora fine tuning:  
***flux_lora_training.ipynb*** runs preparation and training on a single Sagemaker notebook (e.g. ml.g5.4xlarge).  

***flux_lora_training_decoupled.ipynb*** runs preparation and training seperately, it leverages Sagemaker training job to run a Lora training job.

