## Environment
The libraries were generated on debian 11 with gcc 10.2.1-6, qt 6.3.1 and qt 5.15.2.

## Usage

Put the `libfcitx5platforminputcontextplugin.so`  to the path `<QT_INSATLL_PATH>/gcc_64/plugins/platforminputcontexts/`.

And change the permmison:
```shell
chmod 755 libfcitx5platforminputcontextplugin.so
```
The you can enter Chinese characters with fcitx in your qt application now.

(mention: I got both fcitx and fcitx5 installed. I'm not sure whether it maters or not.)