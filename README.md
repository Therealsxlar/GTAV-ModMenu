# GTAV-ModMenu

This is a basic GTA V mod menu developed using C++ and [ScriptHookV](http://www.dev-c.com/gtav/scripthookv/).  
It allows access to native GTA V functions and custom modding features for single-player use.

## 🚀 Features

- Player options (e.g. Get player name, Clear Wanted Level & God mode) for right now.
- Native GTA V function calls
- ScriptHookV native support
- More coming soon.
  
## 🛠 Requirements

- Grand Theft Auto V (Steam, Epic Games, or Rockstar Launcher)
- [ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)
- [ScriptHookV SDK](http://www.dev-c.com/gtav/scripthookv/)
- Microsoft Visual Studio 2022 (C++) to build the dll.

## 🧩 Installation

1. Build the project in **Release | x64** mode using Visual Studio.
2. Rename the output file from `.dll` to `.asi`.
3. Place the following files in your **GTA V game directory**: If you don't have it, you can download it here: [Download ScriptHookV Files](https://ntscorp.ru/dev-c/ScriptHookV_3504.0_813.11.zip)
- `GTAV-ModMenu.asi` (mod menu)
- `ScriptHookV.dll`
- `dinput8.dll`
- `xinput1_4.dll`

4. Launch GTA V — the mod will load automatically when loaded into GTA-V

5. You're all set!

## ⚠ Disclaimer

This mod is intended for **educational and single-player** use only.
