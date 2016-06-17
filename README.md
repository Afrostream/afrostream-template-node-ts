# Description

Template of nodejs module build with typescript

# Usage : Create a new nodejs module

create your project directory

```sh
mkdir YourProject
cd YourProject
```

clone this project inside this directory & remove .git data.

```sh
git clone git@github.com:Afrostream/afrostream-template-node-ts.git
rm -rf .git
```

initalized your git
```sh
git init
```

edit the package.json file (project name/description/...)

# Usage : Typescript usage inside the module

first, we need to install typescript

```sh
npm install
```

## Compile src/* => dist/

```sh
npm run compile
```

## Clean dist/*

```sh
npm run clean
```

## Compile & watch files

```sh
npm run compile:watch
```

## Run dist/javascript code

```sh
npm run dev
```

## Lint your code

```sh
npm run lint
```

## Publish your module

```
npm publish
git commit -a -m "w00t"
# modify your package.json to bump the version v1.2.3
git commit -a -m "chore: bump to v1.2.3"
git push origin master
```

# [FIXME]: Yeoman

This template should be converted to a yeoman generator.
