# Docker registry

This docker-compose creates a docker registry. It can be used to push and pull custom images.

The registry will be available at http://localhost:5000

It embeds also a registry UI that can be reached at http://localhost:3000

When using on a remote server, you have to change the `REGISTRY_DOMAIN` to the host name (ie. "my-registry.com").
Various explanations on how pushing or pulling images can be found in the UI application. 
 