# ceph-top-gun-enablement
Ceph Top-Gun Enablement.

## Local build instructions

At Github, the HTML pages are rendered automatically using Github Actions.

To render the HTML pages on a local clone, use

```
podman run -v $PWD:/antora:Z --rm -t docker.io/antora/antora --cache-dir=./.cache/antora antora-playbook-local.yml
```
