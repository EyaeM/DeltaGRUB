# DeltaGRUB

A Deltarune-themed GRUB bootloader theme.

## ORIGIN OF THE PROJECT

Ive always loved Deltarune and for the past few weeks have been searching for a deltarune grub theme, I found an undertale one called [Grubtale](https://github.com/lazypwny751/grubtale) But not a deltarune one.
So I asked in the Arch Linux discord whether there was a GRUB theme for Deltarune out there. They said if you want one, make it yourself. So here we are a complete amateur making a GRUB theme by forking off [MineGrub](https://github.com/Lxtharia/minegrub-world-sel-theme/tree/dev) and modifying it until it is way shitter but Deltarune themed.
(I have no idea what I'm doing so if you wanna help out your welcome to!)

## IMAGES
  ![Main Screen][main]
  ![Terminal][term]
  
  [main]: https://eyae.lol/files/DeltaMain.jpg
  [term]: https://eyae.lol/files/DeltaTerm.jpg

## INSTALLATION

1. **Fork and clone the repository**
```bash
   git clone https://github.com/EyaeM/DeltaGRUB.git
   cd DeltaGRUB
```

2. **Move the theme folder to GRUB themes directory**
```bash
   sudo cp -r DeltaGRUB /boot/grub/themes/
```

3. **Set the theme and resolution in GRUB config**
```bash
   sudo nano /etc/default/grub
```
   Add or modify these lines:
```
   GRUB_THEME="/boot/grub/themes/DeltaGRUB/theme.txt"
```
```
   GRUB_GFXMODE=1366x768
```

4. **Update GRUB**
   
**Arch Linux**
```bash
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

**Ubuntu**
```bash
sudo update-grub
```

5. **YOU NOW HAVE DELTAGRUB**

## CHECKLIST

- [X] Actually start making the thing
- [X] Align the Text
- [ ] Add more text like the time and description
- [X] Make the boxes become green when over them
- [X] Add the SOUL as a selector
      
## CREDITS

* Theme created by Eyae
* Deltarune by Toby Fox
* MineGrub by Lxtharia
* Fonts: Determination (modified for GRUB)
* My shittop Lapis for enduring 100 Reboots

# License
This is a fan-made theme. Deltarune and related assets belong to Toby Fox.
Overall licensed under the MIT license.
