# AppImageManager
**Install and remove AppImages easily**

Core code taken from [Boga's AppImageMan](https://github.com/miguelrcborges/AppImageMan), with a lot of generalization, help texts and error catching added.

# Features

- Quickly install .appimage files by creating .desktop files in your user application folder.
- List AppImages currently installed 
- Easily remove the desktop files associated with AppImages from your application folder, optionally removing the AppImage itself
- Rename the script to anything you want - functions adjust accordingly
- Update checking and downloading

# Installing and Updating

```bash
sudo curl -o /usr/bin/aim -L https://raw.githubusercontent.com/justrainer/AppImageManager/main/aim
```

# Uninstalling

```bash
sudo rm /usr/bin/aim
```
