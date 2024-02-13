# CTF Template

This project based on [CyberSword](<https://github.com/nkcyber/cybersword>), so that project deployment and managment is uniform across projects.

## Getting Started

> [!IMPORTANT]
> This repo uses [git submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules).
> Remember to clone with `--recursive`:
> ```bash
> git clone git@github.com:nkcyber/YOUR_CTF_NAME.git --recursive
> ```

To get started with this project, install the [CTFd CLI](https://github.com/CTFd/ctfcli) and run `ctf init` to initalze your project information.

See [`administration.md`](./docs/administration.md) for more information.

## About
This project uses the [CTFd CLI](https://github.com/CTFd/ctfcli) for challenge management.

## Service Deployment

Note that [automatic challenge deployment](https://docs.ctfd.io/tutorials/challenges/deploying-challenges/#automatic-challenge-deployment-service) is not available in the free version, which we're using.

As such, we have to take a more involved approach to challenge service deployment.

