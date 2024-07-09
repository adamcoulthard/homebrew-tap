# Adamcoulthard Tap

## How do I install these casks?

`brew install adamcoulthard/tap/<cask>`

Or `brew tap adamcoulthard/tap` and then `brew install <cask>`.

## Casks
Currently different version of casks for the Galasa Command-Line interface (galasactl).  To install the latest version use the following command

```
brew install --no-quarantine galasactl
```

for a specific version use

```
brew install --no-quarantine galasactl@x.xx.x
```
for example
```
brew install --no-quarantine galasactl@0.33.0
```

At the moment the --no-quarantine is required because otherwise its not possible to run the galasactl. See documentation about this at 
https://galasa.dev.

## Releaseing a new version
When a new version of the galasaclt is released a new galasactl@x.xx.x.rb file needs to be created the following changes are required on the file:

* Update the cask name to being galasactl@x.xx.x
* Update the version variable within the file.
* Update the two sha values.

The galasactl.rb needs to be updated to the latest version as well to allow a user to always install the latest version easily.
