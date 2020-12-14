# Profile.d

Loads scripts from the `.profile.d` directory.

## Installation

The installation is as simple as including the load script in one's profile file. Likely `.bash_profile`

Simply add:
```bash
[ -f $HOME/.profile.d/load ] && source $HOME/.profile.d/load
```

To enforce that it is loaded, instead add:
```bash
source $HOME/.profile.d/load
```
