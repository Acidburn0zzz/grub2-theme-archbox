# Default GRUB2 theme for [ArchBox](http://archbox-linux.github.io/)

## Installation

1. Clone this [repo](https://github.com/archbox-linux/grub2-theme-archbox.git)
   ```
   git clone https://github.com/archbox-linux/grub2-theme-archbox.git
   ```

2. Put the folder 'archbox' wherever you want

3. Add following line to **/etc/default/grub** (replacing *\<your-path\>*): 
   ```bash
   GRUB_THEME="<your-path>/archbox/theme.txt"
   ```

4. Regenerate grub config:
   ```
   grub-mkconfig -o /boot/grub/grub.cfg
   ```

5. Reboot to check newly installed theme
