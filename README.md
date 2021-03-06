# CXCloud API Accelerator

This repository uses [CXCloud Core Services](https://github.com/cxcloud/core-services) module and shows off it's capabilities. You can use this as a starting point for your CXCloud projects.

## Configuration

This project uses [`node-config`](lorenwest/node-config) for configuration and [`git-crypt`](AGWA/git-crypt) for encryption of configuration files.

To setup `git-crypt` [follow this detailed guide](https://github.com/lorenwest/node-config/wiki/Securing-Production-Config-Files).

## Deploy

This project's master branch is automatically deployed and is available on [https://demo.cxcloud.com/api/](https://demo.cxcloud.com/api/).

## REST API Documentation

If you have run the project with a `NODE_ENV` set to any value other than `production`, a Swagger API Documentation will be available under the `/api/v1/api-docs` URL.

## Copy repository

1. Create clone of this repository and navigate to it:
```sh
$ git clone https://github.com/cxcloud/api-accelerator.git
$ cd api-accelerator
```
2. Remove git tracking and create a new repository:
```sh
$ rm -rf .git
$ git init
```
3. Add and verify a new remote:
```sh
$ git remote add origin https://github.com/*user*/*repo*.git
$ git remote -v
```
4. Push to new remote:
```sh
$ git commit -am "Initial commit"
$ git push --set-upstream origin master [--force]
```

