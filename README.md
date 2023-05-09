# Finner
Finner is designed to be an enhanced Finnish keyboard layout. The keylayout was designed to be very easy to learn and it keeps changes to the standard Finnish layout as minimal as possible, while providing much better usability.

**Basic layers of the keylayout, with changes compared to the standard Finnish layout highlighted**
![Image of layout](https://raw.githubusercontent.com/ruohola/finner/master/finner.png)

The repository contains both the macOS `.keylayout` file and Windows `.klc` file.

## macOS installation

1. Move or symlink `Finner.keylayout` into `/Library/Keyboard Layouts/`
2. Restart your computer, logging out is not enough
3. Select the new keyboard layout from System Settings

## Windows installation

1. Download [Microsoft Keyboard Layout Creator](https://www.microsoft.com/en-us/download/details.aspx?id=102134) and open it
2. From 'Open' > open the `Finner.klc` file
3. From 'Project' > select 'Build DLL and Setup package'
4. Run the `setup.exe` file from the location it got created to
5. Select the new keyboard layout from Windows Settings

## All symbols from all layers

### No modifiers

```
`1234567890+\
qwertyuiop[]
asdfghjklöä'
<zxcvbnm,.-
```
(Pressing space types ` `, the normal `U+0020 SPACE (SP)` character)

### Shift

```
~!"#^%&/()=?|
QWERTYUIOP{}
ASDFGHJKLÖÄ*
>ZXCVBNM;:_
```
(Pressing space types ` `, the normal `U+0020 SPACE (SP)` character)

### Option (AltGr on Windows)

```
´¡@£$€¼½¾≠≈¿¬
¤¥€®™☐ü↔︎Ωπå“
√∑∆☒☑︎←↓↑→œæ‘
≤«‹©∫§№µ′…–
```
(Pressing space doesn't type anything, to avoid mistakenly entering non-standard whitespace)

### Option + Shift (AltGr + Shift on Windows)

```
 ¹²³⁴⁵⁶⁷⁸⁹⁰±¦
⋅×÷‰† Ü °¶Å”
 ß       ŒÆ’
≥»›     ″ —
```
(Pressing space types ` `, the `U+00A0 NO-BREAK SPACE (NBSP)` character)
