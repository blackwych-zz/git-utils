Git-SSH
=======

SSH config switcher for Git

Installation
------------

Clone this repository (or simply download `git-ssh`) and add this line into your `.profile`:
```Bash
export GIT_SSH=/path/to/git-ssh
```

Usage
-----

Just add settings as git config.

```Bash
# I don't know why, but private keys are not available on ssh-agent
git config gitssh.identity ~/.ssh/id_rsa_xxx.pub
```

Currently supports:

* Identity (`gitssh.identity`).
