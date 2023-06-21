# OpenShift Equinix Execution Environment

Ansible Execution Environment containing assets to deploy and install OpenShift to Equinix. The primary content that is contained within this Execution Environment is the Ansible Content Collections [openshift_equinix](https://github.com/sabre1041/openshift_equinix) for deploying and installing OpenShift to Equinix.

## Building the Execution Environment

Using [Ansible Navigator](https://ansible.readthedocs.io/projects/navigator/), execute the following command to build the Execution Environment from the root of the repository:

```shell
ansible-navigator builder build -t openshift_equinix-ee
```

## Exploring the Execution Environment

Ansible Navigator can be used to explore the Execution Environment created previously. Execute the following command to navigate the contents of the Execution Environment

```shell
ansible-navigator collections --pp=missing --eei=localhost/openshift_equinix-ee
```
