# grub-eighties

Simple grey-ish GRUB theme that is based on "starfield" theme by Daniel Tschudi.

License is `CC-BY-SA 3.0`

## Usage

1. Edit your GRUB config
    ```
    sudo $EDITOR /etc/default/grub
    ```
    Edit line that says `set theme=($root)/path/to/theme.txt` and save.

2. Re-generate your config
    ```bash
    sudo grub-mkconfig > /boot/grub/grub.cfg
    ```
