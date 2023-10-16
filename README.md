# argocd-apps-templates

## General recommendations
  - Replace the environment variables (started with _$_) with the desired values before using the apps.
    - Recommended the usage of the [direnv](https://direnv.net/) plugin to automate this process.
    - If this project is used directly on Argo CD will not have the environment variables automatically replaced; it is necessary to manually update the files before adding on it.

## To do's
  [ ] Migrate to Helm so Argo CD be able to replace the environment variables during runtime
