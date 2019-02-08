
# What is Kubectl?

> Kubectl is the Kubernetes command line interface.

[Overview of kubectl](https://kubernetes.io/docs/reference/kubectl/overview/)

# TL;DR;

```bash
$ docker run --name kubectl bitnami/kubectl:latest
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on [minideb](https://github.com/bitnami/minideb) a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* Bitnami container images are released daily with the latest distribution packages available.


> This [CVE scan report](https://quay.io/repository/bitnami/kubectl?tab=tags) contains a security report with all open CVEs. To get the list of actionable security issues, find the "latest" tag, click the vulnerability report link under the corresponding "Security scan" field and then select the "Only show fixable" filter on the next page.

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`1.13-rhel-7`, `1.13.3-rhel-7-r7` (1.13/rhel-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.13.3-rhel-7-r7/1.13/rhel-7/Dockerfile)
* [`1.13-ol-7`, `1.13.3-ol-7-r7` (1.13/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.13.3-ol-7-r7/1.13/ol-7/Dockerfile)
* [`1.13-debian-9`, `1.13.3-debian-9-r5`, `1.13`, `1.13.3`, `1.13.3-r5`, `latest` (1.13/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.13.3-debian-9-r5/1.13/debian-9/Dockerfile)
* [`1.12-ol-7`, `1.12.5-ol-7-r19` (1.12/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.12.5-ol-7-r19/1.12/ol-7/Dockerfile)
* [`1.12-debian-9`, `1.12.5-debian-9-r17`, `1.12`, `1.12.5`, `1.12.5-r17` (1.12/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.12.5-debian-9-r17/1.12/debian-9/Dockerfile)
* [`1.11-ol-7`, `1.11.7-ol-7-r12` (1.11/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.11.7-ol-7-r12/1.11/ol-7/Dockerfile)
* [`1.11-debian-9`, `1.11.7-debian-9-r10`, `1.11`, `1.11.7`, `1.11.7-r10` (1.11/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.11.7-debian-9-r10/1.11/debian-9/Dockerfile)
* [`1.10-ol-7`, `1.10.12-ol-7-r45` (1.10/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.10.12-ol-7-r45/1.10/ol-7/Dockerfile)
* [`1.10-debian-9`, `1.10.12-debian-9-r45`, `1.10`, `1.10.12`, `1.10.12-r45` (1.10/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.10.12-debian-9-r45/1.10/debian-9/Dockerfile)
* [`1.10.9-ol-7`, `1.10.9-ol-7-r13` (1.10.9/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.10.9-ol-7-r13/1.10.9/ol-7/Dockerfile)
* [`1.10.9-debian-9`, `1.10.9-debian-9-r11`, `1.10.9`, `1.10.9-r11` (1.10.9/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.10.9-debian-9-r11/1.10.9/debian-9/Dockerfile)
* [`1.9-ol-7`, `1.9.11-ol-7-r45` (1.9/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.9.11-ol-7-r45/1.9/ol-7/Dockerfile)
* [`1.9-debian-9`, `1.9.11-debian-9-r45`, `1.9`, `1.9.11`, `1.9.11-r45` (1.9/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-kubectl/blob/1.9.11-debian-9-r45/1.9/debian-9/Dockerfile)

Subscribe to project updates by watching the [bitnami/kubectl GitHub repo](https://github.com/bitnami/bitnami-docker-kubectl).

# Get this image

The recommended way to get the Bitnami Kubectl Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/bitnami/kubectl).

```bash
$ docker pull bitnami/kubectl:latest
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/bitnami/kubectl/tags/) in the Docker Hub Registry.

```bash
$ docker pull bitnami/kubectl:[TAG]
```

If you wish, you can also build the image yourself.

```bash
$ docker build -t bitnami/kubectl:latest https://github.com/bitnami/bitnami-docker-kubectl.git
```

# Configuration

## Running commands

To run commands inside this container you can use `docker run`, for example to execute `kubectl --version` you can follow the example below:

```bash
$ docker run --rm --name kubectl bitnami/kubectl:latest -- --version
```

Consult the [Kubectl Reference Documentation](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands) to find the completed list of commands available.

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-kubectl/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-kubectl/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-kubectl/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright 2019 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
