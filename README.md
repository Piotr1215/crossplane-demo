# Crossplane POC

## Introduction Presentation

[Crossplane Slides](https://slides.com/decoder/crossplane)

## Demo Scenario

The demo scenario highlights Crossplane's composite functionality. Using composites helps abstract away infrastructure complexity from developers by moving it into a Platform Team.

The scenario flow:

- install crossplane on a local cluster :white_check_mark:
- deploy AWS and Azure providers
- expose composites to the developers
- developers deploy and manage the life-cycle of dev/test clusters in AZURE and AWS
- manage composites lifecycle

### Demo Setup

All components from the [crossplane installation](https://crossplane.io/docs/v1.5/getting-started/install-configure.html#install-crossplane) are already pre-installed in the devcontainer in this project.

The components are:
- Kubernetes minikube
- Helm
- kubectl
- Crossplane CLI
- AWS CLI
- Azure CLI

> Crossplane should be installed in a *crossplane-system* namespace, if not please run `.devcontainer/library-scripts/setup-crossplane.sh`

## Conclusion

## TODO

- [ ] Should be moved to Infrastructure sub group once it's created.
