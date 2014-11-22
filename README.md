# Adb Key Monkey

*Fastest Adb Keyboard*

Tool for control android device via PC keyboard

[Download](https://github.com/ckesc/AdbKeyMonkey/releases)

[![Build Status](https://travis-ci.org/ckesc/AdbKeyMonkey.svg?branch=master)](https://travis-ci.org/ckesc/AdbKeyMonkey)

Speed of operation is achieved through the use of [MonkeyRunner API] (http://developer.android.com/tools/help/monkeyrunner_concepts.html)

### Requirement:
Java 7 runtime *(JRE7)*

### How to run
1. Run: `java -jar adbKeyMonkey.jar`

### How to use
When program starts, it connects to first device in adb.
So before run, connect your device via ADB. Execute `adb devices` to verify.

### Keys
* `Up`, `Left`, `Right`, `Down` = `DPAD_UP`, `DPAD_LEFT`, `DPAD_RIGHT`, `DPAD_DOWN`
* `Esc` = Android `BACK`
* `Enter` = `DPAD_CENTER`
* `Backspace` = `Backspace`
* Letter keys = input letter in android


