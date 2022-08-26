[Knights of Pen and Paper +1](https://store.steampowered.com/app/231740/Knights_of_Pen_and_Paper_1_Edition/) is a cool little game, but there are some tedious features about it

1. A secret dungeon vendor which sells endgame equipment has only a 0.001% (!) chance to appear on a 19/20 Castle Sewers dungeon dice roll - this has been changed to 10%
2. You get 800 starting gold bonus on a fresh save file if you have the deluxe/preorder versions - this has been changed to 50000
3. Unlock the deluxe/preorder bonuses regardless of whether you actually own deluxe/preorder dlcs :)

Download from [Releases](https://github.com/hanzbadua/kopp1-patch/releases) and drag-and-drop+replace `Assembly-CSharp.dll` in `GAMEDIRECTORY\knightspp_Data\Managed`

Additionally, this new game DLL has been compiled in Release mode for additional performance (original game binaries were compiled as debug for some reason??)

Tools used to make this: IlSpy 8.0p2 and Visual Studio 2022 (when decompiling with IlSpy, make sure to change the language version to 7.3 as the game has been compiled in .NET Framework 3.5)

Source code unavailable as I can't redistribute source code of a paid game, if you don't trust the patched dll, follow the decompilation steps above and patch it yourself
