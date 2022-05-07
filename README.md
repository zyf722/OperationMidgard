# Operation Miðgarðr

The **Operation Miðgarðr** is a fan-made Steins;Gate 0 **character sprite overhaul project**, intended to replace new character sprites with original ones from Steins;Gate.

![Preview 1](https://s2.loli.net/2022/05/07/rlSq1Vz9MXdTRxu.jpg)

![Preview 2](https://s2.loli.net/2022/05/07/wEKJzqayPlNx6fj.jpg)

## Status

This project is still at a fairly early development stage, with the latest patched script `SG0_01_05.scx`.

Currently planned characters includes _Kurisu_, _Suzuha_ and _Daru_.

## How It Works

### Character Sprite Replacement

Given that Steins;Gate 0 has already contains all those original sprites from Steins;Gate, we simply replace those new sprites with old ones by renaming at first. For example, as for Kurisu, we replace one of the new sprites, `CRS_JLD.png` and `CRS_JLD_.lay`, with an old sprite `CRS_ALA.png` and a corresponding .lay file .

![](https://s2.loli.net/2022/05/07/pYmUWed7l35zLs9.png)

### Expression Error Patch

However, due to the difference in the number of expressions in new and old sprites, some displaying error might occur, such as missing faces or wrong expressions. We fix these errors by editing sprite commands in .scx scripts.

## Credits

Thanks to those outstanding works:

- [SGOMPK](https://github.com/mrboms/SGOMPK): an unpacker & repacker for .mpk datapacks, which we use for extracting character sprites and scripts.
- [sc3ntist](https://github.com/CommitteeOfZero/sc3ntist): a disassembler for .scx scripts, which greatly helps us to locate sprite-related commands and fix those face-expression displaying errors

## License
[The MIT License](https://github.com/zyf722/OperationMidgard/blob/main/LICENSE)
