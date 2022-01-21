# Cthulhu Plymouth Theme

Iä! Iä! Cthulhu fhtagn! Ph'nglui mglw'nfah Cthulhu R'lyeh wgah'nagl fhtagn!

**Test**
`sudo plymouth-set-default-theme [name]`

**Build**
`sudo mkinitcpio --generate /boot/initramfs-linux-lts.img`
`sudo grub-mkconfig -o /boot/grub/grub.cfg`

**Debug**
```sudo plymouthd --debug --debug-file=/tmp/plymouth-debug-out ; sudo plymouth --show-splash ; for ((I=0;I<10;I++)); do sleep 1 ; sudo plymouth --update=event$I ; done ; sudo plymouth --quit```

**Sources:**
 - Background; taken from here https://wallpapersafari.com/w/xSkyAv 
 - Lock; edited from here https://www.virtualgrub.com/razer-kraken-forged-edition/
 - Bullet Font; edited from here https://propnomicon.blogspot.com/2014/06/necrofonticon.html

**References**
  - https://github.com/adi1090x/plymouth-themes/
  - https://linuxconfig.org/how-to-build-an-initramfs-using-dracut-on-linux