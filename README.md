## Installation

To install rbenv-each, clone this repository into your rbenv plugins directory. (You'll need a recent version of rbenv that supports plugin bundles.)


```
$ mkdir -p "$(rbenv root)"/plugins
$ git clone https://github.com/toy/rbenv-each.git "$(rbenv root)"/plugins/each
```

## Usage

```
$ rbenv help each
```

Verbose mode will print a header for each ruby so you can distinguish
the output.

### Examples:

```
$ rbenv each bundle install
$ rbenv each -v rake test
$ rbenv each --aliases bundle check
```
