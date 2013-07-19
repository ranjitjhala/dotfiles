##Includes configuration files for:
Vim, Bash, Zsh, Screen

##To install:
```
$ sh ./bootstrap.sh
```
To exclude files from being istalled add an `--exclude "<file>"` in bootstrap.sh.

## Vim 
Plugins are handled with *Vundle*:

To add a new plugin just add the github path in the Vundle section of .vimrc

To install the plugins run: `BundleInstall`

To clean after removing a plugin: `BundleClean`

For tag support you are going to need Exuberant tags (`ctags`).

The haskell plugins will need `hdevtools` and `ghc_mod` installed. Also make sure vim is run in `hsenv`.

Tags for haskell require the `lushtags` package installed.
