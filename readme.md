# realworld-front-angular-deploy

Simple deployment project for realworld-front-angular project.

## To run
```sh
# validate overlay
$ kustomize build overlays/pipeline
# deploy
kubectl apply -k  overlays/pipeline
```
