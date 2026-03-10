# Plymouth Theme のインストール
```bash
git clone https://github.com/BX293APEN/Plymouth-PEN-Theme.git
sudo cp -r Plymouth-PEN-Theme/ /usr/share/plymouth/themes/pen-theme

sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/pen-theme/pen-theme.plymouth 100
sudo update-alternatives --config default.plymouth
sudo update-initramfs -u
sudo update-grub
```