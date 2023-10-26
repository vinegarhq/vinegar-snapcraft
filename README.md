# Vinegar Snap package development
Welcome to the Vinegar snap's home! The full source of the snap package is stored here.

[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-black.svg)](https://snapcraft.io/vinegar)

**NOTE:** The snap is currently experimental, and it has devmode confinement on! To install it, follow the instructions below:

## Installing
To install the latest `edge` release, you can simply install it via `snap` using the following command:
```
$ sudo snap install --edge --devmode vinegar
```
After running the above command, the experimental snap package should be installed and ready to go!

## Building
To build it, you'll have to manually build it via `snapcraft` [(instructions to install the snapcraft build tool along with lxd can be found here)](https://snapcraft.io/docs/create-a-new-snap#heading--setup)
```
$ snapcraft
```
After the snap is done building, the newly-created package will be in your working directory and ready to install! To install it and test it, simply run the following commands:
```
$ sudo snap install --devmode ./vinegar_*.snap
$ snap run vinegar player
```
# Bug reporting
If you encounter any bugs at all with the snap as it is right now, please open an issue about it! Your help is appreciated
