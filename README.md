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

-   Prompt user to install quickemu dependencies (if not already installed)
-   TBD