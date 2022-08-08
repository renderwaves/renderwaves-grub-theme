### [GRUB](https://gnu.org/software/grub/)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

    git clone https://github.com/renderwaves/renderwaves-grub-theme.git

#### Activating theme

1. Move the renderwaves-th folder to /boot/grub/themes
2. Change the theme in /etc/default/grub ( Set GRUB_THEME to '/boot/grub/themes/renderwaves-th/theme.txt')
3. Run `sudo grub-mkconfig -o /boot/grub/grub.cfg`
