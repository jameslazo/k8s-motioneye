# CHANGELOG


## v0.3.0 (2025-04-13)

### Features

- Pv/pvc for motioneye app
  ([`44199c5`](https://github.com/jameslazo/k8s-motioneye/commit/44199c52fc322e12211b93ca27e2665d2ce7f745))


## v0.2.0 (2025-02-26)


## v0.1.0 (2025-02-26)

### Chores

- Whitelist y*ml
  ([`e012fce`](https://github.com/jameslazo/k8s-motioneye/commit/e012fce88642b12b9ddd2f3bf6da111e7e433ee9))

### Features

- Configmap
  ([`ef20a02`](https://github.com/jameslazo/k8s-motioneye/commit/ef20a02b03c739d325804f7cc310cdc697db0d8e))

ConfigMap adds custom entrypoint.sh when building new docker image from motioneye repository. Hotfix
  for permission issues with motion user and securityContext preventing execution of su command

- Motioneye deployment
  ([`8be4025`](https://github.com/jameslazo/k8s-motioneye/commit/8be402557fa931c53997bbb3a4c0f2c806f938a6))

- Motioneye service
  ([`c9b66f5`](https://github.com/jameslazo/k8s-motioneye/commit/c9b66f5c4787a38f90eb759aa08b8b50aea772d2))

- Namespace
  ([`8c60dd7`](https://github.com/jameslazo/k8s-motioneye/commit/8c60dd746d67b728a426696e93990228b6421744))

- Repo template
  ([`e109c0b`](https://github.com/jameslazo/k8s-motioneye/commit/e109c0b8db3798b9f2594c05b533d907395094ce))
