## Push-to-Deploy Example Using GitHub Actions for DigitalOcean
This repository contains an example workflow using the [GitHub Action for DigitalOcean](https://github.com/digitalocean/action-doctl) to build, tag, push a container image to your DigiatlOcean container registry and deploy to a DigitalOcean Kubernetes cluster.

## Workflow
The [example workflow](https://github.com/digitalocean/sample-push-to-deploy-doks/blob/main/.github/workflows/workflow.yml) triggers on every push to this repo's main branch. For details, see the [Enable Push-to-Deploy](https://www.digitalocean.com/docs/kubernetes/how-to/deploy-using-github-actions/) example.
