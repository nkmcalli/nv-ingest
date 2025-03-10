# Prerequisites for NV-Ingest

Before you begin using NV-Ingest, ensure the following hardware and software prerequisites outlined are met.

## Hardware

| GPU | Family | Memory | # of GPUs (min.) |
| ------ | ------ | ------ | ------ |
| H100 | SXM or PCIe | 80GB | 1 |
| A100 | SXM or PCIe | 80GB | 1 |

## Software

- Linux operating systems (Ubuntu 22.04 or later recommended)
- [Docker](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) (NVIDIA Driver >= `535`, CUDA >= `12.2`)
- [NVIDIA Container Toolkit](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/latest/install-guide.html)


!!! note

    You install Python later. NV-Ingest only supports [Python version 3.10](https://www.python.org/downloads/release/python-3100/).
