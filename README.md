# zmk-config

My split keyboards.

| Keyboard | Layout | Keys (Size) |
| -------- | ------ | ----------- |
| sofle    | 6x4+5  | 58 (60%)    |
| corne    | 6x3+3  | 42 (40%)    |
| sweep    | 5x3+2  | 34 (30%)    |

![My split keyboards](./img/my_keyboards.png)

The bat keyboard is a variant of [cocot46plus](https://github.com/aki27kbd/cocot46plus).

## My Corne Layout

Layer 0 --- Base (Default Layer)

![Layer 0](./img/layer0-base.png)

Layer 1 --- Function & Navigation

![Layer 1](./img/layer1-fn-nav.png)

Layer 2 --- Numbers & Symbols

![Layer 2](./img/layer2-num-sym.png)

Layer 3 --- Bluetooth & Number Pad

![Layer 3](./img/layer3-bt-num.png)

## Hold-Tap

For a 6x3 corne, if you don't want too many hold-tap keys, only one hold-tap
needs to be set, for example, Ctrl/Esc on the first column of left hand. For a
5x3 sweep, many more hold-taps are used (homerow mods + layer-tap on thumb keys).
I use almost the same keymaps for all my keyboards.

> The idea of hold-tap behavior and homerow mods is awesome, but in
> practice, it requires finicky timing. Check
> [urob](https://github.com/urob/zmk-config) for timeless homerow mods.
> BTW, I prefer ACGS as homerow (MacOS + shortcuts), but YMMV.

| Hold   | Tap  |
| ------ | ---- |
| LCtrl  | Esc  |
| LAlt   | A    |
| LCtrl  | S    |
| LGui   | D    |
| LShift | F    |
| RShift | J    |
| RGui   | K    |
| RCtrl  | L    |
| RAlt   | ;    |
| LGui   | Esc  |
| MO1    | Tab  |
| MO2    | BSPC |
| LAlt   | DEL  |

## Macros & Combos

Zmk use key positions for combos, the 36 key matirx is defined as
![36 key matrix](./img/keypos_36keys.png)

| Macros | Definition           |
| ------ | -------------------- |
| email  | `yshenfab@gmail.com` |
| todo   | - [ ]                |
| mobile | my number            |

I didn't put my number in this repo, if you have any private info, just build the
firmware locally.

| Combos | Output  | qwerty keys |
| ------ | ------- | ----------- |
| 0 1    | Esc     | qw          |
| 3 4    | (       | rt          |
| 5 6    | )       | yu          |
| 13 14  | {       | fg          |
| 15 16  | }       | hj          |
| 23 24  | [       | vb          |
| 25 26  | ]       | nm          |
| 20 21  | `       | zx          |
| 21 22  | -       | xc          |
| 22 23  | \_      | cv          |
| 26 27  | =       | m,          |
| 27 28  | +       | ,.          |
| 28 29  | ~       | ./          |
| 10 11  | C-SPC   | as          |
| 11 12  | C-S-Tab | sd          |
| 12 13  | C-Tab   | df          |
| 2 26   | email   | em          |
| 14 15  | todo    | gh          |
| 26 8   | mobile  | mo          |

## Resources

- [My Sweep Config](https://github.com/yshenfab/zmk-sweep)
- [ZMK Docs](https://zmk.dev/docs)
- [urob](https://github.com/urob/zmk-config) -- Timeless homerow mods
- [Miryoku ZMK](https://github.com/manna-harbour/miryoku_zmk) -- 5x3+3, 36 keys
- [Keymap Editor](https://nickcoutsos.github.io/keymap-editor/)
