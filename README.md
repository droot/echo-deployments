# echo-deployments
Deployment Repo for echo apps

# Steps to add new variants

```sh

kpt pkg get git@github.com:droot/kpt-packages.git/echo@main dev --for-deployment

kpt fn render dev
```
