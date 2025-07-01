## Managing Helm with kubernetes.core.helm Modules
<br/>

### Module Overview

The kubernetes.core collection provides dedicated Helm modules that integrate Helm package management directly into Ansible workflows. The primary modules include kubernetes.core.helm for managing chart installations and releases, and kubernetes.core.helm_repository for repository management. These modules abstract Helm CLI operations into declarative Ansible tasks.
Chart Installation and Management

The helm module handles chart deployments by specifying chart names, versions, and target namespaces. It supports installing charts from configured repositories using chart names, or from local paths and remote URLs. The module manages the complete installation lifecycle including initial deployment, upgrades, and rollbacks based on the desired state you define.

<br/>

## This module is part of the kubernetes.core collection (version 5.3.0).

You might already have this collection installed if you are using the ansible package. It is not included in ansible-core. To check whether it is installed, run ansible-galaxy collection list.

To install it, use: ansible-galaxy collection install kubernetes.core. You need further requirements to be able to use this module, see Requirements for details.

To use it in a playbook, specify: kubernetes.core.helm.

<br/>




## Synopsis
Install, upgrade, delete packages with the Helm package manager.

<br/>

## Requirements

helm (https://github.com/helm/helm/releases)
<br/>
yaml (https://pypi.org/project/PyYAML/)




