# MAU7200EA 02.02.0154

Built on 2026-09-02 from `a14_aml_lgup_mau7200ea_dev`.

## Assets
- `mau7200ea_userdebug_02.02.0154_usb_secure.img.7z` (1.8G)
- `mau7200ea_userdebug_02.02.0154_update_secure.zip` (1.8G)

## Unpacking the .7z

Windows: install 7-Zip, then right-click the `.7z` and Extract Here.
(Split sets: download every `.7z.001`, `.7z.002` ... and extract the `.001`.)

Linux: `7z x <file>.7z`

`sha256sums.txt` lists both the extracted image and the archive.

## Flashing

- `*_usb_secure.img` - secure ADNL burn (device USB password required)
- `*_update_secure.zip` - `adb sideload`

