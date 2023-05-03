# workshop-gitops-content-deploy

This repo is part of the [ArgoCD Managing Infrastructure workshop](https://romerobu.github.io/manual-workshop-infra/manual-workshop-infra/index.html) and is intended to deploy gitops and argo configuration on both hub and managed clusters. 

You will find three branches:

- _setup-sno_: branch with configuration to setup argo hub and destination clusters.
- _main_: main branch to deploy managed clusters configuration. It will be pull and customized by users during the workshop.
- _main-day2_: same branch as main but with an additional application set to deploy day2 operations using ApplicationSet.
