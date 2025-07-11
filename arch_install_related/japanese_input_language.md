source:

https://forum.endeavouros.com/t/what-packages-should-i-install-to-be-able-to-write-japanese-from-kde-6-and-have-good-integration-with-it/58703/2

steps:

    extra/fcitx5 5.1.10-1 (8.3 MiB 17.3 MiB) [fcitx5-im]
    Next generation of fcitx
    extra/fcitx5-qt 5.1.6-4 (463.5 KiB 1.8 MiB) [fcitx5-im]
    Fcitx5 Qt Library (Qt5 & Qt6 integrations)
    extra/fcitx5-mozc 2.26.4632.102.g4d2e3bd-2 (15.2 MiB 29.4 MiB)
    Fcitx5 Module of A Japanese Input Method for Chromium OS, Windows, Mac and Linux (the Open Source Edition of Google Japanese Input)
    extra/fcitx5-breeze 3.0.0-1 (10.5 KiB 49.0 KiB)
    Fcitx5 theme to match KDE’s Breeze style.
    extra/fcitx5-configtool 5.1.6-1 (513.1 KiB 1.8 MiB) [fcitx5-im]
    Configuration Tool for Fcitx5

After installing it, you have to start fcitx5 if it doesn’t start by itself, go to System Settings–>Keyboard–>Virtual Keyboard and select Fcitx 5 Wayland Launcher:


Then go to System Settings–>Input Method On and click on Add Input Method. Select Mozc and add it.

Then select Mozc, select the configuration and select Language: Japanese and Layout: Japanese

With this you’re done, now you just have to change the keyboard in KDE when you want to use Japanese:
