# Micro frontend Root

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