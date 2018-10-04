# mac-ruby-rails-setup

* This guide assumes you are already using [Homebrew](https://brew.sh/)


## Install a Ruby Version Manager.  I recommend rbenv.
```sh
$ brew update
$ brew install rbenv ruby-build
```

*Additionally, you can install `$ rbenv-gem-rehash` which automatically hashes new gems when they are installed.*

## Initialize rbenv in your shell
```sh
$ rbenv init
```

*Close your terminal window and open a new one for changes to take effect*

## Test your rbenv installation
```sh
$ curl -fsSL https://github.com/rbenv/rbenv-installer/raw/master/bin/rbenv-doctor | bash
```

## Download Ruby version
```sh
$ rbenv install [version-goes-here]
```
*Example: `$ rbenv install 2.4.4`*

## Set Ruby version for different environments
### Local (version for specific directory)
```sh
$ rbenv local [version-goes-here]
```

### Global (global default version - can be overriden)
```sh
$ rbenv local [version-goes-here]
```

### Which version is installed here?
```sh
$ rbenv version
```

### What versions are available on my system?
```sh
$ rbenv versions
```
