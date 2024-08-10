# rime-arabic

Rime schemata that support both the Arabic script and the DIN 31635 transcription (with slight alterations as requested by H Zhang's course)

> [!note]
> ## Version 0.2.0 release note
> Version 0.2.0 is the first major update, and listed below are some important changes:
> - **Bug fix:** Words like بَقِيَ (*baqiya*) will no longer be mistakenly transcribed as *baqīa*.
> - **New feature:** It is now possible to enter the Arabic script without any white space followed. As a result, we have made a few mapping changes. See below for more detailed information.
> - **New feature:** Now you can use number keys to enter *tashkīl*. See below for more detailed information.
> - **New feature:** *(arabic_pc only)* We have added the ability to input some variation letters. See below for more detailed information.

## arabic_mac

This variant is based on the Mac Arabic keyboard layout.

Use `1` or `Space` to enter Arabic (the latter will have a white space followed), and `Enter` to enter its transcription.

Use `` Shift+` `` + `(Shift+)[any key]` to substitute for `AltGr+(Shift+)[any key]`.

Listed below are other differences from the original layout:

|                   |    Mac     |   v0.1.0   | v0.2.0</br>*initial* | v0.2.0</br>*non-initial* |                             |
| :---------------: | :--------: | :--------: | :------------------: | :----------------------: | :-------------------------: |
|        `1`        | `U+0661` ١ | `U+0661` ١ |      `U+0661` ١      |          **\***          |             `1`             |
|        `2`        | `U+0662` ٢ | `U+0662` ٢ |      `U+0662` ٢      |        `U+064E` َ        |             `2`             |
|        `3`        | `U+0663` ٣ | `U+0663` ٣ |      `U+0663` ٣      |        `U+064B` ً        |             `3`             |
|        `4`        | `U+0664` ٤ | `U+0664` ٤ |      `U+0664` ٤      |        `U+0650` ِ        |             `4`             |
|        `5`        | `U+0665` ٥ | `U+0665` ٥ |      `U+0665` ٥      |        `U+064D` ٍ        |             `5`             |
|        `6`        | `U+0666` ٦ | `U+0666` ٦ |      `U+0666` ٦      |        `U+064F` ُ        |             `6`             |
|        `7`        | `U+0667` ٧ | `U+0667` ٧ |      `U+0667` ٧      |        `U+064C` ٌ        |             `7`             |
|        `8`        | `U+0668` ٨ | `U+0668` ٨ |      `U+0668` ٨      |        `U+0652` ْ        |             `8`             |
|        `9`        | `U+0669` ٩ | `U+0669` ٩ |      `U+0669` ٩      |        `U+0651` ّ        |             `9`             |
|        `0`        | `U+0660` ٠ | `U+0660` ٠ |      `U+0660` ٠      |        `U+0670` ٰ        |             `0`             |
|     `AltGr+1`     | `U+0638` ظ | `U+0638` ظ |        **†**         |          **†**           |     `` Shift+` `` + `1`     |
| `AltGr+(Shift+)I` |    N/A     | `U+06BE` ھ |      `U+06BE` ھ      |        `U+06BE` ھ        | `` Shift+` `` + `(Shift+)I` |
|  `AltGr+Shift+G`  |    N/A     | `U+0654` ٔ |      `U+0654` ٔ      |        `U+0654` ٔ        |  `` Shift+` `` + `Shift+G`  |
|  `AltGr+Shift+H`  |    N/A     | `U+0655` ٕ |      `U+0655` ٕ      |        `U+0655` ٕ        |  `` Shift+` `` + `Shift+H`  |

> [!tip]
> **\*** Non-initial `1` now acts as a function key. As stated before, you can use it to enter Arabic without any white space followed.
> 
> **†** As the function of `1` has been changed, such input will be processed separately, i.e. you will enter a tilde *~*.

## arabic_pc

This variant is based on the IBM PC Arabic keyboard layout.

Use `0` or `Space` to enter Arabic (the latter will have a white space followed), and `Enter` to enter its transcription.

Use `[any key]` + `\` to enter some variation letters:

|                 |   letter   |
|:---------------:|:----------:|
|    `T` + `\`    | `U+06A4` ڤ |
|    `Y` + `\`    | `U+0671` ٱ |
|    `U` + `\`    | `U+06D5` ە |
|    `I` + `\`    | `U+06BE` ھ |
|    `[` + `\`    | `U+0686` چ |
|    `]` + `\`    | `U+0688` ڈ |
|    `S` + `\`    | `U+06D2` ے |
|    `D` + `\`    | `U+06CC` ی |
|    `F` + `\`    | `U+067E` پ |
|    `H` + `\`    | `U+0670` ٰ |
|    `J` + `\`    | `U+0679` ٹ |
|    `K` + `\`    | `U+06BA` ں |
|    `;` + `\`    | `U+06AF` گ |
|    `'` + `\`    | `U+06A9` ک |
|    `V` + `\`    | `U+0691` ڑ |
|    `.` + `\`    | `U+0698` ژ |
| `Shift+Y` + `\` | `U+0655` ٕ |
| `Shift+H` + `\` | `U+0654` ٔ |
| `Shift+N` + `\` | `U+0653` ٓ |

Listed below are other differences from the original layout:

|           |   IBM PC   |   v0.1.0   | v0.2.0</br>*initial* | v0.2.0</br>*non-initial* |           |
| :-------: | :--------: | :--------: | :------------------: | :----------------------: | :-------: |
|    `1`    | `U+0031` 1 | `U+0661` ١ |      `U+0661` ١      |        `U+0651` ّ        |    `1`    |
|    `2`    | `U+0032` 2 | `U+0662` ٢ |      `U+0662` ٢      |        `U+064E` َ        |    `2`    |
|    `3`    | `U+0033` 3 | `U+0663` ٣ |      `U+0663` ٣      |        `U+064B` ً        |    `3`    |
|    `4`    | `U+0034` 4 | `U+0664` ٤ |      `U+0664` ٤      |        `U+064F` ُ        |    `4`    |
|    `5`    | `U+0035` 5 | `U+0665` ٥ |      `U+0665` ٥      |        `U+064C` ٌ        |    `5`    |
|    `6`    | `U+0036` 6 | `U+0666` ٦ |      `U+0666` ٦      |        `U+0650` ِ        |    `6`    |
|    `7`    | `U+0037` 7 | `U+0667` ٧ |      `U+0667` ٧      |        `U+064D` ٍ        |    `7`    |
|    `8`    | `U+0038` 8 | `U+0668` ٨ |      `U+0668` ٨      |        `U+0670` ٰ        |    `8`    |
|    `9`    | `U+0039` 9 | `U+0669` ٩ |      `U+0669` ٩      |        `U+0652` ْ        |    `9`    |
|    `0`    | `U+0030` 0 | `U+0660` ٠ |      `U+0660` ٠      |          **\***          |    `0`    |
|    `B`    |     لا     | `U+0670` ٰ |          لا          |            لا            |     B     |
| `Shift+T` |     لإ     | `U+0655` ٕ |          لإ          |            لإ            | `Shift+T` |
| `Shift+G` |     لأ     | `U+0654` ٔ |          لأ          |            لأ            | `Shift+G` |
| `Shift+B` |     لآ     | `U+0653` ٓ |          لآ          |            لآ            | `Shift+B` |

> [!tip]
> **\*** Non-initial `0` now acts as a function key. As stated before, you can use it to enter Arabic without any white space followed.
