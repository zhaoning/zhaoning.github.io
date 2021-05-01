# My Vim Set-up

## Vim 8 Native Package Manager

Trial not successful. Fell back to `'junegunn/vim-plug'`.

### Where to hold the plug-ins?

Plug-ins are held in `~/.vim/pack/ning/start`, where `ning` can be anything
naming (assuming vim configurations are stored in `~/.vim`). Vim will pick up
any packages added to this folder and automatically load the plug-ins.

Optionally, another folder `opt` can be created to hold packages that are not
loaded automatically. To load packages in this folder, use

```
:packadd package_name
```

### How to manage plug-ins?

Just put the package folder/files under `start` by
- Downloading and extracting
- Cloning a git repo
- ...

### More help

```
:help packages
```

