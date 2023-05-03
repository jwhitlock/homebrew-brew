# Homebrew formula

These are personal formulas for [Homebrew](https://brew.sh/).

## virtualfish

[virtualfish][virtualfish] is a Python virtual environment manager for the
[fish][fish] shell.

[virtualfish]: https://virtualfish.readthedocs.io/en/latest/index.html
[fish]: https://fishshell.com/

To install:

```sh
brew install jwhitlock/brew/virtualfish
vf init compat_aliases auto_activation projects
```

Things I'm thinking about before submitting upstream:

* Should the install call `vf init`? Or should it create `.config/fish/conf.d/virtualfish-loader`?
  - How should the user's chosen plugins be handled?
* Should the prompt function be altered?
