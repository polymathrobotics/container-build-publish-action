# container-build-publish-action
GitHub Action to build and publish container images with Buildx

```
- name: Build and publish container image
  uses: polymathrobotics/container-build-publish-action@main
  with:
    dockerhub-username: ${{ secrets.CONTAINER_REGISTRY_USERNAME }}
    dockerhub-password: ${{ secrets.CONTAINER_REGISTRY_PASSWORD }}
```
