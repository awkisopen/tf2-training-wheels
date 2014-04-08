# TF2 Training Wheels
Welcome to **Training Wheels**, an easy way for new and experienced players alike to have fun and experiment together using the popular training map `tr_walkway_rc2`.

## Installation
*Disclaimer: The commands given in these directions are for Linux servers. However, the configuration files in this repository should work on other platforms as well.*

First, follow the [Linux dedicated server instructions](http://wiki.teamfortress.com/wiki/Linux_dedicated_server) on the official TF2 wiki. At the final step detailing the command-line arguments for `srcds_run`, replace `+map ctf_2fort.bsp` with `+map tr_walkway_rc2.bsp`.

Navigate to the `tf` directory in the place you installed the server files, for example `/home/gameserver/tf2/tf/`. Run the following command to install Training Wheels:

    git init && git remote add github https://github.com/awkisopen/tf2-training-wheels.git && git fetch github && git reset --hard FETCH_HEAD

This will pull the configuration files, map, and anti-cheat plugin from this repository to your server. If the command fails because you do not have git installed, install the `git` package from your system's package manager (for example, `apt-get install git` would install git on Ubuntu or other Debian-based servers).
