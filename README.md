# pacman-timers

Some useful systemd timers for Pacman.

## clean-pacman-cache

Clears the pacman cache for packages that are not installed.

Runs every week when enabled.

## update-packages

Updates all packages installed with pacman.

Runs every week day at 4am when enabled.

Does not run on weekends to decrease likelihood of bad updates being installed.
