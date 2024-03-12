A provisioning script that is used to perform certain actions when starting a container in [RunPod](https://www.runpod.io/) with the [ai-dock/comfyui](https://github.com/ai-dock/comfyui) template, such as creating directories and downloading files.
It is based on the default script provided by the template, and customized to handle WeSmile's booth pre-event setup requirements.

## Usage
### RunPod
Before creating the container, set the environment variable PROVISIONING_SCRIPT to specify the URL of this script.
```
https://raw.githubusercontent.com/WeSmileBooth/provisioning-script/main/custom.sh
```
### Locally
If you are running locally you may instead opt to mount a script at `/opt/ai-dock/bin/provisioning.sh`.
