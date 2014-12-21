# grub-eighties

Simple grey-ish GRUB theme that is based on "starfield" theme by Daniel Tschudi.

License is `CC-BY-SA 3.0`

## Usage

1. Edit your GRUB config, as rot
    ```
    $EDITOR /etc/default/grub
    ```
    Edit line that says `GRUB_THEME="/home/user/repos/grub-eighties/theme.txt"` and save.

2. Re-generate your config, as rot
    ```bash
    grub-mkconfig > /boot/grub/grub.cfg
    ```
