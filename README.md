# ZMK config — Boardsource Rechteck (`bs_lp_60`)

Personal fork of [boardsource/Rechtek_zmk_config](https://github.com/boardsource/Rechtek_zmk_config).

- Keymap: `config/bs_lp_60.keymap`
- Board definition (Zephyr HWMv2, ZMK Studio enabled): `boards/boardsource/bs_lp_60/` — from [boardsource/Rechtek-zmk-config#2](https://github.com/boardsource/Rechtek-zmk-config/pull/2), since the upstream board no longer builds on current ZMK.
- Every push builds firmware in **Actions** → download the `firmware` artifact → double-tap reset → drag `.uf2` onto the drive.
- Live remap: https://zmk.studio over USB (unlock with Fn + Backspace).
