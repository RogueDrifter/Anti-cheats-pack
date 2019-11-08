# Rogue-AC

[![sampctl](https://shields.southcla.ws/badge/sampctl-Anti_cheat_pack-2f2f2f.svg?style=for-the-badge)](https://github.com/RogueDrifter/Anti_cheat_pack)

This is a pack of 14 anticheats and 3 helping systems which you can control through callbacks mentioned
in the includes and the test.pwn file.

`Installation`: The Rogue-AC file needs to be included in your gamemode and in all filterscripts, function(s) is/are to be used only within the gamemode.

`Testing`: All can be done through the test.pwn folder which already contains all of the includes and their callbacks nottify you through `SCM` and `print` messages

`Version`: `8.0`

# Installation

Simply install to your project:

```bash
sampctl package install RogueDrifter/Anti_cheat_pack
```

Include in your code and begin using the library:

```pawn
#include <Rogue-AC>
```

# Usage

Use the callbacks provided to you by the includes depending on the type of it.

If you're including the pack as a whole you'll need to only use the callback `OnPlayerViolate`

If you use separate includes you can use the respective callbacks in the test.pwn file.

# Testing

Use the test.pwn file and check the server for client messages/log for printed messages.

To test, simply run the package:

```bash
sampctl package run
```

# Contains:

```
#define VIOLATION_CODE_BUGATTEMPT 0
#define VIOLATION_CODE_LAGOUT 1
#define VIOLATION_CODE_SLIDEBUG 2
#define VIOLATION_CODE_INVALIDMODS 3
#define VIOLATION_CODE_PARTICLESPAM 4
#define VIOLATION_CODE_CARSWING 5
#define VIOLATION_CODE_MONEYHACK 6
#define VIOLATION_CODE_CARTROLL 7
#define VIOLATION_CODE_CARSPAM 8
#define VIOLATION_CODE_AIRBRAKE 9
#define VIOLATION_CODE_SPEEDING 10
#define VIOLATION_CODE_CHATSPAM 11
#define VIOLATION_CODE_JETPACK 12
#define VIOLATION_CODE_FAKECONNECT 13
#define VIOLATION_CODE_FAKEKILL 14
#define VIOLATION_CODE_GODMODE 15
#define VIOLATION_CODE_WEPHACKS 16
```

# How to update:

Simply open your project and run the code:

```bash
sampctl package ensure
```
