# Adamcoulthard Tap

## How do I install these formulae?

`brew install adamcoulthard/tap/<formula>`

Or `brew tap adamcoulthard/tap` and then `brew install <formula>`.

Or, in a [`brew bundle`](https://github.com/Homebrew/homebrew-bundle) `Brewfile`:

```ruby
tap "adamcoulthard/tap"
brew "<formula>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).

## Casks
Currently only contains one cask for the Galasa Command-Line interface (galasactl).  To install use the following command

```
brew install --no-quarantine galasactl
```

At the moment the --no-quarantine is required because otherwise its not possible to run the galasactl. See documentation about this at 
https://galasa.dev.
