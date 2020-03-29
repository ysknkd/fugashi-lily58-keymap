
## Description

My Lily58 keymap

## Development

Please setup for QMK environment.

* [Setting Up Your QMK Environment](https://docs.qmk.fm/#/newbs_getting_started)

```console
$ git clone https://github.com/qmk/qmk_firmware
$ cd qmk_firmware
$ ./util/new_keymap.sh lily58 fugashi
$ cp path/to/fugashi-lily58-keymaps/keymap.c ./keyboards/lily58/keymap/fugashi/
$ cp path/to/fugashi-lily58-keymaps/rules.mk ./keyboards/lily57/keymap/fugashi/
```

```console
$ make lily58:fugashi
```

