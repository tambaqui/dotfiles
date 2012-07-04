# tambaqui's dotfiles.. a fork of Paul's..

## Installation

### Using Git and the bootstrap script

```bash
git clone https://github.com/tambaqui/dotfiles.git && cd dotfiles && ./bootstrap.sh
```

### Git-free install

```bash
cd; curl -#L https://github.com/tambaqui/dotfiles/tarball/master | tar -xzv --strip-components 1 --exclude={README.md,bootstrap.sh}
```

To update later on, just run that command again.

### Sensible OS X defaults

When setting up a new Mac, you may want to set some sensible OS X defaults:

```bash
./.osx
```

