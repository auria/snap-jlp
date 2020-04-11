# snap recipe for jlp

## about the python packages

jlp stands for jenkins-launchpad-plugin. I'm not the maintainer of the original python
packages (jenkins-launchpad-plugin and tarmac). Those can be found on the `source`
described in the `snapcraft.yaml` file.

## Building and Installing

1. get the recipe `git clone https://github.com/auria/snap-jlp`
2. `cd snap-jlp`
3. `snapcraft --use-lxd`
4. `sudo snap install jlp*.snap --dangerous`
