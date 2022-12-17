# AppImageManager
**Install and remove AppImages easily**

Core code taken from [Borga's AppImageMan](https://github.com/miguelrcborges/AppImageMan), with a lot of generalization, help texts and error catching added.

# Features

- Quickly install .appimage files by creating .desktop files in your user application folder.
- List AppImages currently installed 
- Easily remove the desktop files associated with AppImages from your application folder, optionally removing the AppImage itself

# Installing and Updating

```bash
git clone https://github.com/RainerZufahl/AppImageManager
sudo mv AppImageManager/aim /usr/bin/
rm -rf AppImageMan
```

# Uninstalling

```bash
sudo rm /usr/bin/aim
```