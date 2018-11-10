## Installation

To install rbenv-each, clone this repository into your rbenv plugins directory. (You'll need a recent version of rbenv that supports plugin bundles.)


```shell
mkdir -p "$RBENV_ROOT/plugins"
git clone https://github.com/toy/rbenv-whatis.git "$RBENV_ROOT/plugins/whatis"
git clone https://github.com/toy/rbenv-each.git "$RBENV_ROOT/plugins/each"
```

## Usage

```shell
rbenv help each
```

Verbose mode will print a header for each ruby so you can distinguish
the output.

### Examples:

```shell
rbenv each bundle install
rbenv each -v rake test
rbenv each --aliases bundle check
rbenv each -V '2.0 2.1 2.3' ruby -v
```
