# gitconfigs

Add custom git configs for `user` and `email` (see sides.gitconfig) 

## How it works

Checkout the repo to a folder e.g., D:/projects/sides/gitconfigs 

Include the custom gitconfig file in your global ~/.gitconfig like this:

Windows

```ini
[includeIf "gitdir:D:/projects/sides/"]
     path = D:/projects/sides/gitconfigs/sides.gitconfig
```
