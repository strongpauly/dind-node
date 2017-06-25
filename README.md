# A Versioned Docker-In-Docker Image for Nodejs Builds.

If you find yourself needing an image to lint, test, package your nodejs code, and publish it in a docker,
container, look no further.  These images provide a convenient build image with the following:

- Node [6.9.5](https://github.com/STeveShary/dind-node/blob/master/6/Dockerfile) or [7.2.1](https://github.com/STeveShary/dind-node/blob/master/7/Dockerfile)
- `Docker Engine 17.05`
- `Docker Compose 1.14.0`
- `Git 2.11.2`

Available images:
- `steveshary/dind-node:17.05-6.9.5`
- `steveshary/dind-node:17.05-7.2.1`
