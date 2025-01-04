# Silvertoken Shinobi
Docker container for running shinobi with external mariadb by default.  I use this to build and run shinobi on my raspberry PI kubernetes cluster running on MicroK8s.

# Tags
Shinobi doesn't seem to really maintain version releases and most instructions build from the latest main branch.  This leads to issues when needing to redeploy a specific version of the code.  I solve this by building with a date based tag and pushing a container to Docker hub with that tag. Tags now include short SHA added on to the end making it easier to match a specific shinobi release.

# Links
* [Dockerhub silvertoken/shinobi](https://hub.docker.com/r/silvertoken/shinobi)

# Release updates
| Tag | Description |
| -------- | ------------------------- |
| 20230713 | Updated to alpine 3.18 |
| 20240104 | Updated to node 20, alpine 3.21, accepted SHA tag suffix |
