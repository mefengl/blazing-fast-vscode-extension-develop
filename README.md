# blazing-fast-vscode-extension-develop

it's not in detail, just a simple demo, if anyone want to know more, please create an issue.

## Prepare

use `ppm` to install:

```bash
packages=(
    # vscode
    "yo"
    "generator-code"
    "vsce"
)
```

## Create

```bash
yo code
```

> use `npm` to manage the dependencies when creating the project, since I found there are some problem with `pnpm` when run `vsce package` later.

look at the `vsc-extension-quickstart.md` under the project just created.

## Develop

tell ChatGPT what you want to do

## Package

Package for own use

```bash
vsce package
```

## Publish

to be continue
