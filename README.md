# Docker Collection for Ansible

[![Molecule](https://github.com/bec-galaxy/ansible-collection-docker/actions/workflows/molecule.yml/badge.svg)](https://github.com/bec-galaxy/ansible-collection-docker/actions/workflows/molecule.yml) [![Licence](https://img.shields.io/github/license/bec-galaxy/ansible-collection-docker?label=Licence&color=informational)](https://github.com/bec-galaxy/ansible-collection-docker/blob/main/LICENSE)

A collection to install **Docker** and configuring an **application stack**.

The following steps are supported:

* Distribute a shared `docker-compose.yml` by using the template function.
* Distribute encrypted secrets through an `.env` file.
* Distribute files and folders for a mapped volume.