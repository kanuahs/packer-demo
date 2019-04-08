This repo contains a packer template that creates a docker image, a gcloud VM image and an OVA image parallely.

## Build:
Gcloud: Set up gcloud authentication by following the steps listed [here](https://packer.io/docs/builders/googlecompute.html#authentication).
```
packer build ubuntu1804-nginx.json
```
