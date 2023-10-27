# AWX EE

Modified from the default Execution Environment for AWX:
https://github.com/ansible/awx-ee

This Execution Environment for AWX comes with ibm.power_aix and ibm.power_ibmi collections.

## Build the image locally

First, [install ansible-builder](https://ansible-builder.readthedocs.io/en/stable/installation/).

Then run the following command from the root of this repo:

```bash
$ ansible-builder build -v3 -t quay.io/ansible/awx-ee # --container-runtime=docker # Is podman by default
```
