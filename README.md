# Software Engineering Methods

* Master Build Status [![Build Status](https://img.shields.io/github/actions/workflow/status/kaungmyatlwin18/devops/main.yml?branch=master&style=flat-square)](https://github.com/kaungmyatlwin18/devops/actions)
* Develop Build Status [![Build Status](https://img.shields.io/github/actions/workflow/status/kaungmyatlwin18/devops/main.yml?branch=develop&style=flat-square)](https://github.com/kaungmyatlwin18/devops/actions)
* License [![LICENSE](https://img.shields.io/github/license/kaungmyatlwin18/devops.svg?style=flat-square)](https://github.com/kaungmyatlwin18/devops/blob/master/LICENSE)
* Release [![Releases](https://img.shields.io/github/release/kaungmyatlwin18/devops/all.svg?style=flat-square)](https://github.com/kaungmyatlwin18/devops/releases)


## Development & Git Workflow

Our workflow follows these steps:

1. Pull the latest `develop` branch.
2. Start a new feature branch.
3. Once the feature is finished, create the JAR file.
4. Update and test the Docker configuration with GitHub Actions.
5. Update the feature branch with `develop` to ensure the feature is up-to-date.
6. Check that the feature branch still works.
7. Merge the feature branch into `develop`.
8. Repeat steps 2–7 until the release is ready.
9. Merge the `develop` branch into `release` and create the release.
10. Merge `release` into `master` and `develop`.