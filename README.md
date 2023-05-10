# vertex-ai-stable-diffusion
### Script for Deploying HuggingFace Stable Diffusion on Vertex AI

# Requirements:
- docker
- torch
- torchserve
- google-cloud
- huggingface/diffusers

# Project Files:

| **Files                 | **Purpose                          |
|------------------------------|--------------------------------------------|
| `utility_notebook.ipynb` | Walk through of testing process |
| `Deploy.sh`                   | Deploys on Google Cloud |
| `Dockerfile`           |  Contains Build info, for both local testing and google cloud        |
| `config.properties`     |   Properties of ports to expose |
| `requirementss.txt`     |   Requirments for Docke build |
| `cloudbuild.yaml`     |  Goolge cloud specific yaml |
| `vertex_test/stable_diffusion_handler.py`     |  torchserve  stuff |
| `vertex_test/external_files/connfig.py`     |  Config for Bucket Names |
| `vertex_test/external_files/handler_utils.py`     | Utils for saving to bucket |


# Usage:

- Replace your own information
- Test using utility_notbook
- Deploy using deploy.sh

