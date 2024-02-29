# test-renovate

[//]: # (This is a comment.)

> [!NOTE]
> UDS K3d intentionally does not address airgap concerns for K3d or the load balancer logic deployed in this package. This allows running `zarf init` or deploying a Zarf Init Package via a UDS Bundle after the UDS K3d environment is deployed.

## Prerequisites

- [Zarf](https://docs.zarf.dev/docs/getting-started#installing-zarf) version: 0.31.0
- [K3d](https://k3d.io/#installation) version: 5.4.6
- [Docker](https://docs.docker.com/get-docker/) or [Podman](https://podman.io/getting-started/installation) for running K3d
