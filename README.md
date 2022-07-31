# x-plymouth

## A two-step theme for Plymouth.

<img src="./demo.gif" alt="X Plymouth Theme Demo">

### Installation

```
sudo apt install plymouth-themes
git clone https://github.com/Cronocide/x-plymouth-theme
cd x-plymouth-theme
sudo cp -r x-plymouth /usr/share/plymouth/themes/
sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/x-plymouth/x-plymouth.plymouth 800
sudo update-alternatives --set default.plymouth /usr/share/plymouth/themes/x-plymouth/x-plymouth.plymouth
sudo update-initramfs -u
```

### Customization

The background color can be changed by setting the `BackgroundStartColor` and `BackgroundEndColor` parameters in x-plymouth.plymouth.
