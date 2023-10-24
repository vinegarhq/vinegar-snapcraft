# Vinegar Snap package development
Welcome to the Vinegar snap's home! The full source of the snap package is stored here.

**NOTE:** The snap is currently experimental, and it has devmode confinement on! You can give it a try by following the instructions:

To build it, you'll have to manually build it via `snapcraft` [(instructions to install the snapcraft build tool along with lxd can be found here)](https://snapcraft.io/docs/create-a-new-snap#heading--setup)
```
$ snapcraft
```
After the building is done, there should now be a snap package of Vinegar in your working directory! To install it and test it, simply run the following commands:
```
$ sudo snap install --devmode ./vinegar_*.snap
$ snap run vinegar player
```
# Bug reporting
If you encounter any bugs at all with the snap as it is right now, please open an issue about it! Your help is appreciated