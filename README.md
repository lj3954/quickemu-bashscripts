## Bash scripts to make Quickemu simpler to use.

-   Simple creation/launch of VMs
-   No need to worry about directories
-   Automatically prompts for the amount of RAM, disk space, CPU cores.

## Installation (and updating) instructions
```bash
curl https://raw.githubusercontent.com/lj3954/quickemu-bashscripts/main/quickemu-create > ~/.local/bin/quickemu-create && chmod a+x ~/.local/bin/quickemu-create
curl https://raw.githubusercontent.com/lj3954/quickemu-bashscripts/main/quickemu-launch > ~/.local/bin/quickemu-launch && chmod a+x ~/.local/bin/quickemu-launch
curl https://raw.githubusercontent.com/lj3954/quickemu-bashscripts/main/quickemu-delete > ~/.local/bin/quickemu-delete && chmod a+x ~/.local/bin/quickemu-delete
```

## Features for the future

-   TBD

## Configuration

quickemu-create will check what operating systems are available without waiting for git pull to complete (which will update quickemu if it's not already up to date). This will result in the script loading much faster, but may result in instabililty on slower internet connections. This can be overridden by creating a file at ~/.config/quickemu-bashscripts/quickemu-create.conf and setting WaitForUpdate to true. You can also block the script from automatically updating quickemu by setting SkipUpdate to true.