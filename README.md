# Micro frontend Root

## Prerequisites

Add SSH key your account of github, for more information ckeck [Generating a new SSH key](https://docs.github.com/es/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

## Clone

```shell
git clone --recursive -b main git@github.com:Project-Foundations/pfmf-react-root.git
```

## Install dependencies

```shell
# Install package management
npm i -g pnpm
# Install dependencies of project
pnpm i
```

## Run on develop environment

```shell
pnpm dev
```

## Add submodule

```shell
git submodule add -b main git@github.com:Project-Foundations/pfmf-react-cont.git mfe/pfmf-react-cont
git submodule add -b main git@github.com:Project-Foundations/pfmf-react-prodremo.git mfe/pfmf-react-prodremo
git submodule add -b main git@github.com:Project-Foundations/pf-react-comp.git pf-react-comp
git submodule add -b main git@github.com:Project-Foundations/pf-design-system.git pf-design-system
```