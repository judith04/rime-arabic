# rime-arabic

Rime schemata that support both Arabic and DIN 31635 transcription

## Usage

Use `Space` to enter Arabic (with a white space automatically added after), and `Enter` to enter its transcription.

The transcription is based on DIN 31635, with slight alterations as requested by H Zhang's course.

## Layout

Two variants (`arabic_pc`, `arabic_mac`) are provided, based on the Arabic keyboard layouts of IBM PC and Mac respectively.

Use `~` + `(Shift+)[any key]` to substitute for `AltGr+(Shift+)[any key]` in `arabic_mac`.

Other differences from the original layouts are listed below:

|            | `arabic_pc`          | `arabic_mac`                         |
|:---------- |:-------------------- |:------------------------------------ |
| لا         | *Removed:* `B`       |                                      |
| لإ         | *Removed:* `Shift+T` |                                      |
| لأ         | *Removed:* `Shift+G` |                                      |
| لآ         | *Removed:* `Shift+B` |                                      |
| `U+0670` ٰ | *Added:* `B`         |                                      |
| `U+0655` ٕ | *Added:* `Shift+T`   | *Added:* `` Shift+` `` + `Shift+H`   |
| `U+0654` ٔ | *Added:* `Shift+G`   | *Added:* `` Shift+` `` + `Shift+G`   |
| `U+0653` ٓ | *Added:* `Shift+B`   |                                      |
| `U+06BE` ھ | *N/A*                | *Added:* `` Shift+` `` + `(Shift+)I` |
