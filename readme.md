# NPM

## Commands

- `npm init [-y]`
  : initialize npm to create a new package [faster]

- `npm i [pkgName[@versionNumber, @latest]] [-g] [--save-dev, --no-save]`
  : install package

  - @versionNumber; @latest
    : specify the version you want to install

  - -g
    : install globally

  - --save-dev
    : save as _devDependency_ = for develompent only

  - --no-save
    : install and try package without saving it

- `npm uninstall [pkgName]`
  : uninstall package

- `npm update [pkgName]`
  : update package

- `npm list [--depth=0]`
  : show dependency tree

  - --depth=0
    : show useful packages only (those listed in _package.json_)

- `npm audit`
  : scan packages for security vulnerabilities

- `npx [pkgName]`
  : instantly run package without installing

- `npm run [customScript]`
  : run custom script

## Files

- _package.json_
  : all the info about your package (name, version, description, dependencies, scripts, etc...)

- _package.lock.json_
  : automatically generated description of the dependency tree
