# Eazy Git [![EazyGit Version](https://img.shields.io/badge/version-0.7-blue)](https://github.com/ZechBron)

Upload a file in your repo using terminal without typing long commands.

## Installation:

__Requirements__

```
Ubuntu

 apt-get install git -y

Termux:

 pkg install git -y
```

> git clone https://github.com/ZechBron/EazyGit

> cd EazyGit

> chmod +x *

> ./setup

## How to use:
__Setup user__

> eazygit -n github-username -e email-addrs


__Upload file with commit message__

> eazygit -c filename -h commit-message -b github-repo-url

__Upload file with default commit__

> eazygit -c filename -z -b github-repo-url

---

If you encounter an error, problems or bugs.
There are two things you can do:
- Email me here zech@mbox.re

- Or submit an issue here

![Issues](https://github.com/ZechBron/EazyGit/issues/new)
